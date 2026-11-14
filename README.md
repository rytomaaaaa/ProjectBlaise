# Blaise — the study assistant that checks its own work

**PUBLIC RELEASE v6.0.3 · Windows**

![Blaise checking work on paper: a photo of a worked equation on the board, with the wrong line boxed in red](images/check-my-work.png)

Blaise is a voice assistant for students that lives on your PC. Say *"Blaise"* and talk, or type.

## New in 6.0.3

- **The pointer light matches the button you see**, instead of drawing a box of a different size.
- **Settings groups are cards:** a closed group shows a two-letter tile like the Tools ones, what's inside and how many sections.
- **Two-step sign-in can be set up again:** its QR code shows properly.
- **Dots and loaders with some depth:** warm beads that rise and glow, spinners with a glowing tail, and live and
  camera lights set in a ring.

## New in 6.0.2

- **Hard maths answers sooner:** reading a problem on your screen takes a second or two instead of about 17, and for a
  hard one Blaise says straight away that he's working it out on the board, then tells you the checked answer.
- **More reliable hard answers:** the free reasoning models get room to finish, a used-up daily allowance is remembered
  after a restart, and an answer that can't be checked has to match the value Blaise worked out by calculation.
- **A clean answer box:** the final answer only, never the brain thinking out loud.
- **Learning mode that teaches:** "have a go first" holds more reliably, and a new Tutor level gives hints and questions
  first and a quick check after every answer.
- **Fixes:** no grey window after clicking the eye while minimized; the voice test isn't answered as if you were
  talking to Blaise.

## New in 6.0.1

- **Logic puzzles are checked by brute force too:** knights and knaves, line-ups that fit the rules, the fewest river
  crossings. Blaise writes a small program that tries every possibility.
- **A second check when it matters:** if the checking program and Blaise's reasoning disagree, a model from a
  different AI company writes a second program, so one buggy program can't mislead him.

## New in 6.0: a much smarter brain

- **Two minds on every hard question.** Each one is worked out separately, at the same time, by models from different
  AI companies when you've added more keys (Gemini, Groq, NVIDIA, OpenRouter, Claude, OpenAI...). When they disagree, a
  referee finds the step that went wrong.
- **A program checks the maths.** For a counting, probability or number puzzle, Blaise writes a tiny program that works
  the answer out by brute force and runs it safely on your PC. What AI models usually get wrong - letters in a word,
  which decimal is bigger, weekdays, huge powers - is worked out by code instead.
- **University and postgraduate maths, computed exactly:** topology (homology, fundamental groups), group theory, Galois
  groups, residues, ODEs, number theory, Groebner bases, Jordan forms, recurrences, Markov chains, Laplace and Fourier.
- **Connecting ideas.** *"What if I take the area under this curve?"*, *"is a t-distribution a kind of normal
  distribution?"*, *"if I double the speed, what happens to the energy?"* - Blaise links it to what you were just
  talking about and puts the chain on the board with a picture. He knows 267 ideas, from school maths to quantum
  mechanics, the common mix-ups, and what tells close ideas apart.
- **Worksheet boards**, more exact calculators (statistics, chemistry, physics, biology, money), and sound from your own
  computer is no longer answered as if you'd said it.

## From 5.0: he sees your work, and you get good at it

- **Check my work with the camera.** Hold your page up and say *"check my work"*. Blaise reads exactly what's written,
  says which part he couldn't read instead of guessing, and shows the photo with the first mistake boxed, and why. The
  camera is off until you turn it on, and a light shows while it's on.
- **Get good at this kind.** Under every worked answer: how to spot this kind of question, the plan as steps that work
  on any of them, and three new questions with less help each time, from the first step done for you to one that looks
  different. Every answer is checked by calculation, and one comes back a few days later to check it stuck.
- **Blaise at the top of the screen.** One small capsule with his eye in it shows what he's doing, what he's saying and
  the box you type in. Slide it along the top edge, or bring back the floating eye in Settings.
