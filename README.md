# StyleTTS2-Ukrainian: Text-to-Speech

This repository contains a Text-to-Speech (TTS) application for the Ukrainian language, based on the StyleTTS2 model.

## Features

*   **High-Quality Speech Synthesis:** Generates natural-sounding speech in Ukrainian.
*   **Multiple Voices:** Supports both a single-speaker model and a multi-speaker model with a variety of voices.
*   **Adjustable Speed:** Control the speed of the generated speech.
*   **Text Verbalization:** A beta feature to convert numbers and acronyms into their spoken word form.
*   **Stress Control:** Manually specify word stress using a `+` symbol after the stressed vowel.
*   **Web Interface:** An easy-to-use interface built with Gradio.

## How it Works

The application uses the StyleTTS2 model, which is a state-of-the-art text-to-speech model known for its ability to capture and replicate speech styles.

The process is as follows:
1.  The input text is processed to handle stress marks.
2.  The text is converted to its phonetic representation using the `ipa_uk` library.
3.  The StyleTTS2 model generates the audio waveform from the phonetic representation.
4.  The application provides options for both a fine-tuned single-speaker model and a multi-speaker model with different voice styles.

## How to Use

1.  Enter the Ukrainian text you want to convert to speech.
2.  If needed, use the "Verbalize (beta)" button to process numbers or acronyms.
3.  For incorrect stress, add a `+` symbol after the stressed vowel (e.g., `за+мок` for castle, `замо+к` for lock).
4.  Select a voice (if using the multi-speaker model).
5.  Adjust the speech speed.
6.  Click "Synthesize" to generate the audio.

This project is based on the work of the original StyleTTS2 authors and has been fine-tuned for the Ukrainian language.
