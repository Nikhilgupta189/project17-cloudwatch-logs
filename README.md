
## CloudWatch Dashboard
Created a CloudWatch Logs Insights dashboard named
project17-log-dashboard using AWS CLI.

Command:
aws cloudwatch put-dashboard \
  --dashboard-name project17-log-dashboard \
  --dashboard-body file://dashboard.json \
  --region ap-south-1

Result:
DashboardValidationMessages: []

The dashboard configuration was accepted successfully.
AWS Console access to logs was restricted by IAM permissions.
