# The Obscenity List
*by [Surge AI](https://www.surgehq.ai)*, the world's most powerful NLP data labeling platform and workforce

Ever wish you had a ready-made list of profanity? Maybe you want to remove NSFW comments, filter offensive usernames, or build content moderation tools, and you can't dream up enough obscenities on your own.

At Surge AI, we help companies build human-powered datasets to train stunning AI and NLP, and we're creating the world's largest profanity list in 20+ languages.

## Dataset

This repo contains 1600+ popular English profanities and their variations.

**Columns**
* `text`: the profanity
* `canonical_form_1`: the profanity's canonical form
* `canonical_form_2`: an additional canonical form, if applicable
* `canonical_form_3`: an additional canonical form, if applicable
* `category_1`: the profanity's primary category (see below for list of categories)
* `category_2`: the profanity's secondary category, if applicable
* `category_3`: the profanity's tertiary category, if applicable
* `severity_rating`: We asked 5 [Surge AI](https://www.surgehq.ai) data labelers to rate how severe they believed each profanity to be, on a 1-3 point scale. This is the mean of those 5 ratings.
* `severity_description`: We rounded `severity_rating` to the nearest integer. `Mild` corresponds to a rounded mean rating of `1`, `Strong` to `2`, and `Severe` to `3`.

## Categories
We organized the profanity into the following categories:
- sexual anatomy / sexual acts (ass kisser, dick, pigfucker)
- bodily fluids / excrement (shit, cum)
- sexual orientation / gender  (faggot, tranny, bitch, whore)
- racial / ethnic (chink, n3gro)
- mental disability (retard, dumbass)
- physical disability (quadriplegic bitch)
- physical attributes (fatass, ugly whore)
- animal references (pigfucker, jackass)
- religious offense (goddamn)
- political (China virus)

## Future

We'll be adding more languages and profanity annotations (e.g., augmenting each profanity with its severity level, type, and other variations) over time.

## Contact

Need a larger set of expletives and slurs, or a list of swear words in other languages (Spanish, French, German, Japanese, Portuguese, etc)? We work with top AI and content moderation companies around the world, and we love feedback. Post an issue or reach out to team@surgehq.ai!

![Profanity Logo](https://github.com/surge-ai/profanity/blob/main/logo.png)

Follow us on Twitter at [@HelloSurgeAI](https://www.twitter.com/@HelloSurgeAI).
