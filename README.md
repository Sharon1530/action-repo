# GitHub Actions Webhook Trigger (Techstax Assignment)

This repository contains a GitHub Actions workflow that triggers on:
-> every push to the main branch.
-> every pull request merge into main.

The workflow sends a POST webhook to a Flask-based LLM server hosted in the webhook-repo. The server uses OpenAI to generate smart summaries or changelog-style responses based on the type of event received.
