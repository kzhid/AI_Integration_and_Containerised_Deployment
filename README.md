# AI Integration and Containerised Deployment

This project demonstrates the integration of advanced AI models and containerised deployment using Open WebUI and Ollama. The project includes the optimization of embedding and instructional models, as well as the integration of personalized financial insights.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Model Information](#model-information)
- [Embedding Books](#embedding-books)
- [References](#references)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository showcases an AI-powered financial education and planning assistant, utilizing advanced AI models for personalized financial insights. The project leverages Docker for scalable deployment and performance optimization, with Open WebUI as the interface and Ollama for model management.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Docker](https://docs.docker.com/get-docker/)
- [Open WebUI](https://github.com/open-webui/open-webui)
- [Ollama](https://ollama.com/docs/overview)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kzhid/AI_Integration_and_Containerised_Deployment.git
   cd AI_Integration_and_Containerised_Deployment
   ```
   important: i did not add the modelfile's themselves in this repository, so use your own on ollama, however iv left the modelfile config and other files for learning purposes.
  
2. **Set up Docker container for Open WebUI:**

   Follow the instructions in the [Open WebUI documentation](https://github.com/open-webui/open-webui) to set up and run the Docker container.

3. **Install Ollama:**

   Install and set up Ollama by following the [Ollama documentation](https://ollama.com/docs/overview).

## Usage

1. **Running Open WebUI:**

   Start the Open WebUI Docker container:

   ```bash
   docker-compose up -d
   ```

2. **Accessing Open WebUI:**

   Open your web browser and navigate to `http://localhost:3000` to access the Open WebUI interface.

3. **Using Ollama:**

   Ensure Ollama is running and properly configured as per the [Ollama documentation](https://ollama.com/docs/overview).

## Model Information

The project utilizes the default embedder and chatbot models provided by Ollama. No custom model integration is discussed here.

## Embedding Books

To embed books and provide personalized financial advice:

1. **Upload Books:**

   Use the Open WebUI interface to upload financial books or documents.

2. **Embedding Process:**

   Open WebUI will process the uploaded documents and integrate them with the AI models for personalized insights.

## References

- [Open WebUI Documentation](https://github.com/open-webui/open-webui)
- [Ollama Documentation](https://ollama.com/docs/overview)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your contributions adhere to the coding standards and practices outlined in this project.
