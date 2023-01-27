# README

## NBA Summary Generator

This is a fun project to try and generate NBA game summaries purely based on a game preview.

It uses a fine-tuned version of GPT2 via Hugging Face, and heavily leans on this example notebook: https://colab.research.google.com/drive/1-rKrpWdBR6lliDbJGObkBHsZgk6t2Thz#scrollTo=8a8d8ded

I am leveraging Amazon SageMaker Studio Lab Notebooks for GPU resources, and the game previews and summaries come from rotowire.com

Initial results are definitely imperfect, but it does a decent job of describing a plausible outcome. The model seems to get confused with some of the more binary components of the description (who won/lost), as well as having numbers add up perfectly. But it does a good job of describing individual player performance, and generally describes a narrative that resembles an NBA game.