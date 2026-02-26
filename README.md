# FollowUp AI – Serverless Reminder System

FollowUp AI is a serverless application that helps users create, manage, and receive intelligent follow-up reminders using AWS cloud services.

## Architecture Overview
The system uses a fully serverless architecture:
- Amazon API Gateway to receive user requests
- AWS Lambda for request processing and scheduling logic
- Amazon DynamoDB to store follow-up tasks and schedules
- Amazon EventBridge to trigger scheduled reminders
- Amazon Bedrock to generate AI-powered reminder messages
- Amazon SNS to send email notifications

## Key Benefits
- Fully serverless and scalable
- Low operational cost using AWS Free Tier
- Event-driven and automated
- Easy to extend with SMS, WhatsApp, or mobile notifications

## Use Cases
- Freelancers following up with clients
- Sales teams managing leads
- Job seekers tracking applications
- Personal productivity reminders

## Status
This project is in prototype stage and designed for demonstration, learning, and early-stage startup validation.
