# Degree Rules

This repository contains unofficial degree rules files for use with the
[transition-checker](https://github.com/llimeht/transition-checker/) tooling.

> **These files are entirely unofficial.** They are best-effort transcriptions of the
> handbook rules and may contain accidental errors or omissions. 
> They may also contain proposed tweaks to the official academic rules that are being considered
> as part of the work to plan the flex-semester transition - do not over-interpret such inclusions.
> They do not constitute academic
> advice and do not replace the authoritative rules published in the UNSW Handbook.

## Contents

Each JSON file encodes the degree requirements for one specialisation (or one time-bounded
variant of a specialisation). File names follow the pattern:

- `<STREAM><PROGRAM>.json` — rules applying across all handbook years, e.g. `CEICAH3707.json`
- `<STREAM><PROGRAM>-<YYYY>-<YYYY>.json` — rules for a specific handbook year range,
  e.g. `CEICDH3707-2020-2025.json`

The file format is documented in
[FILE-FORMATS.md](https://github.com/llimeht/transition-checker/blob/main/FILE-FORMATS.md)
in the main repository.

## Usage

Place this repository (or a clone of it) at `rules/` inside a clone of the
transition-checker repository, then follow the instructions in the main `README.md`.
