---
title: Introducing pandas-log
layout: post
date: '2019-10-23 00:00:00'
permalink: introducing-pandas-log/
---

The pandas ecosystem has been invaluable for the data science ecosystem, and thus today most data science tasks consist of series of pandas’ steps to transform raw data into an understandable/usable format.

These steps’ accuracy is crucial, and thus understanding the unexpected results becomes crucial as well. Unfortunately, the ecosystem lacks the tools to understand those unexpected results.

That’s why I created Pandas-log, it provides metadata on each operation which will allow pinpointing the issues. For example, after .query it returns the number of rows being filtered.

You can find the post here: [Introducing pandas-log](https://towardsdatascience.com/introducing-pandas-log-3240a5e57e21)

Let me know what you think, and feel free to reach out with any feedback. 
