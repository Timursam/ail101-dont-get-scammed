# AIL 101 — НЕ ПОПАДИСЬ / Don't Get Scammed

A bilingual, playable digital literacy game built through an AI workflow connecting **Notion, GitHub and Google Drive**.

## Play / Играть

**Play online / Играть:** https://timursam.github.io/ail101-dont-get-scammed/

The public GitHub Pages version was opened and verified in a browser. A portable copy is also included in this repository.

Download this repository and open `index.html` in a browser. No installation, API keys, server or build step is required. The game works offline with system fonts; its optional Google Fonts stylesheet needs an internet connection.

Скачайте репозиторий и откройте `index.html` в браузере. Установка и ключи API не нужны. Переключатель RU / EN меняет язык без потери ответов.

## What the game does

- Six fictional situations: parcel phishing, login-code theft, a fake family voice message, a task-job scam, a fake university form and a fabricated AI citation.
- Three choices per situation, inspectable evidence, immediate consequences and learning feedback.
- 0–2 points per answer, 12 maximum; three endings at 0–5, 6–9 and 10–12 points.
- Fictional wallet starts at 500,000 UZS and privacy at 100. These are game indicators, not real risk estimates.
- RU/EN localization, local progress, responsive layout and a downloadable personal debrief.
- No real payments, password fields, personal-data collection or clickable scam links. The voice message is a transcript, not real audio.

## Connected workflow / Связанные приложения

1. **Notion:** AI saved the bilingual source scenarios, scoring and acceptance criteria, then read them back before implementation.
2. **GitHub:** AI wrote the playable implementation and this guide through the connected GitHub tools.
3. **Google Drive:** AI created the submission folder and uploaded verifiable project evidence.

The apps contribute to the creation workflow. The game itself is static and does not access players' accounts or synchronize live with Notion.

Private project documents and submission-folder links are kept in the owner’s submission materials.

## Validation

Browser-tested all 18 choices in each language (36 choice checks), all three endings in both languages, language switching, local progress restoration and debrief download. Checked a 390 px mobile viewport for horizontal overflow. Screenshots and browser checks are in the submission folder. JavaScript syntax validation passed.

## Reference reading

- Login.gov, verifying messages: https://www.login.gov/help/fraud-concerns/verify-messages/
- FTC, fake emergencies and voice impersonation: https://consumer.ftc.gov/articles/scammers-use-fake-emergencies-steal-your-money
- FTC, task scams: https://consumer.ftc.gov/consumer-alerts/2024/11/task-scams-create-illusion-making-money

All names, messages, prices, suspicious domains and citations in the scenarios are fictional. The AI-citation example intentionally uses an invented claim and labels it as such. No statistics in the game are presented as research findings.

## Files

- `index.html`: page shell
- `style.css`: responsive interface
- `cases.js`: six bilingual scenarios and consequences
- `app.js`: game logic, localization, storage and debrief export

The authoring specification lives in Notion. Hosting metadata is managed separately from this public source repository.
