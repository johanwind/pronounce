# Read Aloud: pronunciation practice

- English: **https://johanwind.github.io/pronounce/**
- Norwegian (Les høyt): **https://johanwind.github.io/pronounce/nb/**
- Greek (Διάβασε δυνατά): **https://johanwind.github.io/pronounce/el/**

Read a short passage aloud and see which words and sounds came out unclear, summed up as three focus areas to practise.

This repository holds only the web page. Scoring runs on a server, and recordings are scored and discarded, never stored. Your progress stays in your browser.

- **English:** a phoneme recogniser ([facebook/wav2vec2-lv-60-espeak-cv-ft](https://huggingface.co/facebook/wav2vec2-lv-60-espeak-cv-ft)) is force-aligned to the expected sounds, and each sound's clarity is compared with synthetic voices ([Kokoro](https://huggingface.co/hexgrad/Kokoro-82M)). Passages are excerpts from public-domain books (Jerome K. Jerome, Saki, P. G. Wodehouse, Stephen Leacock, G. K. Chesterton, O. Henry, Mark Twain, Arthur Conan Doyle, Edgar Allan Poe, Charlotte Perkins Gilman, Aesop).
- **Norwegian (Bokmål):** the National Library's speech recogniser ([NbAiLab/nb-wav2vec2-1b-bokmaal-v2](https://huggingface.co/NbAiLab/nb-wav2vec2-1b-bokmaal-v2)) checks whether each word's spelling explains what you said better than easily confused spellings (y/i, ø/e, kj/sj, o/å, rt/t…). The model voice is Google Cloud Text-to-Speech. Tonal accent is not measured.
- **Greek:** the same phoneme recogniser as English, with Greek sounds from espeak-ng; each sound's clarity is compared with Greek synthetic voices ([MMS-TTS](https://huggingface.co/facebook/mms-tts-ell), Piper). The model voice is Google Cloud Text-to-Speech. Stress is not measured.
