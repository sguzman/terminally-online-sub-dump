# Terminally-Online Sub Dump

## Executive Summary

A set of RSS feeds for terminally online ppl like me to track online stuff and news about the world

## Explanation

### What is this?

I am terminally-online 🫢. So I have made this repo to track the online stuff I care about. I am using RSS feeds for the process and [Newsboat](https://newsboat.org/) to read them. I have also made a script to generate the feeds from the list of sources I have.

I have a directory for each domain. So for example,

- YouTube channels are in [youtube](data/youtube/)
- Twitter accounts are in [twitter](data/twitter/)
- Reddit subreddits are in [reddit](data/reddit/)
- News sites are in [news](data/news/)
- Blogs are in [blogs](data/blogs/)
- Podcasts are in [podcasts](data/podcasts/)
- GitHub repos are in [github](data/github/)
- Books are in [books](data/books/)
- Movies are in [movies](data/movies/)
- TV shows are in [tv](data/tv/)
- Music is in [music](data/music/)
- Games are in [games](data/games/)
- Comics are in [comics](data/comics/)
- Seeking Alpha articles are in [seekingalpha](data/seekingalpha/)
- Trading Economics are in [tradingeconomics](data/tradingeconomics/)

### How to use this?

Each directory functions as a complete domain. So you can use the RSS feed of the directory to track the domain. For example, you can use the RSS feed of [youtube](data/youtube/) to track all the YouTube channels I track. I use this alias to open the feed in Newsboat:

```sh
alias nb='newsboat --url-file=./urls --log-file=./output.log --log-level=5'
```

You don't need all the options. The goal is to make Newsboat `instanced-based`. So a different instance opens the feeds of a different domain.

### How to contribute?

Idk 🤷🏼

### What do I track?

The domains that I track are sites or apps or platforms that I feel contribute to world affairs or track them. I am nosy and like to track everything.

### Why do I track?

Eventually, I plan to do some automated reasoning on the data. I am not sure what I will do with it. But I will do something. I want to be able to predict the future based on what is currently happening and also make money on predict markets.