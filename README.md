# Singing Synthesis from MIDI file

This script relies on the [sinsy.jp](http://sinsy.jp/) website from the Nagoya Institute of Technology which implements a HMM-based Singing Voice Synthesis System.

## Requirements

- musescore: It's used to convert midi to musicxml
- python 3

## Installation

```bash
pip install midi2voice
```

## Usage

You can use it running the installed module using `python -m`. It has five parameters, the lyrics_file, midi_file, singer sex (optional), tempo (optional) and destination folder (optional).

### Usage example
```bash
# Print help
python3 -m midi2voice -h

# Generate the voice given a midi file and a text file with the lyrics
python -m midi2voice -l shallow.txt -m shallow.mid -g female -t 96
```