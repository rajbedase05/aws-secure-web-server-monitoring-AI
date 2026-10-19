# aws-secure-web-server-monitoring-AI
Secure Dockerized web server on AWS EC2 with VPC networking, IAM least privilege, CloudWatch monitoring, SNS alerts, and AI-assisted log analysis.
# Secure Web Server on AWS with Monitoring and AI-Assisted Troubleshooting

## Project Overview

This project aims to deploy a secure Dockerized web server on AWS, monitor its performance, receive alerts, and use AI tools to understand logs and troubleshoot problems.

**Project status:** In Progress

## Objectives

- Secure AWS account access using MFA.
- Apply the principle of least privilege with IAM.
- Build a secure network using Amazon VPC and Security Groups.
- Deploy an Nginx web server using Docker on Amazon EC2.
- Monitor server performance using Amazon CloudWatch.
- Send alert notifications using Amazon SNS.
- Use AI-assisted log analysis to support troubleshooting.

## Technologies

- Amazon Web Services (AWS)
- IAM, VPC, EC2
- Docker and Nginx
- CloudWatch and SNS
- Linux and SSH
- Git and GitHub
- AI-assisted troubleshooting

## Architecture

EC2 Web Server → CloudWatch Monitoring → CloudWatch Alarm → SNS Email Notification

AI assistance will be used separately to analyze selected logs and explain potential issues.

## Implementation Progress

- [ ] Enable root account MFA.
- [ ] Configure an AWS budget alert.
- [ ] Set up appropriate IAM permissions.
- [ ] Configure the VPC and Security Groups.
- [ ] Deploy the Dockerized Nginx web server.
- [ ] Configure CloudWatch monitoring and alarms.
- [ ] Configure SNS email notifications.
- [ ] Test monitoring and document troubleshooting.
- [ ] Upload evidence screenshots.

## Security Practices

- Restrict SSH access to my own public IP.
- Use least-privilege permissions.
- Never commit AWS access keys, passwords, or private SSH keys.
- Remove sensitive information from logs before sharing them with AI tools.
- Review AWS costs and clean up resources after testing.

## Project Evidence

Screenshots, configuration examples, testing results, and troubleshooting notes will be added as each stage is completed.

## Learning Outcomes

This project is designed to develop practical skills in AWS administration, Linux, Docker, cloud monitoring, basic security, troubleshooting, and technical documentation.
