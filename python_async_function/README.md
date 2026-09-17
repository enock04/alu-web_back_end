# Python - Async

This project covers asynchronous programming in Python 3 using `async`/`await`,
running concurrent coroutines, measuring runtime, and working with `asyncio.Task`.

## Learning Objectives

- `async` and `await` syntax
- How to execute an async program with `asyncio`
- How to run concurrent coroutines
- How to create `asyncio` tasks
- How to use the `random` module

## Requirements

- All files are interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.9)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/env python3`
- Code should use the `pycodestyle` style (version 2.5.*)
- All files must be executable
- All modules and functions should be documented
- All functions and coroutines must be type-annotated

## Tasks

| File | Description |
| --- | --- |
| `0-basic_async_syntax.py` | `wait_random` coroutine that waits a random delay (0 to `max_delay`) and returns it |
| `1-concurrent_coroutines.py` | `wait_n` coroutine that spawns `wait_random` `n` times and returns delays in ascending order |
| `2-measure_runtime.py` | `measure_time` function that measures the average execution time of `wait_n(n, max_delay)` |
| `3-tasks.py` | `task_wait_random` function that returns an `asyncio.Task` wrapping `wait_random` |
| `4-tasks.py` | `task_wait_n` coroutine, identical to `wait_n` but using `task_wait_random` |

## Author

Ntwari Enock
