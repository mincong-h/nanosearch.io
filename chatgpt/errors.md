---
layout: default
title: Error Catalog
description: Troubleshooting the ChatGPT QuickSearch Extension
---

{% comment %}
Inspired by https://cloud.google.com/looker/docs/error-catalog
{% endcomment %}

The table below is a collection of some common error messages that surfaced in the ChatGPT QuickSearch Extension, explanations of their underlying causes and where they occur, and troubleshooting resources. The errors appear according to how frequently they are reported to Nanosearch Support, in descending order, starting with the greatest number of support requests at the top.

## Account Not Connected {#CS-001}

Error code: `CS-001`

Error message:

> The extension is not usable yet, consider reloading your ChatGPT tab to trigger to connection.

It means that the backend service of the ChatGPT QuickSearch Extension cannot recognize the user's account information of OpenAI, including the OpenAI user ID and organization IDs. These pieces of information are essential for data processing, data storage, and data retrieval. When it occurs, the extension is unusable. Usually, the action of connecting OpenAI account information to the backend service is handled automatically by the extension without manual intervention. If it is not working, you should consider:

1. Reload the browser tab in which ChatGPT is opened
2. If the previous step is not working, sign out from the browser extension and sign in again
3. Contact support
