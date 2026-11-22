# GENUS · Structures

**Global and nonperturbative structure.** Examples include: wavefunction interpretations of the topological string, BPS invariants as Stokes data for Riemann–Hilbert problems, resurgence analysis, open/closed wavefunctions and quantum mirror curves.

This is one of the four thematic repositories of
[GENUS](https://github.com/genus-collab), a public collaborative
workspace for research in topological strings and enumerative geometry.
Everything here is a *workshop* document: in progress, often AI-assisted,
not refereed, and credited to the GENUS collaboration. Curated, human-written
surveys go to arXiv through the distillation process described in the
[Community Charter](https://github.com/genus-collab/meta/blob/main/CHARTER.md).

## How to take part

1. **Propose** a project: open an issue with the *Project proposal* template.
2. **Start** it: open a PR copying `projects/_template/` to `projects/<project-name>/`.
   Once merged, the project is **Active**.
3. **Work** openly through commits and PRs. Keep `README.md` (status, methodology,
   claim status) up to date and commit the compiled `output/main.pdf`.
4. **Complete** it when the PDF is a coherent body of results, the code reproduces
   its outputs and the methodology statement is accurate; the Strand Lead
   merges the final PR and updates [`INDEX.md`](INDEX.md).

Cross-strand projects live in the most relevant repo, with a cross-reference
in the others' `INDEX.md`.

## Claim status labels

| Label | Meaning |
|---|---|
| `conjectural` | Stated without proof or decisive evidence |
| `numerically supported` | Supported by computation, not proved |
| `AI-proposed, unchecked` | An AI-produced argument no human has yet checked |
| `proved (human-checked)` | Checked by a contributor independent of the argument's originator |
| `formally verified` | Machine-checked, with the formal statement validated by a subject expert |

In LaTeX use `\genusstatus{<label>}` from `genus.sty` (in `genus-collab/meta`).

## Strand Leads

- Strand Lead: *to be appointed by the Steering Committee*
- Deputy: *to be appointed*

## Licence

See [`LICENSE.md`](LICENSE.md): CC BY 4.0 for text and PDFs, MIT for code, CC0 for data (provisional).