- **Hand gestures.** Say *"gesture mode"*: point, pinch to click, drag, scroll, swipe, and move windows with your hand
  in front of the webcam. Your hand is tracked on your PC; nothing about it is sent anywhere.
- **Steadier.** Blaise closes much less often, the eye is easier to drag, and making PDFs works with the newest Edge.

![The capsule at the top of the screen: searching YouTube, then Blaise's words](images/capsule.png)

## See it

| Get good at this kind | A worked answer, step by step and checked |
|---|---|
| ![Under a worked integral: how to spot it, the plan, and three questions with less help each time](images/get-good.png) | ![A worked integral on the board: numbered steps down one line and the answer in one card, marked as checked](images/board.png) |

**A graphing calculator built in.** Ask for a graph by voice or type it, in 2D or 3D, with limits, integrals and visual
proofs:

![A cubic and its derivative on Blaise's graph, with the turning points marked](images/graph.png)

*Screenshots show Blaise's real window with demo content.*

## From 4.1: a calmer look

- A home screen on one centre line, a chat that reads like a log, a calmer blackboard, virus scans with Windows Defender,
  storage clean-up that only removes what you say yes to, and searchable Settings.

## From 4.0: your whole course, run for you

- **Course Autopilot.** Connect Canvas, Google Classroom or Teams and say *"plan my courses"*. Every exam and big
  assignment becomes a goal with steps timed to its date.
- **Every answer checked.** Maths, units and chemistry are worked out exactly. Before Blaise says your answer is right
  or wrong, he checks it.
- **Blaise in your pocket.** On a call from your phone, tap *Snap a problem* and photograph a worksheet. It goes straight
  to your PC, encrypted like your voice.
- **A tutor over your shoulder.** *"Sit with me while I do my homework"*: he speaks up for a clear mistake and offers a
  small nudge when you're stuck, never the answer.
- **My progress.** What you really remember, goals reached on time and what you got done this week, all from your own
  records.

## Also in Blaise

- **Maths, solved and checked.** Full working on the board, from algebra to differential equations, and every answer
  is checked by calculation before you see it.
- **It sees what you're working on.** *"Look at this"* reads the window you're in. *"Check my work"* finds your first
  mistake and gives a hint, not the answer.
- **Study like the research says.** Flash cards with spaced reviews (bring your Anki decks and Quizlet sets), practice
  that brings your mistakes back, an exam predictor, and Physics, Chemistry and Bio labs.
- **Your room and your day.** Calendar, tasks, alarms, a morning briefing, Spotify and smart lights.

## Download

1. Open **[Releases](../../releases/latest)** and download **Blaise-5.0.0-Setup.exe** (about 160 MB).
2. Run it. Because Blaise isn't code-signed yet, Windows may show **"Windows protected your PC"**. Click
   **More info → Run anyway**. Updates after that are different: every update is checked against Blaise's own
   signature before it installs.
3. Create your Blaise account, then get your **free Gemini key** in about 30 seconds: press *Get my free key*, press
   *Create API key* in Google AI Studio, and copy it. Blaise fills it in by himself.

Installed copies update themselves.

## What you need

- Windows 11 64-bit (Windows 10 should work; tell us if it doesn't)
- A microphone, and an internet connection
- A Google account (for the free Gemini key)
- Optional: a phone, to call Blaise and snap problems

## Privacy, in short

- Your voice goes to Google Gemini while Blaise is awake, with **your own key**. Before that, Blaise only listens for
  its name, on your PC.
- Your notes, grades, files and voiceprint stay on your PC (the voiceprint is encrypted and never leaves it).
- Blaise only looks at your screen when you ask. Calls and photos from your phone are encrypted end to end. Full
  details: the privacy policy inside the app (Settings → About).

## Feedback

Blaise can make mistakes. Please tell us what breaks and what you'd love: thumbs up/down in the chat, *Send crash
reports* in Settings, open an **[issue](../../issues)**, or email **rytomaaaaa@projectblaise.com** (also for privacy
requests and security problems; please report those privately).

*Older beta versions (1.x): [Blaise-Downloads](https://github.com/rytomaaaaa/Blaise-Downloads).*
