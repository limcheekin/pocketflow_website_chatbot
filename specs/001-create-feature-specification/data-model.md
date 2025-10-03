# Data Model: Web Support Bot

**Feature**: Web Support Bot
**Date**: 2025-10-03

## Entities

### Webpage
Represents a single URL with its extracted text content and a list of links it contains.

- `url`: String (The URL of the webpage)
- `content`: String (The text content of the webpage)
- `links`: List<String> (A list of hyperlinks found on the webpage)

### Question
The user's query.

- `text`: String (The text of the user's question)

### Answer
The bot's response.

- `text`: String (The text of the bot's answer)
- `type`: Enum (e.g., `direct`, `clarification`, `refusal`)

### Conversation
A record of the back-and-forth between the user and the bot.

- `history`: List<Pair<Question, Answer>> (A list of question-answer pairs)
