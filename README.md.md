# AI-Powered Content Creator Agent using n8n

## Overview

This project automates content creation using n8n. It fetches topics from Google Sheets, performs research using Tavily API, and generates platform-specific content using OpenAI.

## Workflow Steps

1. Fetch topic from Google Sheets (Status: Pending)
2. Perform web research using Tavily API
3. Process data using Split Out and Aggregate nodes
4. Generate content using OpenAI:

   * LinkedIn Post
   * X (Twitter) Post
   * Blog Summary
5. Update Google Sheet with generated content and mark as Completed

## APIs Used

* Tavily Search API
* OpenAI API

## Sample Input

Topic: AI in Healthcare

## Sample Output

* LinkedIn: Generated professional post
* X: Short tweet
* Blog: 150-200 word summary

## Prompt Design

* LinkedIn: Professional tone
* X: Short and engaging
* Blog: Informative and detailed

## Notes

* No API keys are included for security
* Workflow runs end-to-end automatically
