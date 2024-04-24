---
layout: default
title: ChatGPT QuickSearch Extension
---

{% comment %}
For this page:

- The target users are prospects and end-users who want to use or already using our service

{% endcomment %}

## Overview

ChatGPT QuickSearch Extension is a browser extension that allows you to quickly search the conversation history in ChatGPT by providing a search bar for you. You can simply press <kbd>cmd</kbd> / <kbd>ctrl</kbd> + <kbd>K</kbd> to trigger it. This product is currently in alpha testing. Contact: _mincong.h [at] gmail.com_ to have early access for free.

## Demo

Once you open the search bar, you can enter the query in the search bar and the extension will search results as you type.

![open search bar](/assets/2024-04-24-search-bar-open.png)

The matched content will be highlighted, regardless it's the title of the conversation or the underlying messages. You can press the arrow key up ⬆️ and down ⬇️ to navigate the results and press <kbd>enter</kbd> to visit the conversation.

![highlight results](/assets/2024-04-24-search-bar-results.png)

The logic of data synchronization and data ingestion are handled automatically by our extension.

## Privacy

We collect your identity from Google and OpenAI (first name, last name, email, Google picture, OpenAI user ID, OpenAI organization IDs). We also collect all the conversations that happened in ChatGPT. Your data are stored remotely in our database, located in Paris, France. We don't sell your information to any third-party partners. The only third-party service used is [Datadog](https://app.datadoghq.eu/), an observability service for monitoring the proper functioning of our software. Please contact us by email if you want to delete your account and related data.
