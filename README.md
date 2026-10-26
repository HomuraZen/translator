# Interpreter

Live Chinese ⇄ English interpreter for supplier, contractor and staff conversations. Single-file web app (`index.html`), hosted on GitHub Pages.

## What it does
- **他们说**: listens to Mandarin or Cantonese through the phone mic and shows English subtitles live.
- **I speak**: listens to English or Malay and gives a Chinese reply you can play aloud or show full-screen.
- Keeps a transcript on the phone. Type instead of speaking when it's noisy.

## Engines
- **Fast** (default): free Google Translate endpoint. Used for the live subtitles.
- **Accurate**: Claude (`claude-haiku-5-5`). Add an API key in Settings. Also flags prices, quantities, deadlines and halal concerns.

## Setup
1. Repo Settings → Pages → deploy from `main`, root folder.
2. Open the Pages link in Chrome (Android) or Safari (iPhone), allow the microphone, then Add to Home Screen.
3. Optional: add a Claude API key in Settings. Set a monthly spend limit at console.anthropic.com.

## Limits
- Speech-to-text runs through the browser's speech service (Google on Chrome, Apple on Safari). Don't use for confidential talks.
- Live listening is most reliable on Android Chrome. iPhone Safari may cut out more often.
- The free engine is an unofficial endpoint and may stop working. The Claude engine is the fallback.
- Verify money, quantities and halal status with the other person before agreeing. Machine translation can be wrong.
