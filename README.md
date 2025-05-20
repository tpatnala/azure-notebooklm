# Azure NotebookLM

## Overview

An Azure version of `Open NotebookLM` using Azure OpenAI and Azure AI Speech.

See original [Open NotebookLM](https://github.com/gabrielchua/open-notebooklm) for more information.

![Azure NotebookLM](./azure-notebooklm.png)

## Prep

Provision following Azure resouces before running the app.

1. Azure OpenAI (gpt-4o) model
   - model version `2024-08-06` or above

2. Azure AI Speech [HD voices](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/high-definition-voices)
   - available regions: East US, Southeast Asia and West Europe.

```
