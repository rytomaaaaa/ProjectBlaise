# Privacy policy

*Version 2 · 12 November 2026 (adds the camera and hand gestures)*

## The short version

Your account keeps who you are (email, name), your plan and role, and - unless you switch it off - your memory notes, preferences, saved items, notes and flash cards, so they're the same on every computer you use. Your files, keys and conversation history stay on your computer. What you say is sent to the AI services that answer you.

## What our account server keeps

- Your email address, the name you gave, your password (stored hashed by our provider, Supabase; we can't read it), your role (user or admin), your plan, whether the account is suspended, which terms you accepted, when you joined and when you last used Blaise.
- Unless you switch off "Keep my notes and memory in my account" (Settings): your memory notes, your preferences for how Blaise talks, your saved displays, your notes and lists, your flash cards, and your study progress (exams, topics, mistakes to review). Only you can read them (each account is locked to its own data). They're deleted with your account.
- Blaise's server handles your requests: it checks your account, builds the instructions for each voice conversation (from your memory notes and preferences), runs the study and learning tools, and passes your Gemini key to Google for that one request, without keeping the key. It doesn't keep what you asked; its host may keep short technical logs (time, address, errors) for a few days.
- If you turn on crash reports, or say "send the crash report": the error, where in Blaise it happened, Blaise's version and your Windows or macOS version. Never what you said, your files or your keys.
- Admins of this copy of Blaise can see the account list (names, emails, plans, last-used dates) so they can help and keep it safe.

## What stays on your computer

- Conversation history on the board, feedback ratings, reminders and the activity log, plus a working copy of the data kept in your account (in %APPDATA%\Blaise). With "Keep my notes and memory in my account" switched off, everything listed above stays only here.
- Your API keys and passwords for plugins, in Windows Credential Manager (on a Mac, the macOS Keychain).
- **Windows Hello lock** (if you switch it on): Windows checks your face, fingerprint or PIN and only tells Blaise "yes" or "no". Blaise never sees, records or keeps your face, fingerprint or PIN.
- **Code you write in the Terminal**: the project files are kept in Documents\Blaise\Code on your computer. Code only leaves your computer when you ask Blaise about it (it goes to the AI service answering, like any question).
- **Focus guard** (only while a focus session you started is running): Blaise checks the name and title of the window in front every few seconds, on your computer, to notice distractions. Nothing is captured or sent; only the totals (minutes focused, which app distracted you) are kept, on this computer.
- **Grades, applications, review schedules and bibliographies** you add are kept only on this computer.
- **Smart lights**: Blaise talks to your lamps directly over your home Wi-Fi. For Philips Hue it asks Philips' public discovery service where your Hue Bridge is on your network; nothing about you is sent.

## What is sent to other services

- **Your voice** goes to Google's Gemini Live to understand you and answer, while Blaise is awake. Blaise only listens for its wake word on your computer before that.
- **Questions and thinking** (math, searches, explanations, plans, the thinking agent and other hard questions) go to the AI services Blaise uses: Google Gemini with your own key and - only if you've added their keys - Groq, Cerebras, NVIDIA, OpenRouter, GitHub Models, Anthropic, OpenAI, DeepSeek, Mistral, xAI, Together, Fireworks, Token Harbor, or a service you added yourself. Or to a model on your computer (Ollama, LM Studio), which sends nothing. When the thinking agent works on a task, what its tools find (a file's text, your calendar, a web page) is sent with the task to the service doing the thinking.
- **Screen control**: to click and type for you, Blaise reads the names of the buttons, boxes and links in the window in front (on your computer, through Windows' accessibility system) and sends that list to a fast AI service to choose the next step. A screenshot goes to Google Gemini only when a task needs to see the screen.
- **Voice recognition** (only if you choose to teach Blaise your voice, in Settings): Blaise makes a voiceprint - a list of numbers that describes how your voice sounds, not a recording - from three sentences you read out loud. It is kept only on your computer, encrypted so only your Windows account can read it, and is never sent to us or to anyone else. It is used only to tell your voice from other people's when you talk to Blaise. Delete it any time with "Forget my voice" in Settings (uninstalling Blaise with its data removes it too).
- **Looking at what you're working on**: when you ask Blaise to look at your screen or check your work, a picture of the one window you're working in (never the whole desktop, never Blaise's own window) goes to Google Gemini with your key to be read, and is not kept. A photo or copied picture you ask it to check is handled the same way. When you ask Blaise to **watch your window**, he looks at that one window only after it has changed and you've paused - at most once every 20 seconds - and stops after 30 minutes or when you say "stop watching". Off in Private mode.
- **Your camera** (only if you switch on "Let Blaise use the camera" in Settings - it's off until you do): when you ask Blaise to check your work on paper, he takes a few still pictures and keeps the clearest one in memory only - nothing is recorded or saved, and a camera light shows in Blaise's window the whole time the camera is on. That picture goes to Google Gemini with your key, only to copy down what's written; then just that copied text goes to the AI service that checks maths. The result (which line, what went wrong) is kept in memory for 15 minutes, without the picture.
- **Hand gestures** (only while you've turned gesture mode on): the camera finds your hand on your computer, and only the moves it makes (point, click, scroll...) reach Blaise. Nothing about your hand or what the camera sees is sent anywhere, and the hand-tracking library's own usage reports are blocked. It switches itself off when you say "stop gestures", press Esc, or put your hand away for a minute.
- **Spotify**, if you connect it: Blaise uses Spotify's own service to play, pause, shuffle, show what's playing and your liked songs, and Spotify's player in a small browser window. Searches you ask Blaise to open ("search X on YouTube") go straight from your browser to that site.
- **Your own things, when a task needs them**: to plan or answer about your schedule, goals, notes or a file, Blaise reads them on your computer and sends the relevant part with the question to the AI service answering it (for example "plan my week" sends this week's and next week's calendar). It doesn't send them otherwise.
- **Study files** you add to the study library are read by the study coach (through Blaise's server and Google Gemini with your key) to map their topics. The files themselves stay on your computer.
- **Camera photos and pictures** you ask about are sent to the vision model, and not kept.
- **Lecture notes** (only when you ask Blaise to record a lecture, and he asks you first): what your microphone hears is turned into text a few minutes at a time by Google Gemini with your key; the audio itself is never saved. The text and the notes are kept on your computer. Record people only when they're OK with it.
- **Citations**: to cite something, Blaise asks doi.org (for a DOI), Open Library (for an ISBN) or the web page itself for its details. **A CV you ask Blaise to review** is read on your computer and its text sent to the AI service reviewing it, then not kept.
- **Web searches** go to public search engines (through DuckDuckGo's search library), including study questions Blaise checks against trusted references (NCBI Bookshelf, OpenStax, WHO, NICE and similar); study videos and lessons come from MIT Learn and MIT OpenCourseWare.
- **Plugins** you switch on talk to their own services: for example weather (Open-Meteo), news feeds, Wikipedia, dictionary, currency rates, Wolfram|Alpha, and your own calendar or email links.
- **Our providers**: accounts and synced data are kept by Supabase; Blaise's server runs on Vercel.

Those services handle data under their own privacy policies. Private mode in Settings keeps everything it can on your computer (no thinking help, web search or screen control while it's on).

## What we don't collect

- No advertising, no tracking or analytics cookies, and no selling or renting of your data to anyone.
- No location tracking, no contacts upload and no recordings of your voice: the wake word is heard on your computer, and what you say while Blaise is awake goes to Google to be answered, not to us.
- Only what an account needs (listed above). We don't ask for your birthday, address or phone number; at sign-up you only confirm your age.
- Third-party code inside Blaise is listed in its licences page; none of it is an advertising or tracking kit.

## Emails

We don't send marketing or newsletter emails. The only emails from us are the ones your account needs (confirming your address, resetting your password). Emails you send with Blaise's help go from your own email account, to the people you choose.

## Cookies

Blaise doesn't use tracking cookies. The cookie policy in Blaise (Settings, About) lists the little it does keep in your browser.

## How your data is protected

- Keys and sign-ins are kept in Windows Credential Manager; your tasks, people, habits, calendar entries and email contacts on this computer are encrypted so only your Windows account can read them.
- Everything sent between Blaise, its server and the services it uses goes over encrypted connections (HTTPS).
- Your account data is kept by Supabase with each account locked to its own data.
- Blaise keeps a security log on your computer (sign-ins, changed settings, emails sent - never their content or your keys).
- We take reasonable care, but no system is completely secure, and we can't guarantee your data will never be lost or accessed without permission (see the terms of use).

## Your choices

- Delete local data in Settings at any time. Delete your account and everything kept with it in Blaise (menu, Account, "Delete my account"), or ask at rytomaaaaa@projectblaise.com - we'll confirm within 30 days.
- Depending on where you live you may have rights to see, correct, move or delete your data; write to rytomaaaaa@projectblaise.com.

## Children

Blaise is for people aged 13 and over (16 and over in the European Union and the United Kingdom). At sign-up people confirm they meet the minimum age. We don't knowingly collect personal information from anyone younger: if we learn that an account belongs to a child under the minimum age, we delete it and its data. A parent or guardian who thinks their child has an account can ask us at rytomaaaaa@projectblaise.com and we'll delete it.

## Changes and contact

We'll show changes in Blaise before they apply. rytomaaaaa@projectblaise.com · rytoma

This is the same policy Blaise shows in Settings, About.
