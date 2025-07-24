### Project Title
## Smart Hospital Navigation and Assistant System

## Objective
To develop a web-based system that helps patients and hospital visitors easily navigate hospital premises and receive voice-assisted medical guidance through a smart chatbot trained on common illnesses.

## Target Users
Patients and their relatives

First-time visitors

Hospital reception and help desk staff

##  Key Features
🗣️ 1. Medical Chatbot (LLM-based)
Takes user input about symptoms or illness queries

Trained on 44 common illnesses

Provides preliminary advice and directions

Integrated with Hugging Face LLM + Transformers

Text-to-speech support for accessibility

## Hospital Indoor Navigation
Navigation system guides users through hospital departments (like OPD, Emergency, Pharmacy, etc.)

Based on NetworkX graph-based pathfinding

Outputs shortest path from current location to destination

Directions presented in plain English (or voice)

## Web Interface
Built using Gradio for fast UI prototyping

Clean, interactive layout with fields for:

Symptom input

Navigation options

Voice toggle

Responsive and user-friendly

## Tech Stack
Component	Technology
Frontend UI	Gradio (Python-based)
Backend Logic	Python
Chatbot Engine	Hugging Face LLM, Transformers
Navigation	NetworkX
Audio Output	Text-to-Speech (TTS)
Dev Environment	Google Colab

## Functional Requirements
FR-1: Medical Chatbot
Shall accept user queries about health symptoms.

Shall return text and speech responses using an LLM.

Shall not provide medical prescriptions (disclaimer shown).

FR-2: Navigation System
Shall allow the user to input a department name or select from a list.

Shall show the shortest path based on hospital graph structure.

FR-3: Text-to-Speech
Shall convert chatbot responses to voice.

Shall allow enabling/disabling voice.

FR-4: UI/UX
Shall be web-based and responsive.

Shall contain sections for chatbot, navigation, and audio control.