# Quran Tafsir Reader

Read the Quran verse by verse, surah by surah, with classical commentary beside each verse:

- **al-Jalālayn** — al-Maḥallī (d. 1459) and al-Suyūṭī (d. 1505)
- **Ibn Kathīr** — *Tafsīr al-Qurʾān al-ʿAẓīm* (d. 1373)
- **al-Qurṭubī** — *al-Jāmiʿ li-Aḥkām al-Qurʾān* (d. 1273)

Each verse also shows Pickthall's English translation (1930).

**Open it:** https://abdelhamid-sameh.github.io/quran-tafsir/ (home page linking the Quran reader, the hadith study and the 99 Names; the reader itself is at /quran/) — works in any browser, on phones too, no account needed.
To read offline on a computer, download this repository and open `index.html`.

## Sources

- Quran text: Uthmani script (Ḥafṣ), from the Noble Qur'an Encyclopedia (quranenc.com), via the `quran-json` package.
- English: Marmaduke Pickthall, *The Meaning of the Glorious Koran* (1930), via tanzil.net.
- Tafsir: original Arabic texts via the [tafsir_api](https://github.com/spa5k/tafsir_api) dataset. The modern editors' manuscript footnotes are omitted, and commentary that the dataset repeated across verse groups is shown once per group.

The texts are classical works; the license below covers this site's code only.

## مُشكِل الصحيح

A study of 61 contested sahih hadith (Arabic), with a library of the two Sahihs and the sahih narrations of the four Sunan: https://abdelhamid-sameh.github.io/quran-tafsir/hadith/

## الأسماء الحسنى

The 99 Names of Allah (Arabic) in the order of al-Tirmidhi 3507, with a meaning for each and the Quran verses where it appears as a Name (counted from the Quranic Arabic Corpus morphology, ambiguous cases checked by hand): https://abdelhamid-sameh.github.io/quran-tafsir/asma/
