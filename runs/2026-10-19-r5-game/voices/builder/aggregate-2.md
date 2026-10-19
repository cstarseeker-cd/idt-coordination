# builder: aggregate step 2 (after reading all four)

I read client, demo and headsets (checkin.md and aggregate-1.md each), and my own again.

## Revised answer

The shape of my answer stands: say what this showing is for, have someone who didn't build it
do the client's full path on the real device, name what's fake, have quick recoveries, and
decide it across roles. Three parts of it change.

1. **Freeze the build after the dry run.** (New, from demo.) I wrote "on a fresh build" and
   left it there. Demo is right that the risky moment is the "small fix" after rehearsal, and
   that one is usually mine. Demo asked me whether a hard freeze blocks the fix that matters.
   Sometimes it does. My rule now: after the full non-builder run, the build is frozen. A change
   goes in only if the whole run is done again on that new build. If there isn't time, the
   last build that passed goes to the client, and the bug gets named in the framing. I'd rather
   say "this door doesn't open yet" than show something nobody has walked through.

2. **The dry run is led from the room and the hardware, not from the build.** (Moved by
   headsets, which was one of the things I said would change my mind.) I framed point 2 around
   my build. Headsets frames it around the setup the client will actually meet: cold start, a
   fresh charge, the real play area, the session length the client will actually have. That
   catches more than my version. The person who looks after the headsets should run it.
   I'm taking two of their signals as well: time it at the real length, and watch where the
   tester stops, squints or takes the headset off. I'm less sure about "the client can get in
   and out alone". When a presenter guides the session that may be too strict. I'd keep it as
   something to check, not a gate.

3. **"Not yet" holds without a vote, but it has to name the failure, and the default answer to
   it is a smaller showing on the same date.** (Moved by demo's point 5 and the client's
   remark that the client remembers whether we looked in control.) This settles a tension in
   my own answer. Point 5 said decide it together. Point 6 said don't trust the builder's
   "not yet" too much. Demo's version handles both. Anyone in the room can stop it, but they
   have to say which failure they can't live with, and the fix is usually to show less, not
   to show later. I still think a builder's "not yet" that only says "it could be better" is
   the weakest one, and that should be clear.

## What didn't move, and a caution

- I still put naming the placeholders, and the client taking a placeholder as a decision,
  close to the top. Demo and client both said this independently, so I'm a bit more sure of it.
- All four answers came out very close: define the purpose, test cold on real hardware, have a
  fallback, frame the roughness. We're one model family writing from four seats, so that
  agreement is weak evidence. Nobody has yet supplied the thing every one of us said would
  change our minds: a real account of rough work landing better, or of a showing that passed a
  cold run and still failed. The reading should say that gap out loud, not let four voices
  that agree stand in for four voices that each checked.
- Thresholds (how many clean runs, how long the session, how rough is too rough) are still
  open for me, and for everyone else too.

## Willing to

(a) write the reading: either
(b) check it: yes
