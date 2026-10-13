# WordLoop

A flashcard app for learning new words, inspired by Anki. Every word you study loops back to you after a delay that depends on how well you knew it.

## How it works

1. The app shows you a flashcard with a word on the front.
2. You try to recall the meaning, then flip the card to check.
3. You rate the card as **Easy**, **Medium** or **Hard**.
4. The card comes back for review after a period based on your rating.

## Features

- **Flashcards**: a word on the front, its meaning on the back.
- **1000 words**: a built-in deck of 1000 new words to learn.
- **3 levels per card**: rate each card Easy, Medium or Hard.
- **Scheduled reviews**: each level sets how long before the word comes back.
- **Saved progress**: a database stores each user's progress, so study sessions pick up where they left off.

## Review levels

| Level  | Meaning                    | Comes back after |
| ------ | -------------------------- | ---------------- |
| Hard   | Did not remember the word  | 1 day            |
| Medium | Remembered with effort     | 3 days           |
| Easy   | Remembered immediately     | 7 days           |

These periods are starting values and may change.

## Saved progress

For each user and each word, the database keeps:

- the last level chosen (Easy, Medium or Hard)
- when the word was last reviewed
- when the word is due to come back

## Status

In planning. The tech stack and setup instructions will be added once development starts.
