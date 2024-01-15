# TikTok, the Israel-Hamas conflict and antisemitism 

This repo contains data and analysis connected to the spread of pro-Palestinian vs pro-Israel content on TikTok. And the contection between TikTok and the current rise in antisemitism. 

## Background

Survey data suggests TikTok is a meaningful driver of the current surge in antisemitism. The survey finds that spending 30 minutes a day on TikTok increases the chances somebody holds anti-Semitic or anti-Israel views by 17%, compared with 6% for Instagram and 2% for X - though it must be noted that each of these platforms have vastly different demographic characteristics (TikTok has a primarily younger audience, with 41% of users aged between 16 and 24, and 50% under the age of 34, while Instagram has a more diverse audience, with 33% of users aged between 25 and 34 and 30% between 18 and 24). Without normalizing these samples against survey data taken from a general member of the demographic of each platform any statements made about whether or not the platform is causal are essentially bunk.

Survey was conducted between November 21 and November 27. It includes 1323 people aged between 18 and 29. 

![Correlation between social media use and antisemtism](https://github.com/antgoldbloom/tiktok_israel_hamas/blob/main/charts/correlation_between_social_media_and_antisemitism.png)

A likely driver here is that for every video view with a pro-Israel hashtag in the US, there are 54 views with pro-Palestinian hashtags. 

![Ratio of pro-Palestinian views to pro-Israel views](https://github.com/antgoldbloom/tiktok_israel_hamas/blob/main/charts/20231210_us_top_hashtags_israel_hamas.png)

Given TikTok’s scale, it’s not surprising that this imbalance of spread corresponds to an increase in antisemitism. Though it may also be the case that this is simply a correlation and TikTok is not the cause, but rather the effect of Israel's actions. Given Israel's self-proclaimed status as a representative of the Jewish people, paired with it's vicious indiscriminate bombing campaign yielding thousands of civilian deaths, it should be no surprise that anti-semitism is on the rise and such a rise would obviously be reflected on social media platforms - especially those with a more liberal and youthful demographic.


![TikTok scale by comparing with mainstream media](https://github.com/antgoldbloom/tiktok_israel_hamas/blob/main/charts/free_palestine_vs_mainstream_media.png)

## Data

Data in this repo:
1. [raw survey file](data/generation_lab_survey/raw_survey_1323.xlsx)
2. [clean survey file](/data/generation_lab_survey/survey_israel_questions_clean.csv)
3. [tiktok hashtag by country file](/data/tiktok_hashtags/tiktok_hashtags_by_country_20231127_clean.csv.gz) 

## Notebooks

1. [social media survey notebook](social_media_survey_notebook.ipynb)
2. [tiktok hashtag notebook](tiktok_hashtag_notebook.ipynb)