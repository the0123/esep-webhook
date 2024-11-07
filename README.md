**GitHub to Slack Notification**

This Lambda function integrates GitHub and Slack to notify a Slack channel whenever a new GitHub issue is created. It extracts the issue URL from the GitHub webhook payload and posts a message to Slack using a configured webhook URL.

Setup:

1. Deploy the Lambda function in AWS.
2. Set up the SLACK_URL environment variable with your Slack webhook URL.
3. Configure a webhook in GitHub to trigger the Lambda function on issue events.
