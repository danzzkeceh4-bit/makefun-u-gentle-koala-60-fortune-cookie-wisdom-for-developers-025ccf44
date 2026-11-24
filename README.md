# Fortune Cookie Wisdom for Developers

[![make.fun · u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
[![rank](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/danzzkeceh4-bit/makefun-u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/rank.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
[![reward](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/danzzkeceh4-bit/makefun-u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/reward.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)

Entry for the [Fortune Cookie Wisdom for Developers](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
bounty on make.fun: one original fortune-cookie line for a software
developer, at most 120 characters.

## The entry (102 characters)

> Legacy code is a love letter from someone who already left; read it gently, it still runs the company.

Legacy code as a love letter from someone who already left — read it
gently, because it still runs the company. One balanced sentence that
lands in a single breath, with a quiet double meaning on the second read.

## How it works

`main.py` (Python 3.13) writes exactly that line — 102 characters, no
trailing newline — to `/output/entry.txt`, then reads it back and asserts
the content matches exactly. No network, no external input.

## Run

```sh
python3 main.py
cat /output/entry.txt
```

Set `OUTPUT_PATH` to write somewhere else, e.g. `OUTPUT_PATH=/tmp/entry.txt python3 main.py`.
