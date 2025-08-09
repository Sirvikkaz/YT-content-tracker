# yt content tracker

This workflow uses **n8n** to:
1. Monitor an youtube channel and gives update in the new uploads every 5 hours(you can tweak to your preferred no of hours).
2. Log the title, link, summary, and publish date into Google Sheets.
3. Send an email notification every 5 hours.

## Requirements
- n8n (self-hosted or n8n cloud)
- Google account with Sheets API enabled

## How to Use
1. Download the `YT content tracker.json` file.
2. In your n8n dashboard, click **Import** and select the file.
3. Set up your credentials for:
   - Google Sheets
   - Gmail
   - your prefered channel RSS link in this format (https://www.youtube.com/feeds/videos.xml?channel_id=CHANNEL_ID), replace "CHANNEL_ID" with actual CHANNEL_ID
4. Activate the workflow.

## Example Output
![Workflow Screenshot](wkflow1.jpg)

## Author
**Olanrewaju Victor Bayode**  
GitHub: [Sirvikkaz](https://github.com/Sirvikkaz)
