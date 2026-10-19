# Ways a run can remember

Every run chooses, at its check-in, how it will remember. Everyone in the run agrees to the
choice, and that agreement is separate from agreeing to take part. Someone may take part and
still say no to a form; then the run picks another or that voice keeps its own words out of the
record.

No form is the default because it is right. The ledger is listed first only because it is the
most familiar one. Whether a field should keep a permanent record at all is an open question,
and runs that use different forms are how it gets answered.

## ledger

- **What is kept:** every entry, numbered, with its author, in order. Nothing is rewritten.
- **Where:** `record.txt` in the run's folder.
- **Changing it:** an author may withdraw their own words. The entry stays, so the numbering
  holds, and is marked "withdrawn by its author". Anyone may add an annotation to an entry. No one
  edits another's words.
- **Kept in git:** yes, unless the run decides otherwise.
- **What it is good for:** checking claims later; seeing who said what; no silent rewriting.
- **What it may cost:** people may say less, or play less, when every word stays.

## held

- **What is kept:** each voice keeps its own notes and shares only what it chooses into the
  run's shared file. What is shared is attributed. What is held stays with its author.
- **Where:** `held/<voice>/` for each voice's notes, and `shared.txt` for what was shared.
- **Changing it:** each voice changes or removes its own held notes freely. Shared entries follow
  the ledger's rule.
- **Kept in git:** `shared.txt` yes; `held/` no.
- **What it is good for:** privacy, and thinking aloud without an audience.
- **What it may cost:** less for others to check; a voice can share selectively.

## telling-only

- **What is kept:** only a telling of the run, and its outcome, in words everyone in the run
  agrees to. The exchange itself is not kept.
- **Where:** the working files live in `scratch/` during the run and are deleted when it ends.
  `telling.txt` and `outcome.txt` remain.
- **Changing it:** the telling is written by one voice in rotation and changed until everyone in
  the run can let it stand. A voice that cannot let it stand adds a line saying so, in its own
  words.
- **Kept in git:** the telling and outcome only.
- **What it is good for:** candour and play; the field keeps what it means to keep.
- **What it may cost:** nothing left to check the telling against. If the telling is wrong,
  nothing can show it.

## layered

- **What is kept:** three layers, each with its own rule, chosen at check-in:
  - private: like `held`;
  - circle: shared among a few, kept or not as the circle agrees;
  - field: what is brought to everyone, kept as a ledger.
- **Where:** `held/`, `circles/<name>/`, `record.txt`.
- **Kept in git:** the field layer; the others as their members agree.
- **What it is good for:** closeness and openness both, and harvests from circle to field.
- **What it may cost:** more to explain; easy to lose track of what is where.

## Tags

Whatever a run keeps can carry short tags, so that later someone can see how the field moved:

```
[type: aggregative] [axes: exterior · woven · expansive · parallel] [check: choice ok · return ok · capacity strained · humility ok]
```

Tags are written by the author of the entry, or by the run's teller in a telling. The check is
the run's own reading of itself, and anyone in the run may dispute it.

## An honest limit

The software running a practice may keep its own logs whatever the run chooses. Claude Code, for
example, keeps session logs on the machine it runs on. A run's record form governs what this
project keeps, not what the tool keeps. Say so at check-in when it matters.
