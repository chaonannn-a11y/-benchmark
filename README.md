# ChoreoAssist Separation Benchmark

Anonymous listening test for four music source-separation models:

- HT-Demucs
- HT-Demucs FT
- Open-Unmix UMXHQ
- BS-RoFormer MUSDB18HQ community checkpoint

The site contains five listening tasks. Model and task order are randomized in
the browser. Audio is precomputed and stored as lossless 24-bit FLAC; no model
runs in the browser.

## Test URL

https://chaonannn-a11y.github.io/-benchmark/

## Scope

This is a small-sample product benchmark for choreography use. It measures
perceived clarity, interference, stability, choreography usefulness, and
forced preference. It does not establish statistical significance or
reproduce paper SDR results.

The BS-RoFormer checkpoint is used for research comparison only. Its registry
license status is `not-reviewed`.
