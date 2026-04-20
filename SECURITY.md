# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability within this fork, please create an issue.

This fork modifies the following security-related behaviors from the original:
- **Upload disabled by default**: Benchmark results are no longer uploaded to external pastebin services
- **No external tracking**: Hits counter and stats collection to spiritlhl.net are disabled
- **No third-party CDNs**: Installation scripts point to GitHub releases only

For production use, it is recommended to:
1. Review the code before running
2. Use the `-upload=false` flag (default in this fork)
3. Run in an isolated environment
