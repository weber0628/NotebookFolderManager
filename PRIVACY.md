# Privacy Policy for NotebookFolderManager

## Overview
NotebookFolderManager is a browser extension designed to help users organize their NotebookLM notebooks into folders and manage conversation sources with support for multiple export formats.

## Data Collection & Storage

### Local Storage
- **Storage API**: NotebookFolderManager uses Chrome's `storage.sync` API to store folder organization data locally on your device
- **Stored Data**:
  - Folder names and metadata
  - Notebook organization preferences
  - Emoji and color selections for folders
  - Collected conversation sources (locally cached)
  
- **No Cloud Transmission**: Your local folder organization data never leaves your device
- **No Personal Information**: We do not collect email addresses, usage analytics, or any personal identifiable information
- **No Third-Party Sharing**: Your local data is never shared with third parties

### Google Drive Integration (Optional)
- **When Converting to Google Docs**: If you choose to use the "Convert to Google Docs" feature, the extension will:
  - Request your Google account identity to authenticate with Google Drive
  - Create a new document in your Google Drive with the collected sources
  - The document is stored directly in your Google Drive account under your control
  - You can manage or delete these documents anytime through your Google Drive settings

- **Data Handling**:
  - Only the selected source information is sent to Google Drive
  - Google controls the storage and privacy of documents in your Google Drive
  - Please refer to [Google Privacy Policy](https://policies.google.com/privacy) for Google Drive data handling practices

## Permissions Explanation
- **storage permission**: Required to persist your folder organization data across browser sessions and sync across your devices using Chrome Sync
- **clipboardWrite permission**: Used to enable quick-copy functionality when collecting sources and exporting data. Allows copying source titles, URLs, and summaries to your clipboard for convenient pasting
- **identity permission**: Used exclusively for Google Drive authentication when you opt to use the "Convert to Google Docs" feature. Enables secure OAuth 2.0 authentication without requiring password entry

## Data Deletion
- **Local Data**: All local folder organization data is stored in your Chrome profile. Uninstalling the extension will completely remove all associated data
- **Google Drive Documents**: Documents created via the "Convert to Google Docs" feature are stored in your Google Drive. You must manually delete them through Google Drive if you wish to remove them

## Third-Party Services
- **Google Drive**: Optional integration only when you actively choose to convert sources to Google Docs. Governed by Google's privacy policy

## Contact
For privacy concerns, please visit our GitHub repository.

## Last Updated
January 2026
