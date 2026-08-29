# Prompt Injection Controls

Threat examples:
- malicious instructions in documents
- retrieved content asking to reveal secrets
- fake administrator commands
- attempts to override governance policy

Controls:
- treat retrieved text as data, not authority,
- isolate system instructions,
- allowlist tools/actions,
- validate tool parameters,
- require approval for sensitive writes,
- never expose hidden secrets or internal prompts.
