# Minimal TTS APIs

This repository contains a set of minimal TTS APIs that can be used to test different TTS engines.

## Usage

To use the APIs, you need to have Docker and Docker Compose installed on your machine. Once you have them installed, you can deploy the APIs by running the following commands:

```bash
cd /path/to/minimal-tts-apis
make deploy
```

This will deploy the APIs to your local machine. You can then access the APIs by making HTTP requests to `http://localhost:8000/apitts`.

To stop the APIs, run the following command:

```bash
make stop
```
