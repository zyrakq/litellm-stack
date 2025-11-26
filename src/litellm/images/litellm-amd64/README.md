# LiteLLM Custom Image

Custom Docker image for LiteLLM with dynamic configuration generation based on environment variables.

## Quick Start

Build the custom LiteLLM image:

```bash
cd src/litellm/images/litellm-amd64
docker build -t litellm-amd64 .
docker tag litellm-amd64 localhost/litellm:amd64
```
