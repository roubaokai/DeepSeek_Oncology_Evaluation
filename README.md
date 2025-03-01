# DeepSeek_Oncology_Evaluation
This repository provides a set of automated scripts to evaluate DeepSeek and its distilled models for answering medical questions. Files: test.jsonl: Contains 1206 multiple-choice questions and their corresponding correct answers on oncology. Evaluation.py: Script for DeepSeek and its distilled models through SiliconFlow via API.

1.Prerequisites: Ensure you have Python installed (preferably Python 3.7+). Install necessary Python libraries: "pip install openai tqdm"

2.Configuration: In Model_Evaluation.py, update the following variables: api_key: Set this to your API key. model_name: Set the model name you wish to evaluate.

3.Run the Evaluation: Place test.jsonl and both .py files in the same directory. Execute the appropriate script for evaluation: "python Model_Evaluation.py"

4.Results: After running the scripts, the evaluation results will be saved as .jsonl files: model_evaluation_results.jsonl. These files contain both the summary statistics and detailed evaluation for each question, including accuracy, consistency,latency and token usage.
