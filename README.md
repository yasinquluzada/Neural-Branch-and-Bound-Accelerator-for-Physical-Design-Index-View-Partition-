This report presents an exact accelerator for database physical design, jointly selecting
indexes, materialised views, and partition schemes under explicit budget and compat-
ibility constraints. The problem is specified by (i) a finite construction of the candidate
design space, (ii) a formal definition of the plan universe with explicit feasibility con-
ditions, and (iii) a total and deterministic cost functional on the constructed universe.
On this basis, we define a mixed-integer optimization formulation provably equivalent
to the semantic design objective. The solver combines branch-and-bound with column
generation and cutting-plane mechanisms; every operation that can affect bounds or
pruning is subject to finite arithmetic certificate verification. Learning is introduced
only as an advisory layer (proposals for branching, cuts, pricing, and primal construc-
tion) whose effects are mediated by deterministic acceptance gates that preserve exact-
ness. Finally, an empirical closure pack defines the benchmark charter, fairness con-
tract, metric ledger, ablation grid, robustness suite, and repeatability protocol, culmi-
nating in a results ledger with mandatory tables and figures.
