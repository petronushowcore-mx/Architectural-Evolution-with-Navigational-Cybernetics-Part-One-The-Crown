# MANIFEST — Architectural Evolution with Navigational Cybernetics. Part One — The Crown

Inventory of every source document and runnable harness module in this repository. No PDF, detached signature, OpenTimestamps receipt, cover, or deposit-side metadata is part of this GitHub repository.

## Documents

| File | Role |
|---|---|
| `CROWN-OF-EVOLUTION-EN.md` | canonical English manuscript — Layers; Will; the Unit and field I; crowns of evolution; nested substrates; retained fields; computation of nested reality; change of position; empirical supports; closure |
| `README.md` | orientation, status, citation, and run instructions |
| `LICENSE` | repository-wide CC BY-NC-ND 4.0 notice |
| `MANIFEST.md` | this inventory |
| `docs/architecture.svg` | non-normative visual aid for `README.md`; not part of the citable manuscript |

## Harness

Python 3 standard library only. The module exits non-zero on a failed check and produces the same result under normal and optimised interpreter modes.

| Module | Backs | Count |
|---|---|---|
| `gate_en.py` | display and inline mathematics delimiters; heading sequence; editorial-marker absence; declaration-contract presence; section-reference range; escape artefacts; brace balance; quote convention and punctuation; heading-case consistency; DOI completeness for cited corpus works | 12 checks |
| `gate_en.py --teeth` | targeted mutation cases for the registered checks, plus one declared survivor that distinguishes structural checking from arbitrary prose identity | 17/17 registered cases |

## Running

From the repository root:

```bash
python -B harness/gate_en.py
python -B harness/gate_en.py --teeth
python -B -O harness/gate_en.py
python -B -O harness/gate_en.py --teeth
```

**Layout requirement.** `harness/gate_en.py` resolves `CROWN-OF-EVOLUTION-EN.md` at the repository root. A different path may be supplied through the `CROWN_MANUSCRIPT` environment variable.

**Scope.** The harness verifies the declared structural properties of this manuscript. It does not verify the cited sources, establish empirical claims, or substitute for mathematical reading.
