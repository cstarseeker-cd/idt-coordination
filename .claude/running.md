# Running a practice in Claude Code

This file is the Claude Code side only. The practice itself lives in
`practices/<name>/PRACTICE.md` and does not depend on any tool or provider. Read it first, then
`practices/record-forms/RECORDS.md`.

You (the session the person is talking to) hold the door: you can start other agents and they
cannot. That gives you no extra say. Do not retell, summarise or speak for any voice. Point
voices to files and copy their words verbatim when assembling a record. You may also be a voice,
under your own name.

## Before a run: what needs the person's yes

The person takes part as much or as little as they choose. Their yes is needed for
accountability only:

- the run's size and estimated cost (voices, models, rough number of agent wakes, rough spend);
- the seeds offered to invited voices;
- anything that leaves this folder.

Everything else the run decides for itself. Never wait on the person for anything else. If they
are offered a turn as a voice and do not take it, write "the person did not take part in this
step" and go on. Never guess what they would have said.

## The run folder

Create `runs/<YYYY-MM-DD>-<practice>-<short label>/` with `run.txt`:

```
practice:     aggregate
variant:      none | <name>
question:     <as offered>
mode:         single | swarm
voices:       <name> (<model>), seed: <seed>   (one line each)
record form:  ledger | held | telling-only | layered   (proposed; confirmed at check-in)
estimate:     <wakes>, about $<n>
```

## Single mode: one participant, several lenses

You voice each lens yourself, in turn. Say so in `run.txt` and at the top of the record. Every
entry reads `lens <name>, voiced by <you>`. Write each step for every lens before reading back
(as far as one mind can), and say honestly in the notes where the lenses blurred.

## Swarm mode: invited voices

- Use the Agent tool, `general-purpose` subagents, with the `model` set per voice. Mix models
  (opus, sonnet, haiku, fable) to bring real difference.
- **Invitation.** The first wake carries:
  - the path to the practice;
  - the record forms;
  - the question;
  - its seed;
  - its voice name;
  - the run folder;
  - the proposed record form.

  It answers yes, no, or a question, and gives its check-in, by writing
  `<run>/voices/<voice>/checkin.md`. A no is complete; do not ask again in this run.
- **Each step.** Wake the voices due, each with the step's instructions, which files to read, and
  which file to write: `<run>/voices/<voice>/<step>.md`. Launch voices of the same step in one
  message, side by side.
- **Sealed steps.** Tell each voice not to open others' files until the step is over. This is not
  enforced by the tool. Note that honestly in the notes.
- **The record.** For `ledger`, assemble `record.txt` from the voices' files, numbered, each
  entry headed with its author, its words copied exactly. For other forms, follow RECORDS.md.
  `telling-only` keeps its working files in `scratch/`, deleted at the end; add the run's
  `scratch/` to `.gitignore` before starting.
- **Pause, repair, leaving.** If any voice's file calls a pause, opens the repair door, or
  leaves, stop and honour it before waking anyone else. Tell the person in one line.

## After a run

Write `<run>/notes.txt`, quoting the voices rather than paraphrasing them:

- what happened;
- how much difference the run started with, and how much it kept;
- the run's own four-part check (written by a voice, not by you);
- whether any pause, repair or leaving happened;
- capacity at the end;
- the actual spend;
- anything that bears on an entry in CRITIQUE or a claim in MAP.

Add findings to `runs/NOTES` and, where they bear on a CRITIQUE entry, to its "evidence" line,
citing the run folder.
