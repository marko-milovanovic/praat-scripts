# Praat Scripts – Faculty of Philology, University of Belgrade

This repository contains a collection of **Praat scripts** created as part of research and academic work at the **Faculty of Philology, University of Belgrade**. The scripts are designed to assist with phonetic analysis, audio segmentation, annotation, and other speech-related processing tasks.

## 📁 Contents

Below is a list of available scripts. Descriptions and usage instructions are provided for each.

### 🔹 [Extract Formants to Separate TSVs](scripts/file-iterator-formant.praat)
This script processes a folder of paired `.wav` and `.TextGrid` files (named identically) and extracts **formant data** into **individual `.tsv` files**, one per sound file.

**Output columns:**
word, phoneme, duration, f1, f2, f3.

### 🔹 [Extract Formants to Combined TSV](scripts/file-iterator-formant-normalization.praat)
Functionally similar to the first script, but instead of producing a `.tsv` per file, it appends all extracted **formant data** into a **single combined `.tsv` file**, formatted for compatibility with the vowel normalization tool at:

🔗 https://lingtools.uoregon.edu/norm/norm1.php

**Output columns:**
speaker, phoneme, context, F1, F2, F3, glF1, glF2, glF3.

### 🔹 [Extract Pitch to Combined TSVs](scripts/file-iterator-pitch.praat)
This script processes a folder of paired `.wav` and `.TextGrid` files (named identically) and extracts **pitch data** into a **single combined `.tsv` file**.

**Output columns:**
speaker, word, phoneme, duration, minPitch, maxPitch, %.

## 🧪 Requirements

- [Praat](https://www.fon.hum.uva.nl/praat/) – make sure it's installed and up to date.

## 📝 Usage

1. Open Praat.
2. Load the desired script via `Praat > Open Praat Script`.
3. Follow on-screen prompts or refer to script comments for guidance.