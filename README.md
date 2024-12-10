## Restoring Sentiments: Understanding Citizens’ Response to Social Activities on Twitter in U.S. Metropolises During the COVID-19 Pandemic Using Fine-tuned Large Language Model

This repository contains the source codes for the research article entitled [Restoring Sentiments: Understanding Citizens’ Response to Social Activities on Twitter in U.S. Metropolises During the COVID-19 Pandemic Using Fine-tuned Large Lan-guage Model by Ryuichi Saito and Sho Tsugawa](https://doi.org/10.2196/preprints.63824). This work is currently a preprint and under peer-review.

This repository include the codes as follows:
1. Data Collection
   - full_archive_search_nyc.ipynb
   - full_archive_search_la.ipynb
   - full_archive_search_chicago.ipynb
   - unique_users.ipynb
2. Create Training Data
   - join_tweets_separated_by_restriction_type.ipynb
   - create_csv_for_amazonmturk.ipynb
   - prepare_training_and_test_data.ipynb
   - convert_tsv_to_jsonl_for_gpt3_5_finetuning.ipynb
3. Create Models
   - roberta_large_fine_tuning.ipynb
4. Evaluatate Models
   - roberta_large_fine_tuning_accuracy.ipynb
   - gpt_3_5_turbo_accuracy.ipynb
5. Sentiment Classification
   - sentiment_classifier_gpt_3_5_turbo.ipynb 
6. TF-IDF for Sentiment Classification Results
   - tf_idf.ipynb
   
> GPT 3.5 Turbo with fine-tuning is trained on the Open AI console, so the code is not included in this repository.
