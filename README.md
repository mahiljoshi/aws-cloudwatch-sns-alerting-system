# AWS CloudWatch SNS Alerting System

![AWS](https://img.shields.io/badge/AWS-Monitoring-orange)
![CloudWatch](https://img.shields.io/badge/CloudWatch-Alerts-blue)
![SNS](https://img.shields.io/badge/SNS-Notifications-yellow)
![Status](https://img.shields.io/badge/Project-In-Progress-brightgreen)

A basic implementation of AWS monitoring and alerting using CloudWatch and SNS to understand threshold-based notifications for EC2 instances.

---

## Overview

This project demonstrates how AWS CloudWatch monitors EC2 metrics and triggers alerts using SNS when defined thresholds are exceeded.

It focuses on understanding the alerting workflow, alarm state transitions, and how notifications are delivered in real time.

---

## Architecture Flow

EC2 → CloudWatch → SNS → Email Notification

---

## Implementation Summary

- Observed EC2 CPU utilization metrics using CloudWatch  
- Configured CloudWatch alarm based on threshold conditions  
- Set up SNS topic and email subscription for alert notifications  
- Explored alarm state transitions (OK → ALARM)  
- Understood how notifications are triggered based on metric thresholds  

---

## Key Learnings

- Understanding of AWS monitoring and alerting workflow  
- How CloudWatch alarms are configured and triggered  
- Role of SNS in delivering real-time notifications  
- Basic understanding of automated alerting pipelines  

---

## Note

This project focuses on understanding the CloudWatch–SNS monitoring workflow.  
Further enhancements like advanced testing and production-scale setups can be implemented.

---

## Author

Mahil Joshi  
LinkedIn: https://linkedin.com/in/mahiljoshi  
GitHub: https://github.com/mahiljoshi
