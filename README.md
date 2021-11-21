# The Obscenity List
*by [Surge AI](https://www.surgehq.ai)*

Ever wish you had a ready-made list of profanity? Maybe you want to remove NSFW comments, filter offensive usernames, or build content moderation tools, and you can't dream up enough obscenities on your own.

We're creating the world's largest profanity dataset, in 20+ languages.

## Dataset

This repo contains 1600+ popular English profanities and their variations.

**Columns**
* `text`: the profanity
* `severity_rating`: We asked 5 [Surge AI](https://www.surgehq.ai) data labelers to rate how severe they believed each profanity to be, on a 1-3 point scale. This is the mean of those 5 ratings.
* `severity_description`: We rounded `severity_rating` to the nearest integer. `Mild` corresponds to a rounded mean rating of `1`, `Strong` to `2`, and `Severe` to `3`.

## Future

We'll be adding more languages and profanity annotations (e.g., augmenting each profanity with its severity level, type, and other variations) over time.

## Contact

Need a larger set of expletives and slurs, or a list of swear words in other languages (Spanish, French, German, Japanese, Portuguese, etc)? We love feedback. Post an issue or reach out to profanity@surgehq.ai!

![Profanity Logo](https://github.com/surge-ai/profanity/blob/main/logo.png)

Follow us on Twitter at [@HelloSurgeAI](https://www.twitter.com/@HelloSurgeAI).