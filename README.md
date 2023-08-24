# OpenAI Proxy
[![Build Status](https://github.com/qq7594599/openai-proxy/actions/workflows/docker-image.yml/badge.svg)](https://github.com/qq7594599/openai-proxy/actions/workflows/docker-image.yml)

This is a simple proxy for the OpenAI API. It is intended to be used as a
drop-in replacement for the OpenAI API, but with the ability to intercept
requests and responses.



## Installation

```bash
docker pull qq7594599/openai-proxy:latest
```

## Usage

```bash
docker run -p 3000:3000 qq7594599/openai-proxy:latest
```

