# Manual Approval Testing

This repository contains a minimal GitHub Actions workflow to test the `manual-approval` action from the `feature/configurable-polling-interval-test` branch.

## Usage

The workflow can be triggered manually via `workflow_dispatch`. It will:

1. Create an approval issue
2. Wait for approval from the workflow initiator
3. Continue once approved

## Testing

To test the action:

1. Go to the Actions tab
2. Select "Test Manual Approval" workflow
3. Click "Run workflow"
4. Approve or deny the created issue
5. The workflow will continue based on your decision

