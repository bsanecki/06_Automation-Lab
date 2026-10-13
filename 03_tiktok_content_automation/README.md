# 03 - TikTok Content Publishing Automation

An automated social media publishing workflow built with Activepieces, designed to organize content stored in Google Drive and prepare posts for TikTok.

## Features

- **Scheduled execution** — runs automatically on a predefined schedule.
- **Google Drive integration** — retrieves post folders, images, and metadata.
- **Content processing** — uses code steps to process post data and prepare publishing content.
- **Image handling** — loops through multiple images and collects them for a post.
- **Publishing integration** — includes a LetMePost publishing step.
- **State management** — uses storage steps to manage data between workflow actions.
- **Discord notifications** — sends messages through Discord as part of the workflow.

## Workflow

1. Trigger the workflow on a schedule.
2. Retrieve and process files from Google Drive.
3. Identify content and prepare publishing data.
4. Download and collect images using a loop.
5. Retrieve the prepared data and pass it to the publishing step.
6. Update Google Drive and process remaining content.
7. Send a Discord notification.

## Technologies

- Activepieces
- Google Drive
- JavaScript / Code steps
- Storage
- LetMePost
- Discord
