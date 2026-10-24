# Matvey Receipts Backup

Matvey Receipts Backup is a personal-use application supporting the private Telegram bot @Matvey_Receipts_Bot. It records family expenses from receipt photos, produces PDF and spreadsheet reports, and stores original receipts, reports, and database backups in a dedicated folder called «Расходы Матвея» on the owner's Google Drive.

The application uses Google OAuth and the Google Drive API through rclone. Its OAuth configuration requests the full Google Drive scope, which grants technical access beyond the dedicated folder. Intended operations are restricted to the bot's own data and backups. Files can be uploaded, listed, downloaded and deleted at the owner's request.

Receipt images may be analyzed through OpenAI to extract purchase details. No private receipts, records or access credentials are published on this website.

Read our [Privacy Policy](./matvey-privacy.html).

Personal use only.
