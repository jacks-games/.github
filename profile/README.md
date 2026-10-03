# ⚽ Jack's Games

### Ten little games for one six-year-old, built with his dad. Newest first.

Reading, writing, maths and chess. No accounts, no ads, nothing to install — open a link and play. They all run in a browser and are made for an iPad.

# [👉 &nbsp; jackbenn.ing &nbsp; 👈](https://jackbenn.ing)

---

## 🔟 &nbsp; [Jack's Ten Frames](https://github.com/jacks-games/ten-frames) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/ten-frames/)

Two rows of five, red and yellow counters. See seven as *five and two*, fill the frame to ten, then go past it.

![Jack's Ten Frames](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/ten-frames.png)

---

## ⏰ &nbsp; [Jack's Clock](https://github.com/jacks-games/clock) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/clock/)

Read the clock, then set the hands yourself — o'clock, half past, quarter past and quarter to.

![Jack's Clock](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/clock.png)

---

## 💯 &nbsp; [Jack's Big Numbers](https://github.com/jacks-games/big-numbers) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/big-numbers/)

Tens and ones in nets of ten footballs — adding and taking away all the way to 100.

![Jack's Big Numbers](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/big-numbers.png)

---

## 👀 &nbsp; [Jack's Sight Words](https://github.com/jacks-games/sight-words) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/sight-words/)

The twenty most common English words on big cards. Tap one and hear it read out, then find it in the quiz.

![Jack's Sight Words](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/sight-words.png)

---

## 🍎 &nbsp; [Jack's Apples](https://github.com/jacks-games/apples) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/apples/)

Trace the numbers 1 to 20 with your finger, then fill the missing numbers into a grid of apples.

![Jack's Apples](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/apples.png)

---

## 🥅 &nbsp; [Jack's Match](https://github.com/jacks-games/match) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/match/)

Two halves. **First half:** is it a real word or a silly alien word? Nobody reads it to you. **Second half:** hear a word and write it yourself.

![Jack's Match](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/match.png)

---

## ✏️ &nbsp; [Jack's Letters](https://github.com/jacks-games/letters) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/letters/)

Trace all 26 letters with your finger — starting in the right place, going the right way round.

![Jack's Letters](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/letters.png)

---

## 🔢 &nbsp; [Jack's Numbers](https://github.com/jacks-games/numbers) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/numbers/)

Count footballs, add them up and take them away — to 10, then to 20.

![Jack's Numbers](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/numbers.png)

---

## 📖 &nbsp; [Jack's Words](https://github.com/jacks-games/words) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/words/)

Hear a word, build it from letters, then read it in a sentence.

![Jack's Words](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/words.png)

---

## ♟️ &nbsp; [Jackies Schach](https://github.com/jacks-games/chess) &nbsp; · &nbsp; [▶ play](https://jacks-games.github.io/chess/)

Real chess with a coach who marks the safe squares. This one speaks German. 🇩🇪

![Jackies Schach](https://raw.githubusercontent.com/jacks-games/.github/main/profile/img/chess.png)

---

<details>
<summary><b>For grown-ups</b></summary>

Each game is a single self-contained `index.html`: no build step, no analytics, and no network calls beyond its own voice clips — except that chess loads its rules engine (chess.js) from jsDelivr and Sight Words its font from Google Fonts. Speech is pre-rendered clips of a neural English voice (German for chess), with the browser's Web Speech API only as the fallback, and it always waits for a tap first. Progress is kept in `localStorage` on the device — nothing is collected anywhere.

The games are written for an iPad mini in either orientation, with finger-sized targets, and they respect `prefers-reduced-motion`.

The start page at [jackbenn.ing](https://jackbenn.ing) is built from [google814/Jack](https://github.com/google814/Jack), which is the source of truth. The repos here are copies kept in step by `tools/sync-game-repos.sh` in that repo, so each game also has its own page and its own link.

</details>
