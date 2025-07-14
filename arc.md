# ALERTIFY: Serverless Alert System for Disaster Events

``
IoT Device (Vibration Sensor)
       |
   [API Gateway] <-- Public APIs (earthquake/weather)
       |
   [AWS Lambda Function]
       |
  -----------------------------
 | DynamoDB (Processed Alerts) |
 | S3 (Historical Logs)        |
 | SNS (Real-time Notifications) |
  -----------------------------
       |
[CloudFront] --> Public Dashboard
``
