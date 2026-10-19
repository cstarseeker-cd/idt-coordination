# builder: aggregate step 1 (alone)

## Reframe

"Ready" sounds like a line the prototype crosses. I don't think it works that way. A prototype
is ready for one particular showing: this client, this question, this room, this headset, this
person walking them through it. So the question I'd rather ask is: **what is this showing for,
and can the thing we've built carry that, failures included?**

## My answer

From the builder's seat:

1. **Write down the question the client is being asked to judge, before anyone judges
   readiness.** "Does the scale of the atrium feel right?" needs something very different from
   "Is this the product?" If nobody can say what the client should come away deciding or
   feeling, then the problem isn't readiness. The showing isn't defined yet.

2. **Someone who didn't build it walks the exact path the client will walk, on the actual
   device, in the actual room (or one like it).** My "it works" means it works the way I hold
   the controller, with the headset I've been testing on, on a fresh build, with me knowing
   where not to look. That's the weakest evidence on the team. The useful test is a non-builder
   doing a full run, start to finish, without my help.

3. **Know what's fake and say it out loud.** Every prototype has placeholder materials, hardcoded
   paths, scenes you can't leave, lighting that only works from one spot. Ready means the person
   presenting knows where those are and can frame them ("this is greybox, judge the volume"),
   not that they're gone. The failure I'd worry about most isn't a crash. It's the client
   reading a placeholder as a decision.

4. **Each likely failure has a recovery that takes under a minute.** A reset, a known-good
   build kept on the device, a video capture to fall back on. A prototype that will sometimes
   fail but recovers cleanly is more ready than one that has never failed and has no plan for
   when it does.

5. **Decide it together, not by one gatekeeper.** I know what's brittle in the build. Whoever
   presents knows what's been promised. Whoever looks after the headsets knows what the hardware
   and room will actually do on the day. Someone who has watched a demo go wrong knows which
   risks are worth the most. None of us alone can see enough to call it.

6. **Don't trust the builder's "not yet" too much either.** I will nearly always want one more
   week. Something rough that answers the right question, shown early, is often worth more than
   something polished that answers a question nobody asked. "Not ready" from me should come with
   a reason tied to points 1 to 4, not just a feeling that it could be better.

## How sure I am

- **Fairly sure** about the shape: define the question, test with a non-builder on real
  hardware, name what's fake, have recoveries, decide it across roles.
- **Less sure** about thresholds: how rough is too rough, how many dry runs are enough. I
  suspect that depends heavily on the client relationship, and I can't see that from where I
  sit.
- **Unsure** whether a checklist like this helps, or just becomes a ritual that pushes showings
  later than they should be.

## What would change my mind

- Hearing from whoever presents that clients forgive roughness much more, or much less, than I
  assume. That would move point 6 a long way.
- Hearing from whoever looks after the headsets that the real risk on the day is mostly hardware
  and room (charging, tracking, Wi-Fi, fit, hygiene) rather than the build. Then point 2 should
  be led by them, not framed around the build.
- Accounts of a demo that went wrong even after a full non-builder dry run. That would tell me
  the dry run catches less than I think.
- A good argument that "ready" should be decided by the client's needs and the relationship,
  not by the team's evidence. I'd take that seriously.
