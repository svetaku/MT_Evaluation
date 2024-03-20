# GPT-3.5-Turbo Machine Translation Evaluation

## Overview
This repository contains the code and data for evaluating machine translations generated by OpenAI's GPT-3.5-Turbo model using parallel corpora of English texts from various fields (literature, medical, law) and their corresponding human translations to Russian. The evaluation aims to determine the effectiveness of different prompts in generating accurate translations and to identify which prompt performs better in each field.

## Methodology
1. **Data Collection**: 
   - Parallel corpora of English texts and their human translations to Russian were collected from diverse fields including literature, medical, and law.

2. **Machine Translation**:
   - GPT-3.5-Turbo was employed for machine translation from English to Russian using two different prompts.

3. **Manual Alignment**:
   - The original English texts, their human translations, and machine translations were manually aligned at the sentence level to create a reference dataset for evaluation.

4. **Evaluation**:
   - The quality of machine translations was assessed using the BLEU (Bilingual Evaluation Understudy) metric, comparing machine translations against human translations.

5. **Analysis**:
   - Statistical analysis was performed to compare the BLEU scores obtained from different prompts across various fields, aiming to determine the most effective prompt for each field.
