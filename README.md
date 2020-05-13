# Replication package for ReadSE internal validity study

Description of Jupyter notebooks:

 - `Generation_of_Survey_Questions.ipynb`: This notebook is used to generate survey questions in qualtrics TXT format.  
 It uses the file `raw_data.json` and it creates the files `raw_data.md` and `data_clean_questions.txt`.

 - `Process_survey_responses.ipynb`: This notebook processes survey responses files (in raw Qualtrics export format) in the folder `survey_results` and writes the file `survey_results_processed.csv`.  
 All questions with reversed paragraph pairs are swapped back to the original direction (the survey response is swapped too).

 - `Survey_responses_analysys.ipynb`: This notebook is used to analyse survey results. It reads the `survey_results_processed.csv` file. It produces two images (in `figures/`) and the file `survey_questions_report.md`.  
 IMPORTANT: all paragraph pairs are swapped so that the readability deltas show a decrease (responses are swapped accordingly).

Description of files:

 - raw_data.json: raw data in JSON format. An array of paragraph pairs. Each element has the following shape:
    ```json
    {
        "_id": "nopqrst0000",
        "documentRepoId": "ghijklm0000",
        "documentRepoName": "paper-research-foo",
        "fkglDelta": 2.0000,
        "freDelta": -1.5000,
        "from": {
            "commitAuthorEmail": "foo.bar@example.com",
            "commitId": "abcdef0001",
            "readability": {
                "fleschKincaidGradeLevel": 20.0000,
                "fleschReadingEase": 3.5000
            },
            "text": "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
        },
        "to": {
            "commitAuthorEmail": "bar.foo@example.com",
            "commitId": "abcdef0002",
            "readability": {
                "fleschKincaidGradeLevel": 22.0000,
                "fleschReadingEase": 2.0000
            },
            "text": "Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
        }
    }
    ```
    Each element represents two successive versions of a paragraph (`from` and `to`). Each version has a text and two readability measurements, and other metadata.  
    The root fields include `freDelta` and `fkglDelta` which are the changes in the two readability metrics.  
    The main `_id` field is used in the survey as the question identifier.

- `raw_data.md`: raw data in a more readable format, generated with the

- `data_clean_questions.txt`: Qualtrics survey questions in TXT format. There are 61 questions in total. A first question simply asks for the respondent's academic level. The following 60 questions are separated in 10 blocks of 6 questions.  
Each block contains three questions and the three reversed versions of those questions (`from` and `to` paragraphs are reversed).  
Each question has as question ID the original `_id` of the paragraph pair (with `-rev` appended for the reversed pairs).

- `survey_results/`: folder containing raw survey results exported from Qualtrics.

- `survey_results_processed.csv`: survey results processed to a more usable format. Each row has the following fields:
    ```yaml
    ResponseId: Qualtrics response id
    qid: question id (original _id of paragraph pair)
    res: survey response (likert)
    Qlevel: academic level of respondent
    was_rev: whether the paragraph was presented reversed
    freDelta: delta in Flesch reading ease
    fkglDelta: delta in Flesch⁠—Kincaid grade level
    from.text, to.text: paragraph texts
    from.FRE, to.FRE: Flesch reading ease of paragraphs
    from.FKG, to.FKG: Flesch⁠—Kincaid grade level of paragraphs
    ```

- `figures/`: survey results plots of counts of values in the likert scale.

- `survey_questions_report.md`: report with all paragraph pairs as seen in the `figures`.