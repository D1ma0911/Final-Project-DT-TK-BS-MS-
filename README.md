# Final-Project-DT-TK-BS-MS
## Book Study Companion API

This workflow functions as a backend service that generates a comprehensive study guide for a specific book. Triggered by a webhook containing a book title, it aggregates data from multiple sources to provide a summary, educational resources, and interactive content.

## Upon receiving a request, the workflow splits into three parallel processes:

Wikipedia Lookup: Searches for the book to retrieve a concise summary and cover image.

Video Resource Fetching: Queries the YouTube API to find top-rated literary analysis essays and videos related to the title.

AI Quiz Generation: Uses Google Gemini to spell-check the title and generate a custom trivia quiz in JSON format.

## Output
The data from all three branches is merged into a single, clean JSON object containing the corrected title, book summary, a list of relevant YouTube videos, and the generated quiz, which is returned to the requester.

[Project presentanion link](https://github.com/user-attachments/files/24964678/Final_projectIIT1.pdf)
