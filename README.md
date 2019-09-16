---
title: IMO Grand Challenge
permalink: /
---

The [International Mathematical Olympiad](https://www.imo-official.org/) (IMO) is perhaps the most celebrated mental competition in the world and as such is among the ultimate grand challenges for Artificial Intelligence (AI).

**The challenge: build an AI that can win a gold medal in the competition.**

To remove ambiguity about the scoring rules, we propose the formal-to-formal (F2F) variant of the IMO: the AI receives a *formal* representation of the problem (in the [Lean Theorem Prover](https://leanprover.github.io/)), and is required to emit a *formal* (i.e. machine-checkable) proof.
We are working on a proposal for [encoding IMO problems in Lean](https://github.com/IMO-grand-challenge/formal-encoding) and will seek broad consensus on the protocol.

Other proposed rules:

*Credit*. Each proof certificate that the AI produces must be checkable by the Lean kernel in 10 minutes (which is approximately the amount of time it takes a human judge to judge a human's solution). Unlike human competitors, the AI has no opportunity for partial credit.

*Resources*. The AI has only as much time as a human competitor (4.5 hours for each set of 3 problems), but there are no other limits on the computational resources it may use during that time.

*Reproducibility*. The AI must be open-source, released publicly before the first day of the IMO, and be easily reproduceable. The AI cannot query the Internet.

*Challenge*. The grand challenge is to develop an AI that earns enough points in the F2F version of the IMO (described above) that, if it were a human competitor, it would have earned a gold medal.

Note: this is only a preliminary proposal for the rules. To get involved in the discussion, please join our [Zulip channel](https://leanprover.zulipchat.com/#narrow/stream/208328-IMO-grand-challenge).

### Committee

- [Daniel Selsam](https://dselsam.github.io/) (Microsoft Research)
- [Leonardo de Moura](https://leodemoura.github.io/) (Microsoft Research)
- [Kevin Buzzard](http://wwwf.imperial.ac.uk/~buzzard/) (Imperial College London)
- [Reid Barton](https://en.wikipedia.org/wiki/Reid_W._Barton) (University of Pittsburgh)
- [Percy Liang](https://cs.stanford.edu/~pliang/) (Stanford University)
- [Sarah Loos](https://sarahmloos.wordpress.com/) (Google AI)
