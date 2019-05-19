# Pygame testing framework
## Components
- `script.py` — user input.
- `checker.py` — the provided checker for the user's script.
- `checkerlib.py` — the checker's library with all necessary interfaces.
- `enums.py` — commonly used numbers in communication between components.
- `pygame/` — the fake pygame library that communicates with the runner via IPC.
- `runner.py` — the script executor that starts the script in a separate process, sends it the checker nonce and receives pygame events from it.

## Running
```console
$ python3 runner.py
```
