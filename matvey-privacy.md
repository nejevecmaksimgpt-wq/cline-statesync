# Privacy Policy — Matvey Receipts Backup

Last updated: October 24, 2026.

## About the application

Matvey Receipts Backup supports a private Telegram bot, @Matvey_Receipts_Bot, used by its owner to record family expenses, process receipts, produce reports and back up data to Google Drive. The application is not offered as a public service.

## Data processed

The application processes expense amounts, dates, descriptions, receipt photographs, extracted receipt details, generated PDF and spreadsheet reports, and backups of its local expense database. Telegram delivers information submitted by the authorized user. Receipt images or extracted details may be sent to OpenAI for automated recognition.

## Google Drive access

The application connects to the owner's Google Drive using Google OAuth, Google Drive API and rclone. It currently requests the full Google Drive scope (`https://www.googleapis.com/auth/drive`), which technically allows access to files throughout the authorized account. The application is intended to use this permission only for its own receipt originals, reports and database backups inside the dedicated folder «Расходы Матвея».

The application uploads, lists, reads and manages these files for backup and reporting, and may delete specific associated files when the owner requests deletion. Google Drive data is not used for advertising, profiling or unrelated purposes. Files retrieved from Google Drive are not intentionally sent to OpenAI as part of the backup process.

## Storage and access

The main expense database and original receipts are stored on the owner's private server. Backups, receipt originals and generated reports may also be stored in Google Drive. Google OAuth credentials are stored in private application configuration, not in this public GitHub repository. No private receipt records or credentials are published on these pages.

## Sharing

Google Drive is used for backup storage, Telegram carries bot messages, and OpenAI may process submitted receipt images or extracted text to help recognize expenses. The application does not sell Google user data or use it for advertising.

## Retention and deletion

The owner manages stored records, reports and backups. Individual records and associated files may be deleted using the application's available controls or directly within Google Drive; older backup copies may require separate deletion. Google access can be revoked through Google Account security settings. Revoking access stops new authorized Drive operations but does not automatically erase existing files.

## Contact

For privacy questions, contact the application's owner using the support email displayed on the Google OAuth consent screen.
