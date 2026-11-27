# Evidence and claim boundaries

Status: **Pre-release research note / not independently reproduced**

This note identifies what supports the principal claims in the HAIP research
preview. It does not publish HAIP source code, private operational records, raw
conversation history, credentials, device details, or deployment instructions.

## Claim map

| Claim type | Public support | Boundary |
| --- | --- | --- |
| HAIP's architecture and six connected layers | The manuscript and two reviewed diagrams | A descriptive account, not an independently certified implementation |
| Bounded operational cases | Sanitized summaries of retained private project records | The underlying records remain private and have not been externally reproduced |
| Whole-system comprehension observation | The qualitative case record below | One post hoc case, not a benchmark or model ranking |
| Relationship to other systems | The public sources listed in the manuscript | Establishes relevant precedent, not an exhaustive prior-art review |
| Research contribution | The documented integration and claim discipline | No claim of architectural priority, exclusive novelty, or general superiority |
| General safety or effectiveness | None claimed | No production-security, population-level, or universal-performance conclusion |

## Qualitative whole-system comprehension case

### Context

During preparation of this publication, a GPT-5.6 Sol conversation running at
medium reasoning effort had access to the relevant project descriptions. The
task was to identify and explain the publication subject of HAIP as a complete
system.

### Observed behavior

The drafting sequence initially emphasized the familiarity or novelty of
individual mechanisms. It also presented an earlier draft as a refocused
manuscript without fully changing the object of the paper. The owner corrected
the framing by asking what HAIP does as a whole and then stated that the failure
to preserve that whole was itself part of the research question.

After those corrections, the manuscript represented HAIP as a connected
evidence system rather than a feature collection. The relevant distinction was
not whether the conversation could name authorization, retrieval, resource
qualification, isolated verification, retained failure, and recovery. It could.
The observed problem was failure to preserve the invalidation and dependency
rules that determine how evidence from those layers may be combined.

### Interpretation boundary

This is a sanitized qualitative case record. The evaluation criteria were
formalized after the observed interaction, so the case is post hoc. It does not
establish a failure rate, a causal explanation, a comparison with other models,
or a conclusion about other prompts, contexts, reasoning settings, or versions.
It supports only the bounded observation that component recall and fluent
summary did not, in this interaction, guarantee preservation of HAIP's
whole-system relationships.

### Criteria extracted for future evaluation

A future predeclared evaluation should test whether a response preserves all of
the following relationships:

- evidence cannot create authority;
- approval, admission, execution, effect, and recovery are distinct states;
- a favorable later-layer result cannot repair an invalid earlier-layer
  condition;
- resource and knowledge validity are part of the action's evidence contract;
- failure, uncertainty, and `NOT_RUN` work remain part of the retained
  disposition; and
- recovery reconstructs state without silently granting replay authority.

Comparative or quantitative claims would require a frozen prompt and context,
declared model and configuration identities, a scoring rubric fixed before the
runs, retained complete outputs, and an evaluation procedure that distinguishes
relationship preservation from component mention.

## Reproducibility boundary

This preview favors claim control over public reproduction. A later research
package may add synthetic fixtures, expected outcomes, and a predeclared
whole-system comprehension protocol without distributing HAIP itself. Until
then, the public evidence supports a bounded architectural and qualitative case
study only.
