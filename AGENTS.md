## Memory Directories

Agents may persist information across sessions through the shared memory directories below. These paths already exist in the repository and can be read from or written to as needed.

- `agents/memory/records`: append-only historical logs and records (treat as quasi-immutable).
- `agents/memory/long-term`: editable storage for durable knowledge.
- `agents/memory/short-term`: scratch space for ephemeral planning or to-do lists.

Do not store secrets or sensitive credentials in any of these directories.
