# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a YouTube content creation repository focused on AI agent tutorials using LangChain. The repository contains educational materials demonstrating how to build AI agents with tools like calculators and weather fetchers.

## File Structure

- `langchain_demo.ipynb` - Interactive Jupyter notebook demonstrating LangChain agent creation with step-by-step examples
- `youtube_demo.ipynb` - Additional Jupyter notebook with AI agent demonstrations
- `ai_agent_youtube_script.html` - HTML-formatted script for YouTube video content about building AI agents
- `script.html` - Additional HTML script content (appears to be identical to ai_agent_youtube_script.html)

## Working with Jupyter Notebooks

Since this repository primarily contains Jupyter notebooks, use the following approaches:

### Reading Notebooks
- Use `NotebookRead` tool to examine notebook contents and cell outputs
- Notebooks contain executable Python code demonstrating LangChain concepts

### Editing Notebooks  
- Use `NotebookEdit` tool to modify cells
- Preserve existing cell structure and educational flow
- Maintain code documentation and comments for tutorial purposes

## Key Technologies and Dependencies

The codebase demonstrates:
- **LangChain**: Framework for building AI agents with tools
- **OpenAI**: Language model integration via `langchain_openai.ChatOpenAI`
- **dotenv**: Environment variable management for API keys
- **Agent Types**: Uses `ZERO_SHOT_REACT_DESCRIPTION` for reasoning-based tool selection

### Security Note
The code contains `eval()` usage in calculator functions for educational purposes. This is clearly marked as a demonstration and should be flagged if used in production environments.

## Development Environment

No build tools, package managers, or test frameworks are configured in this repository. This is a simple educational content repository without complex development workflows.

## Content Structure

The materials follow a progressive tutorial format:
1. Basic tool creation (calculator)
2. OpenAI/LangChain setup
3. Agent initialization
4. Tool expansion (weather API simulation)
5. Multi-tool agent demonstrations

When working with this codebase, maintain the educational narrative and step-by-step progression that makes the content accessible to learners.