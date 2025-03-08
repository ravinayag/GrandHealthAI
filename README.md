# GrandHealthAI Assistant

This project implements an intelligent health assistant powered by OpenAI that works via your personal Telegram channel, featuring long-term memory, note-taking capabilities, reminders, and the ability to process voice messages, images, and medical-related documents such as medical bills and diagnostic reports. It serves as your first-level assistant to share and gather opinions about medical symptoms, helping you prepare and become more informed about your health concerns.


## Overview

This health assistant uses n8n workflows to create an AI-powered personal health companion via Telegram as user interface that can:

-   Remember health information through long-term memory storage
-   Save medical notes and reminders
-   Process voice messages via transcription
-   Analyze medical documents (prescriptions, bills, diagnostic reports)
-   Send timely health reminders like medications
-   Provide preliminary guidance on symptoms and health concerns
-   Help you prepare for doctor visits with relevant information

The system consists of two main workflows:

1.  **Main Assistant Workflow** (`GrandHealthAI.json`) - Handles incoming messages and interactions
2.  **Reminder Workflow** (`GranHealthAI-Cron.json`) - Manages scheduled health reminders

## Features

-   💬 **Natural Language Processing**: Understand health queries and provide helpful responses
-   🧠 **Memory Management**: Store health information for future reference
-   📝 **Note Taking**: Save medical instructions and important health information
-   ⏰ **Reminder System**: Set and receive medication and appointment reminders
-   🗣️ **Voice Message Processing**: Transcribe and understand spoken messages
-   📷 **Medical Document Analysis**: Extract information from prescriptions and medical reports
-   🗺️ **India-Specific Health Context**: Tailored to Indian healthcare system

## Prerequisites

-   n8n 
-   Telegram account
-   OpenAI API key
-   Supabase or PostgreSQL database