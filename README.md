# OpenVoice Kids — open voices mirror

Copies of the open text-to-speech voices that [OpenVoice Kids](https://github.com/jev1234) (a free, non-commercial AAC app for children) offers for download. The app downloads from here first and checks every archive against a pinned SHA-256 hash; the original source is the [sherpa-onnx `tts-models` release](https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models).

Release [`voices-2026-10`](https://github.com/jev1234/openvoicekids-voices/releases/tag/voices-2026-10):

| Archive | Voice | Licence |
|---|---|---|
| sherpa-onnx-supertonic-3-tts-int8-2026-05-11.tar.bz2 | Supertonic 3 by Supertone (10 voices; en, da, ru, uk, ar, es and more) | Code: MIT / Apache-2.0 (sherpa-onnx). Weights: BigScience OpenRAIL-M — see `SUPERTONIC-3-OpenRAIL-M-LICENSE.txt`, including its use restrictions (no deception, impersonation or harm) |
| vits-piper-en_GB-cori-high.tar.bz2 | Piper "cori" (UK English) | Piper MIT; data public domain (LibriVox) |
| vits-piper-en_GB-alba-medium.tar.bz2 | Piper "alba" (UK English) | Piper MIT; data CC BY 4.0 |
| vits-piper-da_DK-talesyntese-medium.tar.bz2 | Piper "talesyntese" (Danish) | Piper MIT; data CC0 |
| vits-piper-ru_RU-denis-medium.tar.bz2 | Piper "denis" (Russian) | Piper MIT; data CC0 |
| vits-piper-es_MX-claude-high.tar.bz2 | Piper "claude" (Mexican Spanish) | Piper MIT; voice Apache-2.0 |
| vits-piper-es_ES-davefx-medium.tar.bz2 | Piper "davefx" (Spanish) | Piper MIT; data CC0 |

Piper voices use the espeak-ng phonemizer (GPL-3.0), included in each archive as `espeak-ng-data`.
