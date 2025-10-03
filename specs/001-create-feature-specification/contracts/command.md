# Contract: `pocketflow_website_chatbot` Command

**Feature**: Web Support Bot
**Date**: 2025-10-03

## Command-Line Interface

### `pocketflow_website_chatbot`

#### Description
A command-line tool that acts as a web support bot, answering questions based on the content of a given website.

#### Usage
```
pocketflow_website_chatbot <start-urls> --question <question> [--allowed-domains <domains>] [--max-iterations <iterations>]
```

#### Arguments
- `start-urls`: (Required) A list of one or more starting URLs to crawl.
- `--question`: (Required) The initial question to ask the bot.
- `--allowed-domains`: (Optional) A comma-separated list of domains that the crawler is allowed to visit.
- `--max-iterations`: (Optional) The maximum number of crawling iterations. Defaults to 10.

#### Exit Codes
- `0`: Success
- `1`: General error
- `2`: Invalid arguments