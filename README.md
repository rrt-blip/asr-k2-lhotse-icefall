# asr-k2-lhotse-icefall
Automatic Speech Recognition (ASR) pipeline for Hungarian, based on:
- [K2](https://github.com/k2-fsa/k2) for WFST-based decoding
- [Lhotse](https://github.com/lhotse-speech/lhotse) for data preparation
- [Icefall](https://github.com/k2-fsa/icefall) recipe framework

## Features
- 🏗️ End-to-end Hungarian ASR pipeline
- 📝 Custom Hungarian phoneme set and lexicon
- ⚡ Optimized for Common Voice Hungarian dataset

## Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/rrt-blip/asr-k2-lhotse-icefall.git
   cd lhotse-k2-asr/egs/commonvoice_hu/asr