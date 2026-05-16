# Day 16 - GitHub Webhook Integration

## Goal
Trigger Jenkins build automatically from GitHub push events

## What I Did
- Connected GitHub webhook with Jenkins
- Triggered pipeline automatically on code push

## Pipeline Stages
1. Clone Repository  
2. Build Application  

## Concepts Learned
- GitHub webhooks
- Automatic build triggers
- Continuous Integration workflow

## Jenkins Configuration
Enable:
- GitHub hook trigger for GITScm polling

## GitHub Webhook URL
http://<jenkins-url>/github-webhook/

## Output
Pipeline starts automatically after git push