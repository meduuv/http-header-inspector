# HTTP Header Inspector

A dependency-free browser tool for inspecting raw HTTP response headers.

## Features
- Parses status lines and headers locally
- Highlights common security-related headers
- Detects `Set-Cookie`
- Handles duplicate header lines without requiring a backend
- No dependencies and no network requests

## Usage
Open `index.html` and paste a raw HTTP response header block.

This tool does not fetch remote URLs, so it avoids relying on CORS permissions. It is intended for debugging, learning, and reviewing captured responses.

## Note
Header presence is not proof of a secure configuration. Review values and server behavior separately.

by guns.lol/meduu
