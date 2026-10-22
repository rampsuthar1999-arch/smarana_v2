# Smaraṇa Library

A reading and memorization app, in Devanāgarī only, for 27 Sanskrit texts in three sections (Bhagavad Gītā, Upaniṣads, Stotras & prakaraṇas): 3,335 verses and mantras.

### Bhagavad Gītā

| Text | Name | Author / source | Count |
|---|---|---|---|
| श्रीमद्भगवद्गीता | Bhagavad Gītā | Vyāsa · Mahābhārata | 701 |

18 chapters with their yoga names, speaker lines (धृतराष्ट्र उवाच, श्रीभगवानुवाच …) and six variant readings. This edition counts 701 verses, including 13.1 (प्रकृतिं पुरुषं चैव …).

### Upaniṣads

| Text | Name | Author / source | Count |
|---|---|---|---|
| ईशोपनिषत् | Īśa Upaniṣad | Śukla Yajurveda | 19 |
| केनोपनिषत् | Kena Upaniṣad | Sāmaveda | 36 |
| कठोपनिषत् | Kaṭha Upaniṣad | Kṛṣṇa Yajurveda | 121 |
| प्रश्नोपनिषत् | Praśna Upaniṣad | Atharvaveda | 68 |
| मुण्डकोपनिषत् | Muṇḍaka Upaniṣad | Atharvaveda | 65 |
| माण्डूक्योपनिषत् | Māṇḍūkya Upaniṣad | Atharvaveda | 13 |
| गौडपादीयकारिका | Māṇḍūkya Kārikā | Gauḍapāda | 228 |
| तैत्तिरीयोपनिषत् | Taittirīya Upaniṣad | Kṛṣṇa Yajurveda | 53 |
| ऐतरेयोपनिषत् | Aitareya Upaniṣad | Ṛgveda | 34 |
| श्वेताश्वतरोपनिषत् | Śvetāśvatara Upaniṣad | Kṛṣṇa Yajurveda | 114 |
| पुरुषसूक्तम् | Puruṣa Sūkta | Ṛgveda · Taittirīya Āraṇyaka | 25 |

### Stotras & prakaraṇas

| Text | Name | Author / source | Count |
|---|---|---|---|
| पातञ्जलयोगसूत्राणि | Yoga Sūtra | Patañjali | 195 |
| नारदभक्तिसूत्राणि | Nārada Bhakti Sūtra | Nārada | 84 |
| आत्मबोधः | Ātmabodha | Ādi Śaṅkarācārya | 68 |
| अपरोक्षानुभूतिः | Aparokṣānubhūti | Ādi Śaṅkarācārya | 144 |
| विवेकचूडामणिः | Vivekacūḍāmaṇi | Ādi Śaṅkarācārya | 580 |
| भज गोविन्दम् | Bhaja Govindam | Ādi Śaṅkarācārya | 34 |
| दक्षिणामूर्तिस्तोत्रम् | Dakṣiṇāmūrti Stotram | Ādi Śaṅkarācārya | 10 |
| ब्रह्मज्ञानावलीमाला | Brahmajñānāvalīmālā | Ādi Śaṅkarācārya | 21 |
| प्रौढानुभूतिः | Prauḍhānubhūti | Ādi Śaṅkarācārya | 17 |
| प्रबोधसुधाकरः | Prabodhasudhākara | Ādi Śaṅkarācārya | 257 |
| दृग्दृश्यविवेकः | Dṛg-Dṛśya-Viveka | Bhāratī Tīrtha | 46 |
| भिक्षुगीता | Bhikṣu Gītā | Bhāgavata 11.23 | 20 |
| भ्रमरगीतम् | Bhramara Gītā | Bhāgavata 10.47 | 69 |
| गोपीगीतम् | Gopī Gītā | Bhāgavata 10.31 | 19 |
| गीतगोविन्दम् | Gītagovindam | Jayadeva | 294 |

