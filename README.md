# IDMap: A Pseudo-Speaker Generator Framework Based on Speaker Identity Index to Vector Mapping

## Demo Page

This repository provides audio samples for the paper:

**IDMap: A Pseudo-Speaker Generator Framework Based on Speaker Identity Index to Vector Mapping**

## Abstract

Facilitated by the speech generation framework that disentangles speech into content, speaker, and prosody, voice anonymization is accomplished by substituting the original speaker embedding vector with that of a pseudo-speaker. In this framework, the pseudo-speaker generation forms a fundamental challenge. Current pseudo-speaker generation methods demonstrate limitations in the uniqueness of pseudo-speakers, consequently restricting their effectiveness in voice privacy protection. Besides, existing model-based methods suffer from heavy computation costs. Especially in the large-scale scenario where a huge number of pseudo-speakers are generated, the limitations of uniqueness and computational inefficiency become more significant. To this end, this paper proposes a framework for pseudo-speaker generation, which establishes a mapping from speaker identity index to speaker vector in the feedforward architecture, termed IDMap. Specifically, the framework is specified into two models: IDMap-MLP and IDMap-Diff. Experiments were conducted on both small- and large-scale evaluation datasets. Small-scale evaluations on the LibriSpeech dataset validated the effectiveness of the proposed IDMap framework in enhancing the uniqueness of pseudo-speakers, thereby improving voice privacy protection, while at a reduced computational cost. Large-scale evaluations on the MLS and Common Voice datasets further justified the superiority of the IDMap framework regarding the stability of the voice privacy protection capability as the number of pseudo-speakers increased.

---

## Audio Samples

The audio samples are organized by pseudo-speaker generation method.  
For each utterance, the same sample ID is used across all displayed methods.

- `Original` denotes the original speech.
- `RS` denotes random selection.
- `Average` denotes the average-based method.
- `PSD` denotes the PSD-based method.
- `GAN` denotes the GAN-based method.
- `Proposed` denotes the proposed IDMap-based anonymizer.

---

## Selected Samples

| File name | Original | RS | Average | PSD | GAN | Proposed |
|---|---|---|---|---|---|---|
| `1272-128104-0000.wav` | [audio](Original/1272-128104-0000.wav) | [audio](RS/wav/1272-128104-0000.wav) | [audio](Average/wav/1272-128104-0000.wav) | [audio](PSD/wav/1272-128104-0000.wav) | [audio](GAN/wav/1272-128104-0000.wav) | [audio](Proposed/wav/1272-128104-0000.wav) |
| `1462-170138-0000.wav` | [audio](Original/1462-170138-0000.wav) | [audio](RS/wav/1462-170138-0000.wav) | [audio](Average/wav/1462-170138-0000.wav) | [audio](PSD/wav/1462-170138-0000.wav) | [audio](GAN/wav/1462-170138-0000.wav) | [audio](Proposed/wav/1462-170138-0000.wav) |
| `251-118436-0001.wav` | [audio](Original/251-118436-0001.wav) | [audio](RS/wav/251-118436-0001.wav) | [audio](Average/wav/251-118436-0001.wav) | [audio](PSD/wav/251-118436-0001.wav) | [audio](GAN/wav/251-118436-0001.wav) | [audio](Proposed/wav/251-118436-0001.wav) |
| `84-121123-0000.wav` | [audio](Original/84-121123-0000.wav) | [audio](RS/wav/84-121123-0000.wav) | [audio](Average/wav/84-121123-0000.wav) | [audio](PSD/wav/84-121123-0000.wav) | [audio](GAN/wav/84-121123-0000.wav) | [audio](Proposed/wav/84-121123-0000.wav) |

---

## Citation

The paper is currently under review. Citation information will be updated after publication.
