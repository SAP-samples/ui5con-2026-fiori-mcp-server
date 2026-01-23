[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/ui5con-2026-fiori-mcp-server)](https://api.reuse.software/info/github.com/SAP-samples/ui5con-2026-fiori-mcp-server)
# Hands-on | Create great UX with AI, SAP Fiori elements and the MCP Server for Fiori 

## Description

This repository contains the material for the SAP UI5con [Hands-on | Create great UX with AI, SAP Fiori elements and the MCP Server for Fiori](https://openui5.org/ui5con/bengaluru2026/index.html).  

***

## Overview

In this hands-on tutorial you will work through a set of exercises that highlight the benefits and capabilities of the **MCP servers developed by SAP** to create and modify SAP Fiori applications with the help of AI coding assistants.

You will gain comprehensive knowledge of AI assisted full-stack development, and learn how to use AI Clients to kickstart your SAP Fiori elements agentic application development.

## Using AI during Agentic app Development

We are using Cline as AI client within SBAS and Anthropic claude-4-sonnet LLM (Large Language Model) throughout the exercises. When developing SAP Fiori applications with LLMs, you may encounter situations where a prompt is not executed as intended, or technical errors occur when calling MCP server tools. Knowing how to approach these issues systematically can save time and prevent disruption. Cline and the choosen LLM are powerful assistants for problem resolution.

### General steps in case of issues:

[Detailed steps and examples of resolving common issues](./exercises/troubleshoot/)

1. Verify connectivity:
    - Check if your machine has network access.
    - Confirm that the MCP server is up and running.

2. Approach errors systematically
    - Pause before panicking
        - Use natural pauses when the client asks for approval to inspect the current results and chat history.    
        - Stop execution with the "Cancel" button. You can always proceed from there with a new prompt
    - Identify the source: Check if the issue is:
        - CDS compiler error
        - SQLite/database error
        - Console/browser runtime error

3. Using the LLM to solve an issue
    - The LLM occasionally makes mistakes, or forgets required steps leading to error situations
    - But the LLM can read the terminal output and react to API reponses, and correct error visible there
    - Other issues, like from browser console output, can be resolved by copy-pasting the full error message into the chat and ask for a fix in a prompt
    - LLM works best when exact messages are provided rather than manual descriptions.

4. Use Restore Points if Needed
    - If a solution strategy does not work, you can always restore the files and chat to a previous checkpoint using Cline’s restore functionality.

5. Don’t be afraid to retry an exercise or step after restoring to a checkpoint.

## Exercises

Begin your exercises here. At the end of each section, there is a link to continue to the next section.

- [Getting Started - Setting up your AI Development Environment](./exercises/ex0/)

- [Exercise 1 - Create CAP Project and Fiori List Report App based on Image](./exercises/ex1.0/)
    - [Exercise 1.1 Enable automatic data loading in List Report](./exercises/ex1.1/)
    - [Exercise 1.2 Add new column destination to list report table](./exercises/ex1.2/)
    - [Exercise 1.3 Add Analytical chart to list report page](./exercises/ex1.3/)

- [Exercise 2 - Modify travel object page based on Image](./exercises/ex2.0/)
    - [Exercise 2.1 Add Custom Section with RichTextEditor Building Block](./exercises/ex2.1/)

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2026 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
