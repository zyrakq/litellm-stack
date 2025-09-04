# LiteLLM Custom Image

Custom Docker image for LiteLLM with dynamic configuration generation based on environment variables.

## Quick Start

Build the custom LiteLLM image:

```bash
cd src/litellm/image
docker build -t litellm .
docker tag litellm localhost/litellm
```
