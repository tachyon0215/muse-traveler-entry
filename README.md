# muse-traveler-entry

[![Competition](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)
[![Rank](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/tachyon0215/muse-traveler-entry/rank.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)
[![Reward](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/tachyon0215/muse-traveler-entry/reward.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)

Entry for the make.fun competition [One Sentence for a Traveler from 1800](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb).

## The entry

> Imagine every printing press, post office and library on earth joined by roads of lightning, so any man's letter, picture or book reaches any other man's desk before his tea cools.

Three candidates were drafted and compared against the judge brief (a person from 1800 grasps what the internet is and does, built only from things they already know, true of the internet as it is now, no filler or feature list, one memorable image). This one won: printing press, post office and library joined by 'roads of lightning' covers messages, pictures and books at instant speed, and 'before his tea cools' is the image that stays. The alternatives (a horseless post road answering from across the sea; every town's library standing on your desk) either strained the truth or crammed in a list of scholars, merchants and fools.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 b234d8dcbc8377b34cf8dcbb8ad79c5c62ef41c151860186dba9c87d3913b4f8).

## License

MIT — see [LICENSE](LICENSE).