## Features
- **Library**: all texts with progress and due counts; tap *Study* to add a text to your daily practice. Search across every text in Devanāgarī or Roman letters (`chitta`, `citta`, `चित्त`).
- **Read**: the complete text of any work, laid out by section with speaker lines. Jump to a section, show or hide verse numbers, and switch on progress colours to see which verses you know. Tap a verse number to open it in Learn; *Read full text* in Learn brings you back to the same verse in context.
- **Learn**: one verse at a time, shown in sections (pādas, prakaraṇas, sargas and aṣṭapadīs).
  - Fade the text: full, ⅓ hidden, ⅔ hidden, first letters, blank. Tap a shaded syllable to check it.
  - *Line by line*: learn line 1, then line 2, then both together, and so on.
  - *Chain*: the last line of the previous verse is the cue for the next.
  - *Listen*: reads the verse or current line aloud with a device voice, at three speeds.
- **Recall**: spaced repetition (again, 1, 3, 7, 16, 35 days) with a combined *Today* queue across your texts. Prompts: verse number, previous verse, or first line.
- **Quiz**: what comes next, which verse has this number, what number a verse is, fill in the missing line, put four verses in order.
- **Progress**: totals, day streak, and a strength map for every verse.
- **Settings**: text size, new verses per day, listening speed, and moving progress between devices with a copy-and-paste code or file.

Progress is kept in the browser's localStorage. Nothing is sent anywhere.

## Publish on GitHub Pages
1. Create a public repository, for example `smarana`.
2. Upload everything in this folder (including the hidden `.nojekyll` file) to the repository root. When updating, upload over the old files; delete the old `icon.svg` if it is still there.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. The app appears at `https://<username>.github.io/smarana/` within a minute or two.

## Install on your phone
**Android (Chrome)**
1. Open the app's address in Chrome.
2. Tap ⋮ → **Add to home screen** → **Install** (or tap the install banner if it appears).
3. The स्म icon appears on your home screen and in the app drawer, and the app opens full-screen. It also works offline.

If Chrome says *"This app is already installed"* but *"Could not open app"*, an earlier install attempt was left half-finished. Remove it first: Android **Settings → Apps → Smaraṇa (or स्मरण) → Uninstall**, then in Chrome tap ⋮ → **Settings → Site settings → All sites →** your github.io address **→ Clear & reset**, and install again.

**iPhone (Safari)**: open the address in Safari, tap **Share → Add to Home Screen**.

Your progress lives in the browser that runs the app. The installed app shares it with Chrome on the same phone; to move it to another device, use **Settings → Copy progress code**.

## Upaniṣad notes
- Each Upaniṣad opens with its śānti pāṭha as the first item; the closing repetition is left out.
- Taittirīya prose is split into the edition's numbered passages within each anuvāka (31 anuvākas across the three vallīs), and long passages are broken into recitation lines at daṇḍas.
- Gauḍapāda's Kārikā keeps the 12 Māṇḍūkya mantras in their place among the 215 kārikās, labelled मन्त्रः and कारिका.
- Puruṣa Sūkta includes the Uttaranārāyaṇa (6 mantras) as its own section.
- Parenthetical alternative readings in the source (for example in Muṇḍaka 3.1.6) appear as variant readings.

## Icon and offline files
`icon-192.png`, `icon-512.png`, `maskable-*.png`, `apple-touch-icon.png` and `favicon-48.png` are the app icon (स्म set in Tiro Devanagari Sanskrit, SIL Open Font License, see `FONT-LICENSE-OFL.txt`). `manifest.webmanifest` makes the app installable and `sw.js` keeps it working offline.

## Data
`index.html` is self-contained. `data/<id>.json` holds each text for reuse: `sec` lists sections as `[title, first verse index]`, and each entry in `v` is `[label, [lines…], extras]`, where extras may hold `s` (speaker), `g` (song in Gītagovindam), `v` (variant readings) and `r` (refrain).

Texts are from the sanskritdocuments.org editions, with Vedic accents and English translations removed. Source typos in verse numbering (Ātmabodha 20, 22; Vivekacūḍāmaṇi 241, 271, 411; Nārada Bhakti Sūtra 54, 66, 68, 69, 77; Prabodhasudhākara 164 and a repeated 185) were repaired so every verse is present. Bhaja Govindam's source numbers two verses 13; the second appears as 13अ.
