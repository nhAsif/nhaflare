# nhaFlare

## Introduction

nhaFlare is a cloudflare worker proxy which you can deploy yourself to download anything through cloudflare.

## Preview

![nhaFlare Preview Image](docs/assets/preview.png "nhaFlare")

## Features

- **Increase Speed**: Increase your slow download speed with Cloudflare CDN
- **Resumable Downloads**: Generates resumable download url for any url
- **Universal**: Works with most if not any download links

## Deployment

### Easily deploy with Cloudflare Worker

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/nhAsif/nhaflare)

### Manual Deploy

```bash
# Clone this repo
git clone https://github.com/nhAsif/nhaflare

# Goto the repo dir
cd nhaflare

# Install dependency
npm install

# Deploy
npm run deploy

```

## Development

```bash

# Start development server
npm run dev

```
