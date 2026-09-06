# Music Library System

## Description
This project implements a `Song` class for MusicTech Innovations' music library system. Each song tracks its own name, artist, and genre, while the class as a whole maintains global stats across every song created.

## Features

- **Instance attributes**: `name`, `artist`, `genre` — set on creation.
- **Class attributes**:
  - `count` — total number of Song objects created.
  - `genres` — list of all unique genres seen so far.
  - `artists` — list of all unique artists seen so far.
  - `genre_count` — dict mapping each genre to how many songs belong to it.
  - `artist_count` — dict mapping each artist to how many songs they have.
- These class attributes update automatically every time a new `Song` is instantiated.

## Running Tests
\`\`\`
pytest lib/testing/song_test.py
\`\`\`

## Test Results
![Passing tests](![alt text](image.png))