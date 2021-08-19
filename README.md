# Slack Pipeline Notification Template

### Description
Template to quickly deploy the resources needed to recieve slack notifications about AWS CodePipeline state changes.
Creates a lambda, a role, and an EventBridge rule.

### Prerequisites
Create a slack incoming webhook for the desired channel.
Open slack > Add apps (left side) > search for "Incoming WebHooks" > add > Add to Slack > choose a channel > Add Incoming WebHooks integration

Copy the webhook url and enter it as a cloudformation parameter when prompted.
Be sure to include the pound sign when entering in the channel as a parameter.