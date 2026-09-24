# Claude Onboarding

An interactive onboarding page for people who are new to AI, in **Spanish, French and English**.

Open `index.html` in a browser, or publish it with GitHub Pages.

`index.html` merges two pages into one, with the look of `onboarding-clawd-demo-v5-no-mascot-animation.html`:

- the **Claude onboarding** (guide, artifacts, one-month program),
- the **Claude starter logbook** (workshops, ranks, coach), now the **Workshop** view in the menu.

## What's inside

**Guide.** Claude introduces itself and asks simple questions first: text size (smaller, normal, bigger), pace (slower, normal, faster) and voice input. Then a 4-step onboarding: create a first result (an artifact), ask for a change, share a little about yourself (including hobbies), save it in a project. At a faster pace, explanations are shorter and optional steps can be skipped; at a slower pace, the project step is left out.

**Your month with Claude.** Small challenges spread over 30 days, a demo simulation to move time forward, and free Academy courses that unlock along the way.

**Workshop.** Hidden at first. It opens on day 7 of "Your month with Claude", once the person knows the basics. Exercises about the person's hobbies come first, followed by the general ones:

- **Which tool?** A quiz with everyday situations: Chat, Projects, Cowork or Claude Code.
- **Prompt builder.** Write a brief in four parts (context, task, constraints, output), with live hints, then have Claude review it.
- **Fix the prompt.** Pick the best rewrite of a weak request.
- **AI vocabulary.** 16 flashcards in Spanish, French and English.
- **Job site.** Concrete first steps, from foundations to finishing.
- **Rank.** Progress from Apprentice to Journeyman to Master craftsman.

Inside Claude, Claude writes the hobby exercises live from what the person shared. Elsewhere, the page uses pre-written exercises for eight hobbies (cooking, travel, sport, music, gardening, reading, DIY and crafts, family), in the three languages.

An **ES | FR | EN** switch translates the whole page. The first visit follows the browser language. The chosen language and progress on the general workshop exercises are saved in the browser. Nothing entered in the Guide is saved, including hobbies and the exercises made from them.

## About Claude's live answers

Live answers (artifacts, revisions, coach questions from the Workshop and the chat box) use the Claude artifact runtime, so they only work when the page is opened as a Claude artifact. Anywhere else (a local file, GitHub Pages), the Guide falls back to sample answers, and the chat explains that live answers are not available.

The coach keeps the conversation, can add a translation to each answer (a Workshop option, on by default), and has a Stop button while it answers.
