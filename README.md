# Word Game

A SwiftUI Word Game

## Overview

This project is a simple word game built with SwiftUI. The user is given a random root word and must create as many valid English words as possible using the letters from the root word. The app checks for originality, possibility, and validity of each word entered.

## Features

- Randomly selects a root word from a bundled word list (`start.txt`)
- Users enter words using a text field
- Words must:
  - Not have been used already
  - Be possible to spell from the root word's letters
  - Be a real English word (checked with `UITextChecker`)
- Used words are displayed in a list with their letter count
- Error alerts for invalid entries

## How to Run

1. Open lab12.xcodeproj in Xcode (version 15 or later recommended).
2. Build and run the project on a simulator or device.
3. The game will display a random root word. Enter words in the text field and press return to submit.

## File Structure

- ContentView.swift: Main game logic and UI
- lab12App.swift: App entry point
- start.txt: List of possible root words (one per line)

## Example Gameplay

1. The app shows a root word (e.g., `silkworm`).
2. Enter a word like `milk` and submit.
3. If valid, it appears in the list. If not, an error alert explains why.

---

**Author:** Dana Barhoom  
**Created:** December 29, 2024
