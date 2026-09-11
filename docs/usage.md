# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
python batch.py prompts.jsonl -o answers.jsonl --workers 4 --rpm 300
```

## Notes

- Real rate limiting: sliding windows on requests/min and tokens/min
- JSONL in, JSONL out: the input is streamed line by line
