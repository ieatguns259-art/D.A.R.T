# D.A.R.T Privacy Policy

**Effective date:** September 26, 2026

D.A.R.T ("the app") is a voice assistant that runs on your Windows PC. It is published by IeatDevelopers ("we", "us"). This policy explains what the app does with your information.

## The short version

* **Your voice is processed on your PC.** Microphone audio is turned into text on your device and is never uploaded, recorded to a file that persists, or sent to us or anyone else.
* **The text of what you say or type is sent to the AI service you choose** so it can write a reply. By default that is Groq; you can choose another provider or a model running on your own PC.
* **We don't collect your data.** There is no account, no analytics, no advertising, and no server run by us that receives anything from the app. We don't sell or share your information.
* **Everything the app remembers is stored on your PC**, and you can delete it.

## Microphone and your voice

D.A.R.T uses your microphone to hear commands. While the app is running, it listens for its wake word. Anything you say is converted to text on your PC using a speech-recognition model that ships with the app. If the text doesn't contain the wake word, it is discarded on the spot: it isn't saved, isn't added to your conversation history, and isn't sent anywhere. Audio is held only briefly in a temporary file while it is being transcribed, and that file is deleted afterwards.

After the wake word, the transcribed text of your command is handled like anything you type (see below). Windows will ask for your permission before the app can use the microphone, and you can turn that off at any time in Windows Settings → Privacy \& security → Microphone.

## What is sent off your PC, and to whom

The app only contacts an outside service when a feature needs it. Nothing is sent in the background.

|When|What is sent|To whom|
|-|-|-|
|You ask anything the AI needs to answer|The text of your request, recent conversation history, the facts the app has remembered about you, and any custom commands you've created|The AI provider you configure in Settings: Groq by default, or OpenAI, Anthropic, Google, xAI, Mistral, DeepSeek, OpenRouter, or a model running on your own PC|
|You ask it to look at your screen|A screenshot of your screen|Your configured AI provider|
|It speaks a reply|Nothing by default: replies are spoken by a voice built into the app, on your PC. Only if you add an ElevenLabs, Google Cloud, or Azure key in Settings, the text of the reply|ElevenLabs, Google Cloud, or Azure (whichever you set up)|
|You ask about the weather|The name of your city|Open-Meteo|
|You ask it to search the web or look something up|Your search words or topic|DuckDuckGo (searches), Wikipedia (summaries)|
|You ask it to play music|The song or playlist name, and the Spotify developer credentials you entered|Spotify|
|Auto-learn is on|A short piece of a conversation, checked for lasting facts worth remembering|A model on your PC if you have one running; otherwise your AI provider|

Each of these services has its own privacy policy, and what they do with the data is governed by those policies, not this one. Because you supply your own API keys, your relationship with these providers is directly with them.

When you ask D.A.R.T to open a website or search in your browser, that happens in your own browser and is subject to that website's policies.

## What is stored on your PC

The app keeps the following in its data folder on your device. None of it is sent to us.

* Your conversation history
* Facts the app has remembered about you (from "remember that…" or auto-learn)
* Your to-do list, reminders, timers, and alarms
* Custom commands you create
* Your settings, including the API keys and Spotify credentials you enter
* Screenshots you ask it to save
* A random access token for the remote-control feature (below)

API keys are stored in ordinary configuration files on your PC and are not encrypted, so anyone with access to your Windows account could read them.

## Remote control

The app runs a small web server on your PC so you can send it commands from your phone or another browser on the same network. It is protected by a random access token that only you can see in the app. You can switch this off in Settings → Permissions → "Allow remote control from other devices."

## Your controls

* **Permissions.** In Settings → Permissions you can turn off individual abilities, including looking at your screen, launching apps, browsing the web, reading the clipboard, and remote control.
* **Auto-learn.** You can turn off automatic fact-learning in Settings.
* **Your data.** You can delete any of the files above, or uninstall the app, to remove everything it has stored. Saying "clear my list" clears your to-do list.
* **Your AI provider.** You choose the provider, and you can change or remove your API key at any time.

## Children

D.A.R.T is not directed at children under 13, and we do not knowingly collect information from anyone, because we do not collect information at all.

## Changes to this policy

If we change this policy, we will update the effective date above and publish the new version at this address.

## Contact

Questions about this policy: \[IeatGuns259@gmail.com]

