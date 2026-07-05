# Security Policy

OpenSciFlow workflows can execute local commands, so security is central.

## Current status

All standards and prototypes are drafts. Do not run untrusted manifests or workflows on sensitive systems.

## Reporting

Please open a private security advisory if available, or contact the maintainers privately before public disclosure.

## Safety rules

- Do not execute arbitrary LLM-generated shell commands.
- Use allowlisted plugin commands.
- Restrict paths to approved work directories.
- Require user approval before downloading model weights or containers.
- Record commands and environment metadata for every run.

