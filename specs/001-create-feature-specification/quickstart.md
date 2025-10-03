# Quickstart: Web Support Bot

**Feature**: Web Support Bot
**Date**: 2025-10-03

This document provides a quickstart guide for using the `pocketflow_website_chatbot`.

## Prerequisites
- Dart SDK ^3.9.0

## Installation
1.  Clone the repository:
    ```bash
    git clone https://github.com/limcheekin/pocketflow_website_chatbot.git
    cd pocketflow_website_chatbot
    ```
2.  Install dependencies:
    ```bash
    dart pub get
    ```

## Usage
To run the web support bot, use the following command:
```bash
dart run pocketflow_website_chatbot <start-urls> --question <question>
```

### Example
```bash
dart run pocketflow_website_chatbot https://example.com --question "What is this website about?"
```

### Arguments
- `start-urls`: (Required) A list of one or more starting URLs to crawl.
- `--question`: (Required) The initial question to ask the bot.
- `--allowed-domains`: (Optional) A comma-separated list of domains that the crawler is allowed to visit.
- `--max-iterations`: (Optional) The maximum number of crawling iterations. Defaults to 10.
