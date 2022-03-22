# CommonSense-Question-Answering-by-FineTuningBert

The Commonsense Question Answering project is based upon the OpenBookQA dataset modeled on an “open book” middle-school science exam” format (see https://aclanthology.org/D18‐1260.pdf). Multiple-choice questions are posed based upon one of 1326 facts.

We have trained two models:
Fact = 1. Model to use knowledge from an accompanying fact along with commonsense to answer the questions.
Fact = 0. Model to use only commonsense to answer the questions.

We have fine-tuned the BERT model for common-sense question answering.

We got a baseline accuracy of 55% and 69% for fact = 0 and fact = 1 respectively.

We then attempted a different approach by pre-training the model on a modified version of the CommonSenseQA model then incrementally finetuned the model on the OpenBookQA to get improved accuracies of 58% and 71% for fact = 0 and fact = 1 respectively.

Please refer to Report.pdf for a detailed explanation.
