# AWS CloudWatch SNS Alerting System

## Overview
This project demonstrates real-time monitoring of AWS EC2 instances using CloudWatch and automated alerting using SNS.

## Architecture
EC2 Instance → CloudWatch Metrics → Alarm → SNS → Email Notification

## Services Used
- Amazon EC2
- CloudWatch
- SNS

## Key Features
- Monitored EC2 CPU utilization metrics  
- Configured CloudWatch alarms for threshold-based alerts  
- Integrated SNS for real-time email notifications  
- Tested alert triggering using simulated high CPU usage  

## My Contributions
- Implemented monitoring and alerting workflow  
- Configured CloudWatch alarms and SNS integration  
- Analyzed system metrics and alert behavior  

## Future Improvements
- Add multi-metric monitoring (memory, disk usage)  
- Integrate with AWS Lambda for automated response  
