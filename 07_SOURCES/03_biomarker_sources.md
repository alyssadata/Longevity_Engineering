# 03_biomarker_sources

## Biomarker Sources

This file defines how sources are used to support the biomarker section of the
repository.

Its purpose is not to collect all aging biomarker literature.

Its purpose is to make clear:

- what kinds of sources support biomarker classes
- what kinds of sources support validation claims
- what kinds of sources support intervention-tracking claims
- what kinds of sources are too weak for individual-level interpretation
- how biomarker source quality affects protocol weight

This file exists because biomarker sources do not all do the same kind of
work.

A source that helps define a biomarker class is not the same as a source that
shows it is useful for intervention tracking.
A source that shows cohort-level prediction is not the same as a source that
justifies individual-level protocol influence.

This section needs that distinction.

## Core Position

Biomarker sources matter here not only because they provide data, but because
they determine what kind of claim the repository can honestly make.

A biomarker source may support:

- class definition
- analytical validity
- outcome association
- intervention responsiveness
- individual-level interpretability
- translational relevance
- limit-setting and caution

Those are different evidentiary jobs.

This repository therefore does not ask only:
Is there a source?

It asks:
What is this source actually strong enough to support?

## Why This File Matters

The biomarker section already established several important boundaries:

- the measurement problem is structural
- biomarker movement is not the same as organismal improvement
- no biomarker class is currently strong enough to support confident
  individual-level decisions on its own
- function takes precedence when biomarkers conflict with it

Those are current repository positions. :contentReference[oaicite:1]{index=1}

That means biomarker sources must now be handled with more precision.

The real source question is no longer:
Can this biomarker be cited?

It is:
What kind of authority should its source actually carry?

## What Counts As a Biomarker Source

A biomarker source in this repository is a source that helps answer one of the
following questions:

- What is this biomarker class measuring?
- How well is it validated?
- Is it strong at the cohort level, the individual level, or neither?
- Does it track age, burden, risk, intervention response, or some mixture?
- Does it improve protocol clarity, or only make the biomarker sound more
  sophisticated?
- Where does this biomarker class fail?

A source is not a biomarker source merely because it mentions aging markers.

It has to clarify what the biomarker can and cannot honestly do.

## Main Biomarker Source Types

### 1. Biomarker-class reviews

These sources help define a biomarker class and map its strengths, limits, and
common failure modes.

Examples include reviews on:

- epigenetic clocks
- telomere measures
- inflammatory and immune markers
- mitochondrial and metabolic measures
- proteomic and multi-omic clocks
- functional and physiological biomarkers
- composite and system-level models

These reviews are often the strongest sources for clarifying what kind of
biomarker category the repository is dealing with.

### 2. Validation and consortium sources

These are among the most important sources in the entire biomarker section.

They help answer questions such as:

- how biomarkers should be validated
- what counts as analytical versus clinical validity
- what standards matter for translation
- what the field still lacks for stronger individual-level or protocol use

These sources are especially important because they help support the
repository’s caution structure rather than only its measurement structure.

### 3. Primary cohort and outcome studies

These sources matter when the question is whether a biomarker predicts
something meaningful in humans.

They are especially useful for claims about:

- mortality
- morbidity
- frailty
- healthy aging
- multimorbidity
- disease risk
- longitudinal outcome association

These sources can be strong for showing association.
They are not automatically strong for intervention tracking.

### 4. Intervention-response studies

These sources are crucial when the repository is asking whether a biomarker is
actually useful for tracking change under intervention.

This is a different evidentiary job than age correlation or risk prediction.

These sources matter especially for protocol questions, because the repository
needs to know which biomarkers help assess movement, not only baseline state.

### 5. Analytical and methodological sources

These sources matter when the issue is not the biomarker concept, but the
quality of the measurement itself.

Examples include sources clarifying:

- assay reproducibility
- tissue specificity
- sample handling issues
- batch effects
- preprocessing sensitivity
- timing mismatch
- group-level versus individual-level use limits

These are often some of the most important sources when the repository is
setting boundaries rather than making optimistic claims.

## What Biomarker Sources Are Good For

In this repository, biomarker sources are especially useful for:

### 1. Defining the biomarker’s job

Is the biomarker best understood as:

- descriptive
- predictive
- mechanistic
- burden-indicating
- response-tracking
- translationally useful
- still too weak for protocol influence

This is one of the most important questions a biomarker source can answer.

### 2. Setting evidentiary scope

A source can help show whether a biomarker is useful for:

- cohorts
- populations
- disease contexts
- human outcome prediction
- intervention tracking
- one-person interpretation

The repository should not silently move a biomarker beyond the scope its source
supports.

### 3. Clarifying failure modes

Biomarker sources are often most useful when they show where a biomarker class
fails, not only where it works.

This matters because the repository already treats measurement and
interpretation failure as central issues rather than side notes.

### 4. Supporting protocol restraint

A biomarker source can strengthen the repo most when it helps answer:

Why should this biomarker **not** yet be allowed too much protocol weight?

That is one of the most important uses of source logic in this section.

## What Biomarker Sources Are Not Good For

Biomarker sources are weaker when they are used to do jobs they do not support.

For example, a biomarker source is not automatically the right source for:

