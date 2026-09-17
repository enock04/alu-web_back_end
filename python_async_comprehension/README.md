# Python - Async Comprehension

This project covers async generators, async comprehensions, and measuring
the runtime of coroutines executed in parallel with `asyncio.gather`.

## Learning Objectives

- How to write an asynchronous generator
- How to use async comprehensions
- How to type-annotate generators

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
| `0-async_generator.py` | `async_generator` coroutine that loops 10 times, waits 1 second each time, and yields a random number between 0 and 10 |
| `1-async_comprehension.py` | `async_comprehension` coroutine that collects 10 random numbers using an async comprehension over `async_generator` |
| `2-measure_runtime.py` | `measure_runtime` coroutine that runs `async_comprehension` four times in parallel with `asyncio.gather` and returns the total runtime |

## Author

Ntwari Enock
