# Workshop: Portuguese

## Purpose

Language workshop for learning Portuguese. Focused on the 30 most important Portuguese verbs and their conjugations, with example sentences and audio pronunciation.

## Target Audience

- **Level**: Beginner to lower intermediate
- **Native languages**: German, English, or Farsi speakers
- **Goal**: Build core verb vocabulary for daily conversation

## Structure

- **10 lessons** covering 30 core verbs
- **Interface languages**: Deutsch, English, Farsi
- **Teaching language**: Portuguese (pt-PT)
- **Features**: audio pronunciation, assessments, grammar labels, coach integration

## Labels

`Language`

## Coach

This workshop has coach integration via `coach.email` — learners can optionally send their assessment answers via email for feedback.

## Conventions

- `q` = Portuguese example sentence (teaching language)
- `a` = translation in interface language
- Labels mark tenses/forms
- Each verb has its own lesson with multiple example sentences

## Development

```bash
# Generate audio (Edge TTS)
bash generate-audio.sh deutsch/portuguese
bash generate-audio.sh english/portuguese
bash generate-audio.sh farsi/portuguese
```

## See Also

- [Open Learn Platform](https://github.com/openlearnapp/openlearnapp.github.io)
- [Workshop Guide](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/workshop-guide.md)
- [Lesson Schema](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/lesson-schema.md)
- [Workshop Creator Plugin](https://github.com/openlearnapp/plugin-workshop-creator)
