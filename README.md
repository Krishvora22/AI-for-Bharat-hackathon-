# 🚀 AI-Powered Serverless Code Review System

An intelligent, fully serverless code review platform that automatically analyzes GitHub Pull Requests using AI and provides actionable feedback on **security, architecture, performance, and best practices**.

Designed for startups, student developers, and small teams, this system delivers senior-level review insights while operating within AWS free tiers.

---

## 📌 Overview

This project implements a serverless architecture on AWS that:

- Processes GitHub webhook events  
- Runs AI-driven code analysis  
- Detects security vulnerabilities  
- Posts automated feedback directly to Pull Requests  

### ✨ Key Goals

- Near-zero operational cost  
- Highly scalable serverless design  
- Automated security scanning  
- Architectural analysis with AI  
- Policy-based enforcement  

---

## 🏗️ Architecture

### High-Level Flow

1. GitHub sends a webhook on PR events  
2. API Gateway validates the request  
3. Review Engine orchestrates analysis  
4. AI + Security + Context analyzers run in parallel  
5. Results are posted back to the Pull Request  

---

## 🔥 Features

### ✅ Automated GitHub Integration
- Triggered on Pull Request updates  
- Posts comments directly on PRs  
- Supports multiple repositories  

### 🤖 AI-Powered Code Analysis
- Detects architectural patterns  
- Identifies best practice violations  
- Maintains context across multiple files  

### 🔐 Security Scanning
- SQL injection detection  
- Hardcoded secrets identification  
- Authentication flaw detection  
- OWASP Top 10 checks  

### 📊 Dashboard & Analytics
- Code quality trends  
- Contributor insights  
- Automation time savings  

### 📜 Policy-as-Code
- YAML / JSON configurable rules  
- Severity-based merge blocking  
- Per-repository configurations  

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|-------------|
| Cloud | AWS Lambda, API Gateway |
| Database | DynamoDB (Single Table) |
| Storage | Amazon S3 |
| Secrets | AWS Secrets Manager |
| AI | Gemini 2.5 Flash |
| Language | Python 3.11 |

---

## ⚙️ System Components

### Review Engine
Coordinates the full review workflow including fetching PR diffs, aggregating results, and posting comments.

### AI Analyzer
Uses Gemini 2.5 Flash to perform intelligent code analysis and recommend improvements.

### Security Scanner
Applies static analysis and rule-based scanning to detect vulnerabilities.

### Context Analyzer
Examines cross-file dependencies and architectural impact.

---

## 🚀 Getting Started

### Prerequisites

- AWS Account (Free Tier recommended)
- GitHub repository
- Python 3.11
- Gemini API access


