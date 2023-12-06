<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## WRLD-LP Dataset

WRLD-LP is an open audio dataset comprised of a series of symbolic drum recordings in the genres of world percussion music. The dataset includes 3,162 audio loops recorded in uncompressed stereo WAV format. The compositions were generated with an internal sample dataset played with note-dense MIDI drum files from a code-based music generation system, along with a MIDI transformer model trained on more than 30,000 MIDI files.

## Dataset

The primary objective of this dataset is to provide accessible content for machine learning applications in music and audio research. Some potential use cases for this dataset include tempo detection and classification, drum rhythm analysis, audio-to-MIDI conversion, source separation, automated mixing, music information retrieval, AI music generation, sound design, and signal processing.

**Specifications**

- 3,162 audio loops (7.3 hours)
- 24-bit WAV format
- BPM labeled
- Tempo range: 100-130 bpm
- Expressive percussion drumming
- Mixed rhythms of world music

## Examples

See the examples folder to preview MP3 demos.

## License

This dataset is developed by WaivOps, a crowdsourced music project managed by the sound label company Patchbanks. All recordings have been compiled by verified sources for copyright clearance.

The WRLD-LP dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Download

The audio files are provided in 24-bit WAV format and encoded at 44.1kHz.

Direct Download (6.5GB) [wrld_lp_id_001.tar.gz](https://zenodo.org/record/8388266/files/wrld_lp_id_001.tar.gz?download=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8388266.svg)](https://doi.org/10.5281/zenodo.8388266)


## File Name Reference

| **Label** | **Reference**              |
| --------- | -------------------------- |
| bpm       | The tempo of the audio file|
| wrld      | Main genre (world)         |
| lp        | Drum style (Latin percussion)|
| id        | Identification number      |
| _0000     | Playlist track number      |

## Citation

If you use this dataset for a research or development project, please cite the following references:

```bash
@misc{WRLD-LP,
author = {WaivOps},
title = {WaivOps WRLD-LP: Open Audio Resources for Machine Learning in Music},
year = {2023},
doi = {10.5281/zenodo.8388266},
url = {https://doi.org/10.5281/zenodo.8388266},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
