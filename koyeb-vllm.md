## Requirements

- A Koyeb account to build and run the vLLM instance on GPUs.
- Access to GPU Instances on Koyeb. Join the preview today to gain access.
- Hugging Face account with a read-only API token. You will use this to fetch the models that vLLM will run. You may also need to accept the terms and conditions or usage license agreements associated with the models you intend to use. In some cases, you may need to request access to the model from the model owners on Hugging Face. For this guide, make sure you have accepted any terms required for the google/gemma-2b-it model.

# Steps

- Create a custom Dockerfile
- Push the Dockerfile to GitHub
- Deploy vLLM on Koyeb
- Querying the model with the vLLM API
- Querying the completions endpoint
- Querying the chat endpoint
- Additional vLLM image customization


