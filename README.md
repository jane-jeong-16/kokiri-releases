# Kokiri - A User-Friendly DB GUI
<img width="100" alt="image" src="https://github.com/user-attachments/assets/f13f4524-1386-4405-8edb-a2812edf56a2" />

(Kokiri means "elephant" in Korean! Inspired by Postgres's Elephant icon. Kinda looks like its baby 🐘 🍼 ) <img width="20" alt="image" src="https://github.com/user-attachments/assets/71e7550a-c285-45c6-baf1-c428a8a1bd73" />

Kokiri is just a personal project I made because I wasn't a big fan of any of the postgres editors I was using. My pain points:
1. AWS SSM support - I couldn't find anything that would help us do this without writing a script myself and also consistently refresh connections
2. they were just very monochrome and grey and sad :(

## Download - (currently available only for macOS, Apple Silicon)

**[⬇︎ Latest release](https://github.com/jane-jeong-16/kokiri-releases/releases/latest)** — macOS (Apple Silicon)

Updates are auto-detected on launch!

## Requirements:
- currently available only for macOS, Apple Silicon
- DB support: PostgreSQL, MySQL (beta - not fully tested)
- Connection types: SSH, Direct, AWS SSM, and scripts

## My favorite features

### 🤖 AI Assistant
The AI Assistant knows your schema inside and out, and can help you build complex queries pretty quickly.

### 🤝 "Join on Join on Join" views
Generates combined views that are easy on the eyes especially when you have multiple levels of one-to-many relations.

### 🔄 AWS SSM connection auto-management 
If you have your database access in RDS within a VPC that you have to access through a bastion and have to keep running `aws sso login`, this will do it automatically for you.

### ✅ Auto-complete
Pretty traditional feature, but depending on what you type, it'll

### 💾 Easy query saving
Most db guis save whole query documents. Kokiri allows you to save specific segments of sql to reuse - for example, if you use a common join very frequently, add that and type '\' to insert it instantly.

### 🔒 Security
- The AI Assistant uses your own API Key, so only your AI account access your AI query history.
- SSL enabled
- All secrets stored in OS keystore
- Auto-updates enabled by default

