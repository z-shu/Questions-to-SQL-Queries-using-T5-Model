# Questions-to-SQL-Queries-using-T5-Model

## Overview
Lately, the task of generating SQL query from questions has received a lot of attention and was applied in a variety of domains. However, there was a significant lack of research papers that focused on the healthcare domain. Hence, the aim of the project was to develop a model that is able to transform natural language questions into SQL queries (Question-to-SQL) within the healthcare domain. The Text-to-Text Transfer Transformer (T5) model was utilised and has been evaluated on the Medical Information Mart for Intensive Care SQL (MIMICSQL) dataset.

## Results
The experimental results revealed how  effective the T5 model is, as it was able to achieve an exact match accuracy of 45.7% and 59.3% on the validation and testing datasets respectively, outperforming previous models. Moreover, the T5 model was capable of predicting most of the SQL queries correctly in terms of approximate string matching, achieving an average fuzz ratio score of 98% and 98.5% on the validation set and the test set respectively.