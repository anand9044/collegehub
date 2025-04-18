# CollegeHub Documentation Review Agent

## Overview
The CollegeHub Documentation Review Agent is an automated tool designed to help review documentation files in GitHub pull requests. It uses the **Google Gemini API** to analyze text in files (such as `.md`, `.txt`, `.py`) and provides suggestions for grammar, spelling, and clarity improvements.

## Features
- Automatic PR Analysis: The agent extracts documentation-related files from a GitHub pull request.
- AI-powered Review: Using the *Google Gemini model*, the agent identifies issues in the documentation and suggests corrections.
- Interactive Review: Users can interactively select and review files in the pull request.

## Prerequisites
1. GitHub API Key: A GitHub API key is required for authenticating and accessing the GitHub repository.
2. Google Gemini API Key: You need an API key for Google Gemini.

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/anand9044/collegehub.git
   cd collegehub