- proving an intervention improves function
- justifying promotion of an exploratory intervention
- overriding organismal outcomes
- supporting a stronger protocol role than the biomarker actually deserves
- smoothing over biomarker-function conflict

These moves are exactly what this repository is trying to prevent.

## How the Biomarker Section Uses Sources

The biomarker section should rely on sources differently at different levels.

### At the section README level

The biomarker README should rely most heavily on:

- biomarker-class reviews
- validation and consortium sources
- structural reviews clarifying major limitations across biomarker types

This is where the repository sets the measurement problem clearly.

### At the individual-file level

Each biomarker file should rely most heavily on:

- class-specific reviews
- primary cohort or validation studies
- primary intervention-response studies where relevant
- methodological sources when interpretation limits are load-bearing

This is where narrower claims need stronger support.

### At the protocol-interface level

Files touching protocol use should rely most heavily on:

- validation standards
- intervention-response studies
- sources supporting or limiting individual-level interpretation
- sources clarifying biomarker-function alignment or mismatch

This is where the source burden becomes heaviest, because the repo is closest
to real decision logic there.

## Biomarker Source Failure Modes

### Failure Mode 1 | Association inflation

A source showing age association or outcome association is treated as if it
already supports intervention tracking or individual protocol use.

### Failure Mode 2 | Cohort-to-individual overreach

A source is strong at the population level and quietly overread at the
individual level.

### Failure Mode 3 | Validation smoothing

A biomarker sounds mature because it is widely discussed, while validation
limitations are left underweighted.

### Failure Mode 4 | Clock prestige borrowing

A technically sophisticated biomarker model is treated as if that sophistication
itself justifies protocol relevance.

### Failure Mode 5 | Response-description collapse

Sources supporting descriptive or predictive use are treated as if they also
support response tracking.

## What This File Should Eventually Contain

As the repository grows, this file should likely hold or point toward the
sources doing the most structural work for the biomarker section.

Likely source groups include:

- biomarker-class defining reviews
- validation and consortium guidance
- primary studies on outcome prediction
- primary studies on intervention responsiveness
- methodological sources on assay and interpretation limits
- sources showing where biomarker classes conflict with function or with each
  other

The point is not to collect all biomarker papers.

The point is to identify which sources actually support the biomarker logic
used in this repo.

## Biomarker Source Questions the Repository Should Ask

Before giving a biomarker source real weight, the repository should ask:

- What biomarker job is this source actually supporting?
- Is this source about class definition, validation, outcome prediction, or
  intervention response?
- Is it being used for a claim wider than it actually supports?
- Does it help clarify individual-level strength, or only cohort-level value?
- Does it support protocol relevance, or only biological or predictive
  interest?
- Is a more specific methodological or primary study needed for this point?

If those questions cannot be answered well, the source may be doing less real
work than it appears to do.

## Relationship to the Rest of the Source Section

This file is the biomarker-specific companion to the broader review logic in
`01_foundational_reviews.md` and the biological-map logic in
`02_hallmark_sources.md`.

It should relate to the rest of `07_SOURCES` like this:

- `01_foundational_reviews.md` = how review literature supports the repo’s
  overall structure
- `02_hallmark_sources.md` = how sources support the biological map
- `03_biomarker_sources.md` = how sources support biomarker classes,
  validation, and protocol limits
- `04_intervention_sources.md` = how sources support intervention ranking and
  maturity
- `05_risk_and_translation_sources.md` = how sources support nonpromotion,
  restraint, and failure logic
- `06_protocol_and_guideline_sources.md` = how sources support structured,
  human-facing protocol boundaries

This file stays at the measurement-logic level.

## Relationship to the Rest of the Repository

This file is directly constrained by:

**02_BIOMARKERS**  
because that section is the measurement architecture this file exists to
support

**08_NOTES | Emerging Patterns**  
especially Pattern 4 and Pattern 6, because those patterns already established
that the measurement problem is structural and that function remains the
arbitration layer when biomarker conflict appears :contentReference[oaicite:2]{index=2}

**05_PROTOCOL_DESIGN/05_biomarker_use_in_protocols**  
because biomarker source quality directly affects how much protocol weight a
biomarker can honestly carry

**04_RISKS_AND_FAILURE_MODES/02_measurement_and_interpretation_failures.md**  
because many biomarker-source failures show up later as interpretation failures
in the repo

## Current Assessment

Current repository assessment:

- importance to measurement honesty: foundational
- importance to protocol restraint: high
- importance to biomarker-class clarity: high
- relevance to the whole source section: high

## Open Questions

- Which biomarker classes in the repository currently have the strongest
  source base for intervention tracking rather than just outcome prediction?
- Which biomarker domains are still too dependent on review language and need
  stronger primary response-tracking support?
- Where is the repository most vulnerable to cohort-to-individual overreach?
- Which biomarker classes need the strongest methodological sourcing to keep
  them from being overread?

## Status

Foundational source-logic file.

This file should be treated as the place where the repository becomes explicit
about how biomarker sources are being weighted, limited, and translated into
actual evidentiary role, so that measurement sophistication does not quietly
become more authority than it has earned.

Authored and maintained by Alyssa Solen | Solen Systems  
CC BY 4.0 | Reuse with attribution
