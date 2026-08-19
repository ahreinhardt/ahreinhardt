## Alex Reinhardt

Physics teacher who ships production software. MS Software Engineering, RIT.

I build and operate **[PhabPhysics](https://github.com/ahreinhardt/phabphysics)** — an
AP Physics learning platform running in real classrooms at
[phabphysics.com](https://phabphysics.com). Three courses — AP Physics 1, 2 and C —
from one codebase: ~135k lines of TypeScript and JS on Firebase, 3,786 problem
generators, and 24 blocking check groups. Design, implementation, physics content,
and operations are all mine.

**What I'm good at**

- **Correctness under generated content.** Problems are randomized per student and
  authored with LLM assistance, so nothing is hand-checkable. I build the
  deterministic gates that make that safe — property harnesses over generators,
  physics invariant checks, snapshot baselines, browser render sweeps.
- **Shipping into live systems.** The practice core grades real students, so it
  doesn't get refactored mid-semester. Features ship as wrapper modules that load
  after it — two additional courses landed with a single reviewed line changed in
  the 2,100-line scoring core.
- **Interactive simulation.** 13 physics engines in 2D canvas and Three.js, with
  live telemetry and conservation-law test suites.

**Currently** — finishing AP Physics C Electricity & Magnetism.

📄 **[Read the engineering case study →](https://github.com/ahreinhardt/phabphysics)**

<sub>ahreinhardt@gmail.com</sub>
