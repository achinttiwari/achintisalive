# Achintisalive: AI Socratic Tutor for Secure Coding 🛡️💡

## Overview
Achintisalive is an AI-powered educational co-pilot designed to solve the lack of personalized feedback in secure coding. Built for the Gen AI Academy APAC, it acts as a Socratic tutor—analyzing code snippets for security vulnerabilities and algorithmic inefficiencies, and guiding users to the solution through hints rather than just providing the corrected code.

## The Problem
Developers and students working through technical skill roadmaps often hit roadblocks when their code fails security checks. Traditional AI tools instantly generate the fixed code, bypassing the learning process. Achintisalive encourages active learning by teaching *how* to think securely.

## Key Features
* Vulnerability Spotter: Flags common security risks (e.g., SQL injections, XSS, hardcoded credentials) and inefficiencies.
* Socratic Tutor Mode: A step-by-step hint system that gently guides the user toward the solution without revealing the raw code fix.
* Interactive Code Remediation: Validates updated code and explains the secure principles behind the new approach.

## Tech Stack & Architecture
* Frontend UI: Streamlit (Python)
* Core AI Engine: Google Gemini 1.5 Flash API (via Google AI Studio)
* Deployment: Google Cloud Run (Containerized via Docker)

## Project Status: Work in Progress 🚧
This repository is currently under active development. 

## Getting Started (Coming Soon)
Once the initial code is pushed, you will be able to run this locally:

1. Clone the repository: 
   git clone https://github.com/achinttiwari/achintisalive.git
2. Navigate to the directory:
   cd achintisalive
3. Install dependencies: 
   pip install -r requirements.txt
4. Set your Google Gemini API key:
   export GEMINI_API_KEY="your_api_key_here"
5. Run the app: 
   streamlit run app.py

## Live Demo
[Deployment URL will be added here once deployed to Google Cloud Run]
