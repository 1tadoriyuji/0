# Data Stream Integration Sync

An automated, serverless data pipeline worker designed to run scheduled data synchronization jobs via GitHub Actions.

## Setup Instructions

1. Go to your repository **Settings** -> **Secrets and variables** -> **Actions**.
2. Click **New repository secret**.
3. Set Name to: `SYNC_CONFIG`
4. Paste the encrypted payload generated from your local dashboard into the Value field.
5. The workflow will automatically run on the defined schedule (or trigger it manually under the Actions tab).
