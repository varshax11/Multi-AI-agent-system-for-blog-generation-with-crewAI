#Multi AI Agent System for Blog Generation with CrewAI

A powerful automated blog content generation system built with CrewAI and Cohere LLM. This project orchestrates multiple AI agents to plan, write, and edit high-quality blog content on any topic.

## Overview

This system creates a collaborative AI workflow with three specialized agents:
- **Content Planner**: Researches and outlines content strategy
- **Content Writer**: Crafts engaging blog posts based on the planner's work
- **Editor**: Reviews and refines the content for quality and consistency

## Features

- Fully automated end-to-end content creation pipeline
- Multi-agent coordination through CrewAI framework
- Factually accurate and engaging content production
- SEO optimization built into the planning process
- Balanced editorial review process

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/crewai-blog-generator.git
cd crewai-blog-generator

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set your Cohere API Key in the environment variables:
export COHERE_API_KEY="your-cohere-api-key"

## License
This project is licensed under the MIT License - see the LICENSE file for details.
