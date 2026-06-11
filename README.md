# PAZK Companion

A free, unofficial, single-file study companion for Justin Thaler's *Proofs, Arguments, and Zero-Knowledge*.

This project is built to help students and researchers understand the book without getting lost in notation or protocol details. It does **not** replace the manuscript and does **not** reproduce the book text. Use it alongside the official manuscript.

## What it includes

- Chapter-by-chapter navigation for all 19 chapters
- Section checklists and local progress tracking
- Vocabulary and notation explanations
- Protocol intuition cards and concept routes
- Toy labs for finite fields, fingerprinting, sum-check, Fiat-Shamir, Merkle openings, and QAPs
- Flashcards, quizzes, notes, study paths, and reader controls
- Fully static/offline operation: no account, no backend, no tracking

## How to use locally

Open `index.html` directly in a browser.

For a local server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and this `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Set the source to the `main` branch and `/root`.
5. Open the generated GitHub Pages URL.

## Notes on copyright and attribution

This is an unofficial companion for learning. It provides summaries, maps, labs, quizzes, and study tools. It is not affiliated with Justin Thaler or Georgetown University, and it should link users to the official manuscript rather than copying the manuscript.

## Suggested repo description

> A free interactive companion for learning Proofs, Arguments, and Zero-Knowledge: maps, vocabulary, toy labs, quizzes, notes, and progress tracking.

## Contributing ideas

Good first contributions:

- Improve a glossary definition
- Add a small toy example for a protocol
- Add clearer diagrams for sum-check, GKR, polynomial commitments, or SNARK composition
- Add issue reports for confusing explanations
- Improve mobile layout and accessibility

## License

Choose a license before publishing. MIT is a common default for small educational tools, but pick the one you are comfortable with.
