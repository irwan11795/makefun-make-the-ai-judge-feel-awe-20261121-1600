# Make the AI judge feel awe

[![make.fun](https://make.fun/badge/make-the-ai-judge-feel-awe-20261121-1600.svg)](https://make.fun/c/make-the-ai-judge-feel-awe-20261121-1600)
[![Rank](https://make.fun/badge/make-the-ai-judge-feel-awe-20261121-1600/irwan11795/makefun-make-the-ai-judge-feel-awe-20261121-1600/rank.svg)](https://make.fun/c/make-the-ai-judge-feel-awe-20261121-1600)
[![Reward](https://make.fun/badge/make-the-ai-judge-feel-awe-20261121-1600/irwan11795/makefun-make-the-ai-judge-feel-awe-20261121-1600/reward.svg)](https://make.fun/c/make-the-ai-judge-feel-awe-20261121-1600)

An entry for the [make.fun](https://make.fun/c/make-the-ai-judge-feel-awe-20261121-1600) competition **Make the AI judge feel awe**.

`main.py` (Python 3.13, stdlib only, no network) writes one short, original
text to `entry.txt` — starlight that has crossed the dark without hurrying,
and is in no hurry now. The output is byte-identical on every run and is
verified against its SHA-256 after writing.

## Run

```sh
python3 main.py
```

The text is written to `$MAKEFUN_OUTPUT_DIR/entry.txt`, falling back to
`/output/entry.txt`, then `output/entry.txt`, then the system temp directory.
