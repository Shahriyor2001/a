# CI/CD Pipeline Testing Guide

## Manually Triggering the Workflow

1. **Navigate to the Actions Tab**: Go to your GitHub repository and click on the "Actions" tab.
2. **Select the Workflow**: Find the workflow you want to run (e.g., CI/CD Pipeline).
3. **Run Workflow**: If the workflow is configured to allow manual triggers, you will see a "Run workflow" button. Click it to manually trigger the workflow.

## Testing the Pipeline with Changes

1. **Make a Small Change**: Edit a file in your codebase (e.g., update a comment or add a console log).
2. **Commit the Change**: Use the following commands to commit your changes:
   ```bash
   git add .
   git commit -m "Test CI/CD pipeline"
   git push origin main
   ```
3. **Check Actions Tab**: After pushing, go back to the "Actions" tab to monitor the workflow execution.

## Review Logs

- After the workflow runs, check the logs for each job (lint and test) to ensure everything executed successfully.
