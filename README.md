# Read Aloud: English pronunciation practice

**https://johanwind.github.io/pronounce/**

Read a short passage aloud and see which words and sounds came out unclear, summed up as three focus areas to practise.

This repository holds only the web page. Scoring runs on a server: a phoneme recogniser ([facebook/wav2vec2-lv-60-espeak-cv-ft](https://huggingface.co/facebook/wav2vec2-lv-60-espeak-cv-ft)) is force-aligned to the expected sounds, and each sound's clarity is compared with a model voice ([Kokoro](https://huggingface.co/hexgrad/Kokoro-82M)). Recordings are scored and discarded, never stored; your progress stays in your browser.

Passages are excerpts from public-domain books (Jerome K. Jerome, Saki, P. G. Wodehouse, Stephen Leacock, G. K. Chesterton, O. Henry, Mark Twain, Arthur Conan Doyle, Edgar Allan Poe, Charlotte Perkins Gilman, Aesop).
