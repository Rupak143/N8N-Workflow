# N8N-Workflows

#1. YouTube Automation with Google Drive using n8n

This project automates uploading videos from Google Drive to YouTube using n8n.

## Features

- Auto upload videos to YouTube
- Google Drive integration
- Google Sheets queue system
- Scheduled uploads
- Automatic status updates
- Fully automated workflow

## Workflow

Google Sheets → Google Drive → YouTube → Update Status

## Tech Stack

- n8n
- Docker
- Google Drive API
- Google Sheets API
- YouTube Data API v3

## Setup

1. Install n8n using Docker
2. Connect Google credentials
3. Import workflow JSON
4. Add video details to Google Sheets
5. Activate workflow

## Status Queue

- Pending → Ready for upload
- Uploaded → Successfully uploaded
- Failed → Upload failed

## Author

Built with n8n automation.
