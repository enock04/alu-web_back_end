# Pagination

This project covers different ways to paginate a dataset: simple
page/page_size pagination, hypermedia pagination (with metadata about
next/previous/total pages), and deletion-resilient pagination that keeps
working correctly even if rows are removed from the dataset between
requests.

## Learning Objectives

- How to paginate a dataset with simple `page` and `page_size` parameters
- How to paginate a dataset with hypermedia metadata
- How to paginate in a way that is resilient to deletions

## Requirements

- All files are interpreted on Ubuntu 20.04 LTS using `python3` (version 3.9)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/env python3`
- Code should use the `pycodestyle` style (version 2.5.*)
- All files must be executable
- All modules, classes, and functions should be documented
- All functions and coroutines must be type-annotated
- `Popular_Baby_Names.csv` must be present in this directory to run the
  Server classes (not included in this repo — download it separately)

## Tasks

| File | Description |
| --- | --- |
| `0-simple_helper_function.py` | `index_range` function that returns a start/end index tuple for a given page and page size |
| `1-simple_pagination.py` | `Server` class with a `get_page` method that returns the correct page of the dataset |
| `2-hypermedia_pagination.py` | `Server` class with a `get_hyper` method that adds pagination metadata (`next_page`, `prev_page`, `total_pages`) |
| `3-hypermedia_del_pagination.py` | `Server` class with a `get_hyper_index` method that paginates by index and stays correct even if rows are deleted from the dataset |

## Author

Ntwari Enock
