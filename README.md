# project-inconsitency-analytics
Analyse a dataset of mismatches

This repo has a csv file with person and company linkedin links. Specifically, where the company of a person's linkedin section didn't match the company linkedin. We've only done a very basic comparison, some of these matches might totally be valid. For example, it's the same company with slightly different links. Maybe the person has jobs at multiple companies, and we've only checked the first.

Your task is to figure out:
1. Are there any valid matches?
2. What is the breakdown of the errors?

You can use this API to scrape both company and personal linkedins: [https://nubela.co/proxycurl/](https://nubela.co/proxycurl/).

I'll give you an API key, but don't add commit it to this repository!