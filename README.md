# Openings, Explained

**[Read the GitHub Pages collection](https://knightway8.github.io/chess16/)**

Understand what opening moves accomplish, one lesson at a time.

For players who know the legal moves and want reasons instead of long memorized variations.

## Format

- 16 direct lessons, each a self-contained HTML file with its own styles and embedded vector chess pieces.
- 32 lesson diagrams: the starting position and the result of the fully explained line.
- Visible explanations throughout: no answer inputs, hidden solutions, scores, progress controls, or client-side JavaScript.
- One printable collection, Markdown notes, and PGN move sequences.

A single lesson can be saved or copied on its own and read offline. Navigation to other lessons requires those neighboring files, but the lesson text and diagrams do not. Open [collection.html](collection.html) and use your browser’s Print command to print or save as PDF.

## Lessons

1. [Central pawns make room for the pieces](lessons/01-central-pawns-make-room-for-the-pieces.html)
2. [Develop toward useful work](lessons/02-develop-toward-useful-work.html)
3. [Castling connects safety with development](lessons/03-castling-connects-safety-with-development.html)
4. [An early queen can become a target](lessons/04-an-early-queen-can-become-a-target.html)
5. [The f7 pawn begins with only one defender](lessons/05-the-f7-pawn-begins-with-only-one-defender.html)
6. [The Queen’s Gambit challenges a central pawn](lessons/06-the-queens-gambit-challenges-a-central-pawn.html)
7. [The Sicilian trades a flank pawn for a central pawn](lessons/07-the-sicilian-trades-a-flank-pawn-for-a-central-pawn.html)
8. [A pawn chain has a base](lessons/08-a-pawn-chain-has-a-base.html)
9. [Develop a bishop before closing its diagonal](lessons/09-develop-a-bishop-before-closing-its-diagonal.html)
10. [A fianchetto puts a bishop on a long diagonal](lessons/10-a-fianchetto-puts-a-bishop-on-a-long-diagonal.html)
11. [A closed center gives plans time to develop](lessons/11-a-closed-center-gives-plans-time-to-develop.html)
12. [A gambit exchanges material for opportunities](lessons/12-a-gambit-exchanges-material-for-opportunities.html)
13. [Sometimes development is worth more than grabbing a pawn](lessons/13-sometimes-development-is-worth-more-than-grabbing-a-pawn.html)
14. [A central break must include the opponent’s forcing reply](lessons/14-a-central-break-must-include-the-opponents-forcing-reply.html)
15. [Small pawn moves can expose a large diagonal](lessons/15-small-pawn-moves-can-expose-a-large-diagonal.html)
16. [The opening ends when the position gives you a plan](lessons/16-the-opening-ends-when-the-position-gives-you-a-plan.html)

## Four companion collections

| Repository | Collection | Live site |
| --- | --- | --- |
| [chess15](https://github.com/knightway8/chess15) | Chess, Clearly | [Read](https://knightway8.github.io/chess15/) |
| [chess16](https://github.com/knightway8/chess16) | Openings, Explained | [Read](https://knightway8.github.io/chess16/) |
| [chess17](https://github.com/knightway8/chess17) | Tactics, Made Visible | [Read](https://knightway8.github.io/chess17/) |
| [chess18](https://github.com/knightway8/chess18) | Endgames, Step by Step | [Read](https://knightway8.github.io/chess18/) |

## Verification and maintenance

[Sources and verification](sources.html) explains the scope. [VERIFICATION.json](VERIFICATION.json) records legal move, diagram, PGN, self-containment, and directory-size checks. The endgame collection also includes exact tablebase results. Illustrative tactical continuations are not claims of exhaustive analysis.

Edit [source/course.json](source/course.json), run `node tools/build.mjs`, then run `node tools/verify.cjs`. All directories must remain below 1,000 entries.

GitHub Pages publishes the root of `main` through `.nojekyll`. Default-branch rules require pull requests and block force pushes and branch deletion, without bypass actors. An owner can still alter settings or delete a repository.

## Credits

Original AI-created lessons prepared for knightway8. Cburnett pieces by Colin M. L. Burnett are supplied under GPL-2.0-or-later, with [unmodified SVG sources, provenance, and license](source/pieces/README.md). The artwork’s full license is also embedded as a comment in each standalone HTML file. chess.js is used for authoring checks under its [BSD-2-Clause license](vendor/chess-LICENSE.txt).
