# Chapter 5: Pretraining on Unlabeled Data

&nbsp;
## Main Chapter Code

- [01_main-chapter-code](01_main-chapter-code) contains the main chapter code

&nbsp;
## Bonus Materials

- [02_alternative_weight_loading](02_alternative_weight_loading) contains code to load the GPT model weights from alternative places in case the model weights become unavailable from OpenAI
- [03_bonus_pretraining_on_gutenberg](03_bonus_pretraining_on_gutenberg) contains code to pretrain the LLM longer on the whole corpus of books from Project Gutenberg
- [04_learning_rate_schedulers](04_learning_rate_schedulers) contains code implementing a more sophisticated training function including learning rate schedulers and gradient clipping
- [05_bonus_hparam_tuning](05_bonus_hparam_tuning) contains an optional hyperparameter tuning script
- [06_user_interface](06_user_interface) implements an interactive user interface to interact with the pretrained LLM
- [07_gpt_to_llama](07_gpt_to_llama) contains a step-by-step guide for converting a GPT architecture implementation to Llama 3.2 and loads pretrained weights from Meta AI
