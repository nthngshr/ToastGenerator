# Toasts Generator

For the past few years I've been preparing a New Year pet-project. Whereas for 2021 it was an analysis of all the President's New Year's speeches (no politics) to summarise and highlight the main idea, then for 2022 it is a toast generator.

For this I use sberbank-ai/rugpt3medium_based_on_gpt2. Here, the idea is to learn how to generate toast without a manually specified prompt and to end each toast at the end_of_text marker. 

I based the idea on these two articles:
1. https://towardsdatascience.com/teaching-gpt-2-a-sense-of-humor-fine-tuning-large-transformer-models-on-a-single-gpu-in-pytorch-59e8cec40912
2. https://towardsdatascience.com/how-to-fine-tune-gpt-2-for-text-generation-ae2ea53bc272

My original dataset is small, only 1073 toasts I copied from various strange sources, if I find where to get more, it will be larger (yours truly, captain obvious).

Here, some examples from January on the same dataset to see how the model works. It’s worth noting here that no end_of_text was added in January, the beginning of the toast was set manually and manually copied. There were no model evaluation, just checking the idea.

- Если у вас сломался телевизор, то вы можете поехать на нем посмотреть новогоднюю программу. Но если вы не купите новый телевизор, то вам придется поехать на нем в кинотеатр. Так выпьем за то, чтобы в новом году мы всегда были в центре событий!
- Муж пришел с работы уставший, но довольный. Жена налила ему рюмку водки. – Выпьем за то, чтобы в новом году нам всегда хватало сил на что-нибудь хорошее!
- Друзья! Предлагаю выпить за то, чтобы в новом году наши враги никогда не забывали, с кем имеют дело! Давайте выпьем за то, чтобы в новом году наши враги не забывали, с кем имеют дело!

The project is under construction. New results on their way.
