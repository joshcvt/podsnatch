# PodSnatch

PodSnatch is a simple<sup>[1](#footnote1)</sup>, cross-platform
<sup>[2](#footnote2)</sup> podcast downloader.  Feed it an OPML file and wire it
up to a cronjob, and it downloads your podcasts on your schedule.  PodSnatch
also downloads all the metadata for each episode, and stores it in a plaintext
file with the same name as the episode audio, with `.txt` appended.

<a name="footnote1">1</a>: Only \~100 lines of Python!

<a name="footnote2">2</a>: *Probably*, I've only tested on Mac.

## Usage
```bash
python podsnatch.py --opml <input file> -o <output directory>
```

## Contributing
PRs welcone!