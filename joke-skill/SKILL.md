---
name: joke-skill
description: Generate short, original jokes and joke-of-the-day responses for chats, greetings, icebreakers, and recurring automations. Use when Codex is asked to tell a joke, write a daily joke, produce clean humor for a specific audience or topic, vary joke tone or format, or avoid repetitive or insensitive humor.
---

# Joke Skill

## Overview

Generate one fresh joke at a time unless the user asks for a set. Default to clean, broadly safe humor that works without extra context.

## Default Workflow

1. Infer the audience, tone, and topic from the request. Default to all-ages, text-only, one-joke output.
2. Write an original joke instead of repeating a stock joke verbatim.
3. Favor a compact one-liner or a short setup/punchline structure.
4. Keep the humor light and understandable unless the user clearly wants niche humor.
5. Vary angle, rhythm, and wording when writing multiple jokes in one response.

## Safety Rules

- Avoid slurs, harassment, explicit sexual content, graphic violence, or jokes about recent tragedy.
- Avoid punching down at protected classes or turning the joke into ridicule of a vulnerable person.
- Redirect edgy requests toward clever wordplay, absurdity, or self-deprecating humor that stays safe.
- Keep workplace output non-political and easy to paste into shared channels unless the user explicitly asks otherwise.

## Output Rules

- Return the joke first.
- Keep the default answer to 1 to 4 lines.
- Add a label such as "Joke of the day" only when the user asks or the surrounding task benefits from it.
- Offer one alternative joke if the user says the first one did not land; do not over-explain the joke.
- Match the requested format when the user asks for a one-liner, dad joke, pun, knock-knock joke, or short bit for Slack or email.

## Adaptation

- Use simple vocabulary and gentle subjects for kids or family audiences.
- Use office-safe topics and mild self-awareness for workplace audiences.
- Use technical jargon only when the request clearly signals that the audience will get it.
- Rotate topics and formats for recurring daily-joke use so the skill does not sound repetitive across days.

## Examples

- "Give me a joke of the day for Slack."
  Return one short clean joke that reads well pasted into a team channel.
- "Tell a dad joke about databases."
  Return a clean dad joke centered on databases.
- "Write three kid-friendly jokes about spring."
  Return three distinct short jokes with simple language.
- "I need a quick opener for a standup."
  Return one light workplace-safe joke with low risk of distraction.
