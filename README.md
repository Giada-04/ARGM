# Audio Restoration for Generative Models (ARGM)

**Improving MusicGen Outputs**

*Author: Giada Manfredi*

Date: January 2026

---

This repository contains code, appendix, audio and figures related to the report **“Audio Restoration for Generative Models — Improving MusicGen Outputs”**.

Recent text-to-music generative models such as MusicGen can produce coherent musical samples directly from textual prompts. Despite their strong semantic consistency, the generated audio often exhibits limited perceptual quality due to noise, quantization artifacts, and reduced spectral detail. In this work, we propose a fully zero-shot audio restoration pipeline that combines machine learning–based source separation with traditional digital signal processing (DSP) techniques. Specifically, we first decompose MusicGen outputs into individual audio stems using Demucs and then apply a DSP-based enhancement pipeline independently to each stem before remixing. Through spectral analysis and quantitative evaluation of low-energy frequency components, we show that the proposed stem-wise restoration consistently achieves superior audio enhancement compared to applying the same processing directly to the mixed audio, with particularly significant improvements in noise reduction.

---

The code is designed to be executed on *Google Colab*, however running it in other environments may require certain adjustments.
