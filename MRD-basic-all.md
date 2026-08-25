# Basic MRDs — the Zistgah / AyeAI estate

**Twenty-six components. One skeleton each.** These are the *basic* MRDs: the spine from which a
full MRD and its paired Commercial & IPR dossier get built. Everything here was retrieved from the
durable record or the live repositories. Nothing was inferred to make a section look complete.

**How to read a `[UNRESOLVED]`.** It means the record does not contain it, and I have not supplied
a plausible substitute. Where a component is mostly `[UNRESOLVED]`, that is the finding — it names
the retrieval session that is owed before anything can be built.

**Classification: Restricted.** Section 6 of every entry lists live disclosures. Read the IPR
warning at the end before publishing any of this.

---

## The taxonomy this obeys

Five categories, and *product* is an operational and economic word, not a claim that a thing is
software:

| | |
|---|---|
| **Laboratory** | Mez — where independently existing systems are composed and exercised |
| **Sovereign systems** | GENIE · Kitab · Misty DoI · Tok DOI · spiguard · ILM · FAKIR · CHAKRA · the Dome · TransEg · AAB — each owns its ontology, runtime, artifacts, evolution and users |
| **Independent cyclers** | Matba · Khwab · Awaz · Tilasm · Pench · Yadein — one shared engine, six emphatically separate workflows |
| **Protocols, methods, gates** | Candor · MASI · VGC · AAB-as-method · the IPR process |
| **Services and physical capability** | Teaching · litigation simulation · the physical lab · architectural guidance · research supervision |

**Interoperability does not eliminate independence.** Matba interoperating with Mez does not make
Matba part of Mez. GENIE is not Mez. ILM is not Mez.

---

---

# Mez Cognitive Workbench · میز

**Laboratory** · repo `zistgah/mez` · DOI none · **live-unsealed**

> A desk you own: a laboratory in which independently existing systems are composed, exercised, inspected and synthesised.

## 1. The problem, and who has it

Work spanning many independent systems has no place to stand. Capability exists in the estate and cannot be reached from where the person is sitting.

Users: the author himself · engineers composing across systems · researchers running a cycle · institutions taking inventory

## 2. Scope

**In**

- three rungs: console, 2D studio, dome
- the six output cyclers as reachable systems
- the prompt operating system
- capability matrix
- ACM/NISO/FAIR4RS badge scoring
- WBS, bearings, mail, meetings, classes
- local-AI seam

**Out**

- reimplementing any component it reaches
- cloud storage of the person's data
- certifying anything (samd is framework only)

**Refuses, and the refusal is the specification**

- a stub that looks alive (M2)
- overwriting a cell the person set by hand (owned.json)
- binding to anything but loopback (M6)
- awarding Results Reproduced to itself

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **rung** | a projection of the laboratory; changes what is SHOWN, never what is COMPUTED | not a permission level, not a feature tier |
| **wiring gap** | a capability that exists and cannot be reached from the desk | not a missing build |
| **sovereign system** | owns its ontology, runtime, artifacts, evolution and users | not a module, not a plugin |

## 4. Requirements

**MEZ-R-01** local-first, Python standard library only, runs with the network unplugged — *M1*

**MEZ-R-02** never pretend: anything absent exits 3 and says where it looked — *M2*

**MEZ-R-03** the person's data is plain CSV/JSON; the export format IS the storage format — *M3*

**MEZ-R-04** an owned cell is never overwritten by an import; --force required — *the destructive-import bug*

**MEZ-R-05** role changes the view, never the computation — *M4/C33*

**MEZ-R-06** components are DATA; delete them all and the desk still runs — *M5*

**MEZ-R-07** loopback only; exposing to a network is a separate deliberate act — *M6*


## 5. Invariants, failures, evidence

**Must never stop being true**

- no component id appears in the spine's code
- a badge is never self-awarded where it requires an independent party
- the manifest never contains its own hash

**How it has actually gone wrong**

- 21 basenames duplicated three deep and 2.5MB of tarballs committed inside the repo (23 Aug)
- the seal broken by a script that changed tracked content and did not reseal
- the studio served on loopback only while docs/ stayed empty

**What must exist before it may be called done**

- every suite green from a clean clone
- manifest verifies over all tracked files
- Pages actually enabled

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- M1-M6 repo overlay
- C33 three rungs
- C37 wired-but-unproven is its own tier
- C38 the estate mirror is read-only

**Composes with**

- reaches 13 sovereign systems by interface, never containment
- probes 127.0.0.1:7373 from the published page
- CORS on reads only

**`[UNRESOLVED]`**

- which of index.html / desk.html / about.html / index2.html is the front door
- the immersive rung has never run against a live dome

---

# The Six Output Cyclers · مطبع خواب آواز طلسم پیچ یادیں

**Sovereign systems** · repo `zistgah/{matba,khwab,awaz,tilasm,pench,yadein}` · DOI 21948734 · 22005507 · 22005575 · 22010869 · 22010962 · 22011073 · **live-minted**

> Six independent creativity cyclers classified by WHAT COMES OUT: print, visual, audio, immersive, embodied, record.

## 1. The problem, and who has it

Turning raw material or a bare idea into a published, sealed, citable artifact requires a different workflow per output kind, and no shared tool respects that difference.

Users: authors and researchers · film and audio makers · XR builders · roboticists · anyone keeping a life record

## 2. Scope

**In**

- one shared ENGINE: clipboard loop, answer routing, artefact inbox, AI source table
- 62 stages across six workflows, each with its own implementation prompt
- kitab-shaped output that reads in the same reader as every other book
- seed / clear / attest / mint as four distinct implements

**Out**

- a shared WORKFLOW — that was the error of 19 Aug
- being an AI provider
- assuming any commercial service exists

**Refuses, and the refusal is the specification**

- tilasm: a piece where no station leads anywhere; a station with no comfort note
- pench: a manoeuvre with no operating envelope; an invented limit in place of an unknown one; a sim2real claim naming no hardware run
- yadein: publishing any entry not individually marked; sharpening a vague date; adding a surname the source never gave
- all: claiming a file in a folder was produced by an AI

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **cycler** | classified by OUTPUT, not by input | matba is print and not 'books'; khwab spans a single image to a long-running series |
| **engine vs workflow** | the engine is common; the workflow is emphatically not | shared code is an implementation optimisation, never an ontological claim |
| **gate** | a boundary only a human may cross | not a confirmation dialogue |

## 4. Requirements

**CYCLERS-R-01** each cycler declares its own purpose, contract, context, state, invariants, failure modes, evidence requirements, workflow and artifact model — *19 Aug ruling*

**CYCLERS-R-02** the AI source table ships WITH links, in a config file, alphabetical so the order is not a ranking — *21 Aug correction to an earlier empty table*

**CYCLERS-R-03** at least one keyless local path, and answering by hand always allowed — *C32*

**CYCLERS-R-04** a leak check refuses any page borrowing a sibling's vocabulary — *the defect that reached six live DOIs*

**CYCLERS-R-05** chapters are cues into ONE media file, never cut copies — *one file, one hash, one deposit*


## 5. Invariants, failures, evidence

**Must never stop being true**

- no two cyclers share a purpose, contract, artifact or step sequence
- the artefact inbox says what is newly VISIBLE, never who made it
- the mint implement records intent and mints nothing

**How it has actually gone wrong**

- one workflow parameterised by a noun and shipped six times — 'cues into one entry' on a diary
- a description pipeline where ab-initio construction was needed
- the AI table shipped empty, making the tool useless out of the box

**What must exist before it may be called done**

- 47-65 assertions per cycler, green from a clean extraction
- the leak check proven to catch what actually shipped
- no service name in the code, only in the config

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- per-repo CONTRACT overlay clause 8: the model's own refusals are contract, not style
- kitab-shaped deployment
- nothing pushes or mints without a typed gate

**Composes with**

- emit into kitab
- reached from mez by interface
- each runs standalone with no server for the composing half

**`[UNRESOLVED]`**

- the pench safety envelope has never been exercised against real hardware
- yadein's path to TransEg is declared, not built

---

# GENIE

**Sovereign system** · repo `zistgah/genie` · DOI genie corpus minted; prompt-OS plate pending · **live-minted**

> Generalized Emotive-Narrative Interaction Engine, and the Prompt Operating System: an eleven-node cycle in which every prompt must CREATE, VERIFY, EXECUTE, MEASURE, FALSIFY or INTEGRATE an artifact.

## 1. The problem, and who has it

AI-assisted research drifts, hallucinates and produces prose about work instead of the work. A hypothesis silently becomes a derived fact.

Users: researchers running a formal programme · anyone building an artifact from nothing

## 2. Scope

**In**

- DISCOVER → SPECIFY → FORMALIZE → IMPLEMENT → VERIFY → SIMULATE → EXPERIMENT → FALSIFY → DOCUMENT → AUDIT → REFINE
- Layer 0 constitution plus layers 1-10
- nine epistemic tags
- three entry modes with ab-initio first
- the lab BOM, software stack and 18 work chunks
- aesthetic analysis engine

**Out**

- being a chat interface
- promoting a conjecture to canon

**Refuses, and the refusal is the specification**

- a step whose product begins describe/explain/summarise/discuss
- a PASS with no evidence
- saying the research is complete
- a measurement with no units or uncertainty

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **Act** | executable intent; a walk through transition structure | NOT the ACT of ACT-R, NOT a legislative text |
| **Inclination** | a signed directional gradient on transition EDGES, I in [-1,+1] | not a probability; 0 is neutrality, not cessation |
| **Natural Justice** | a gate on the intent-to-execution transition | not external ethical commentary |

## 4. Requirements

**GENIE-R-01** every statement carries an epistemic tag; untagged reads as derived, which would be a lie — *the plate*

**GENIE-R-02** retrieved, inferred, proposed and unresolved are kept apart — *layer 2*

**GENIE-R-03** where unknown, write UNRESOLVED and never supply a plausible value — *layer 4*

**GENIE-R-04** completeness reported per component; the system never says 'complete' — *panel 13*

**GENIE-R-05** a simulation may never pass the experiment gate — *the six-gate pipeline*


## 5. Invariants, failures, evidence

**Must never stop being true**

- each cycle leaves a more complete executable artifact than the last
- a conjecture never becomes a theorem by restatement

**How it has actually gone wrong**

- Claude built description workflows and called them cyclers
- MERGE was conflated with CANON in an early reading

**What must exist before it may be called done**

- 191 assertions on the engine, every guard mutation-tested
- 18 work chunks each with a named module and a stated oracle

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- Oracle / Interpretation (IWBT) / Verification (VGC) kept separate
- dome-derived; Pages/JS; BYOK

**Composes with**

- uses the cycler protocol
- can be used BY the workbench and can use the workbench — bidirectional

**`[UNRESOLVED]`**

- the 8-dimension aesthetic vector P F S E N C I X is UNADOPTED pending his ruling
- two poster titles carry religiously significant words he has ruled must be renamed

---

# Kitab · کتاب

**Sovereign system** · repo `zistgah/kitab` · DOI none · **live**

> The book template every cycler emits into: reader, theme, plumbing, talking figures, exercises.

## 1. The problem, and who has it

A published research artifact should read the same whatever produced it, and should carry its own provenance and assessment.

Users: readers of any estate book · authors forking a book · teachers setting work

## 2. Scope

**In**

- parts, chapters, figures that declare explanation/tts/seed
- exercises: MCQ, cloze, long-answer handoff, timed, proctored
- certificates backed by OTS
- config-driven embeds
- PWA

**Out**

- hosting
- accounts
- tracking a reader

**Refuses, and the refusal is the specification**

- auto-marking a long answer
- naming an AI vendor in shipped content
- hardcoding a social handle, callback or provider

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **talking artifact** | a figure that can explain itself, speak, and hand off to the reader's own AI | not a chatbot |

## 4. Requirements

**KITAB-R-01** never name an AI vendor; which AI is the reader's choice — *standing rule*

**KITAB-R-02** nothing hardcoded: handles, seeding URLs, sim URLs, review repos, callbacks, providers — *a shipped default is fine; a shipped constant is not*

**KITAB-R-03** entry paths: fork the book being read, or a blank slate — *content paths a/b/c*

**KITAB-R-04** completion recorded by GitHub issue OR web callback, configurable, or nowhere


## 5. Invariants, failures, evidence

**Must never stop being true**

- assets/figures is DATA; template placeholders are swept before real ones land
- a certificate is evidence of a run, not of identity

**How it has actually gone wrong**

- five Lorem-Ipsum placeholder SVGs reached a live DOI (21917807)

**What must exist before it may be called done**

- the reader renders every block type from a clean clone

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- licence: code GPL-3.0-or-later where dome-derived; content per deposit

**Composes with**

- every cycler emits into it
- reads in the same reader across the estate

**`[UNRESOLVED]`**

- exercises and certificates are specified and partially built; the proctored path is not exercised

---

# Misty DoI

**Sovereign system** · repo `project-ilm/misty-doi` · DOI 10.5281/zenodo.20719388 · **live-pypi-1.0.1**

> The publication layer: mint, version, walk, harvest — from concept to persistent scholarly artifact.

## 1. The problem, and who has it

Getting a researcher's own work to a persistent, citable, machine-readable record is donkey work, and the mistakes are irreversible.

Users: the author · third-party authors minting their OWN work under their OWN token · institutions auditing a deposit estate

## 2. Scope

**In**

- init validate transform package ots publish newversion discard walk harvest latest masi clearance
- MASI: seven tracks, ordered states, evidence requirements, five cross-track gates
- rules and known_facts are DATA

**Out**

- owning disclosure rules — extracted to spiguard on the CBE ruling
- minting third-party work

**Refuses, and the refusal is the specification**

- minting while a linked patent matter is pre-filing unless defensive publication is asserted (G3)
- accepted without a recorded review round (G4)
- an approval applied backwards (G1)
- a prereg stamped after collection (G2)

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **concept DOI vs version DOI** | publish makes a NEW record; newversion mints beneath an existing concept | using the wrong one splits a lineage, unmergeable without the registrar |
| **clearance** | a signed receipt that covers THIS exact artifact | misty verifies it and knows nothing about what was checked |

## 4. Requirements

**MISTY-R-01** tokens by PATH only, never inlined, never in a flag, never committed

**MISTY-R-02** mint is TEST-gated, not human-donkey-work gated — *his correction*

**MISTY-R-03** enable OTHERS to mint their own work — kits remove every step but the one only they can take

**MISTY-R-04** the interface is READ at run time, never recalled


## 5. Invariants, failures, evidence

**Must never stop being true**

- a walk reports and never edits
- a date is never inferred or proposed
- the same title under two concept DOIs is a reported ERROR

**How it has actually gone wrong**

- AAB under two concept DOIs — split lineage, live and unmergeable
- ~140 records with empty affiliation, no ORCID, no version
- ~180 DOIs recorded in no repo
- harvest downloads all 404'd on draft file links

**What must exist before it may be called done**

- 28-test suite plus e2e against a local Zenodo stand-in; live Zenodo deliberately never contacted because minting is irreversible

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- CBE: disclosure rules and minting mechanics change for different reasons, so they are different components

**Composes with**

- spiguard emits the clearance it verifies
- Candor supplies the attested intent
- Tok DOI is the atomic layer beneath it

**`[UNRESOLVED]`**

- v1.1.3 built and never landed; live repo still 1.1.2 with guard.py present
- PyPI still at 1.0.1
- sandbox 403 — sandbox.zenodo.org needs its own token

---

# Tok DOI

**Sovereign system** · repo `project-ilm/tok-doi` · DOI 10.5281/zenodo.21402745 · **live-minted**

> Register cryptographic proof, not publications: artifact to SHA-256 to OpenTimestamps to AyeSHA to a public registry.

## 1. The problem, and who has it

Proof of existence at arbitrary granularity has no lightweight, keyless, backend-free path.

Users: anyone needing a dated proof · PIE signatories · MASI ledger holders

## 2. Scope

**In**

- browser-first registrar, verifier, PIE signing page
- registries as DATA
- collections: sub-DOI to curated set to Misty to Zenodo
- T-MASI: the same seven tracks and five gates in the browser

**Out**

- scholarly publication
- storing raw .ots

**Refuses, and the refusal is the specification**

- storing a raw .ots — only its AyeSHA encoding
- requiring a backend or an account

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **atomic registration** | proof at arbitrary granularity | not a publication, not a verdict |

## 4. Requirements

**TOKDOI-R-01** browser-first, no backend; GitHub Pages plus public OTS is sufficient

**TOKDOI-R-02** keyless submission by compose-URL — *registries retrieved, never generated*


## 5. Invariants, failures, evidence

**Must never stop being true**

- gate verdicts match the Python implementation — one definition, two runtimes, and a check that says so

**How it has actually gone wrong**

- seeded pre-rename with old naming; its own DOI was absent from the repo until corrected

**What must exist before it may be called done**

- 10 parity checks proving browser gates match misty/masi.py

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- five T-MASI clauses in CONTRACT.md

**Composes with**

- feeds Misty for the publication layer
- carries the PIE signatory campaign

**`[UNRESOLVED]`**

- AyeSHA canonical encoding NOT defined — a reversible placeholder codec ships behind a stable interface

---

# spiguard

**Sovereign system** · repo `NOT CREATED` · DOI none · **built-never-landed**

> The disclosure gate: judges secrets, third-party PII, IPR leakage, plagiarism, patent language and clean-room, and emits a clearance. Fails closed.

## 1. The problem, and who has it

Disclosure rules change with law and compliance; minting mechanics change with the platform. Conflating them makes both unmaintainable.

Users: anyone about to publish anything from the estate

## 2. Scope

**In**

- scan (full gate, emits clearance) · privacy (reduced: secrets+PII+IPR, the only estate-wide mode) · verify

**Out**

- minting
- knowing anything about DOIs

**Refuses, and the refusal is the specification**

- passing on ERROR without an explicit --allow-findings and a reason
- asserting integrity without author_verified:true

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **clearance** | HMAC over the subject digest = metadata plus every file hash | the thin CBE interface where spiguard judges and misty mints |

## 4. Requirements

**SPIGUARD-R-01** FAILS CLOSED — *author_domains configurable so the author's own contact is not flagged*


## 5. Invariants, failures, evidence

**Must never stop being true**

- it never mints; misty never judges

**How it has actually gone wrong**

- the entire component exists as a tarball and has never been created as a repo

**What must exist before it may be called done**

- 14 tests: 9 scan, 5 clearance

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- his CBE ruling: 'Misty is not the place for the IPR filter'

**Composes with**

- emits the clearance misty/clearance.py verifies

**`[UNRESOLVED]`**

- no repo under either org; this is the highest-value unlanded component in the estate

---

# Candor

**Protocol** · repo `project-ilm/tok-doi (attest/)` · DOI none · **live-mint-ready**

> Attested authorisation: in-toto Statement v1 plus OTS, so an irreversible act is one human command carrying its reason.

## 1. The problem, and who has it

Irreversible operations either drown the operator in prompts or happen without a recorded justification.

Users: anyone pushing or minting in the estate

## 2. Scope

**In**

- receipt schema, append-only receipts, auto-discovery of files, integrity gate against doi/DEPOSIT.sha256

**Out**

- deciding anything

**Refuses, and the refusal is the specification**

- a receipt whose reason was invented rather than recorded

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **intent** | a signed statement that a named person means to act, and why | not the act |

## 4. Requirements

**CANDOR-R-01** one human command plus a git-style short digest plus a reason — 'no donkey work'

**CANDOR-R-02** raw .ots never stored


## 5. Invariants, failures, evidence

**Must never stop being true**

- the typed gate IS the Candor intent and must land as a receipt

**How it has actually gone wrong**

- a push to zistgah/fakir with no receipt at all — the chain stops dead at it
- and again across nine repos on 23 Aug

**What must exist before it may be called done**

- receipt chains present and OTS-paired in the repos that were done correctly

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- predicateType https://project-ilm.org/attestations/candor/v1

**Composes with**

- third of four in seal → clear → attest → mint

**`[UNRESOLVED]`**

- may get its own DOI; metadata is prepared

---

# Project ILM

**Sovereign system** · repo `ilm.codes` · DOI none · **live**

> Integrative Linguistic Multiscript: three strictly separate axes — Script, Language, Standard — across 600+ scripts and 7,000+ languages.

## 1. The problem, and who has it

Script, language and standard are routinely conflated, which makes non-English computing a translation problem instead of a representation problem.

Users: speakers and writers of under-served languages · standards bodies · anyone building multiscript software

## 2. Scope

**In**

- the three-axis registry
- LOS specification corpus L3.2 through L7.2
- Single-Pane-of-Glass artifact browser
- registry served with ACAO:* so others can fetch it

**Out**

- being a translation system — a FORBIDDEN substitution

**Refuses, and the refusal is the specification**

- collapsing the three axes

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **Script / Language / Standard** | three strictly separate axes | ILM must NOT become 'a multilingual translation system' |

## 4. Requirements

**ILM-R-01** 600-700+ scripts, 7,000+ languages in scope

**ILM-R-02** successor to HPS, which supplies the transducer lineage


## 5. Invariants, failures, evidence

**Must never stop being true**

- the axes never merge

**How it has actually gone wrong**

- four real defects filed as issues #8-#11 after the context rebuild

**What must exist before it may be called done**

- registry fetched live by FAKIR at runtime

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- [UNRESOLVED] no per-repo contract retrieved

**Composes with**

- supplies the language axis of FAKIR's three-axis seeding
- successor to Hindawi/HPS

**`[UNRESOLVED]`**

- governance across 7,600+ languages and 600+ scripts — repo structure NOT designed
- how a language community contributes without a fork

---

# FAKIR / UKOP

**Sovereign system** · repo `zistgah/fakir` · DOI 10.5281/zenodo.21436550 · posters 21436552 · **live-minted-v2**

> Foundational Architecture for Knowledge, Intelligence and Reasoning — the concrete kernel of UKOP, spanning every ISIC/ISCO/ISCED domain across AGI layers L0-L9.

## 1. The problem, and who has it

There is no domain-neutral reference architecture for human knowledge that is exhaustive across the UN/ILO/UNESCO classifications and addressable at every AGI layer.

Users: researchers seeding work in any domain · institutions mapping capability · the AGI programme itself

## 2. Scope

**In**

- 1,505-node lattice gated against UNSD/ILO/UIS
- the dome explorer as the estate's shared dome
- three-axis seeding: AGI layer x domain x language
- RFC suite Volumes I-VII
- conformance levels 0-5

**Out**

- letting an external standard enter the core — the Interoperability Layer exists for that

**Refuses, and the refusal is the specification**

- a lattice that is not exhaustive
- branching code on world identity

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **Artifact, Identity, Version, Manifestation, Representation, Policy, Provenance, Trust Domain, Semantic Graph** | UKOP canonical primitives |  |
| **one-way publication boundary** | publication is a boundary crossing, not a state change |  |

## 4. Requirements

**FAKIR-R-01** explorer must represent ALL ISIC sections, ISCO major groups, ISCED broad fields, exhaustively

**FAKIR-R-02** reuse the actual dome; never reinvent it — *one library, one world config per zistgah, never a fork*

**FAKIR-R-03** clicking a point seeds a task using AAB methodology

**FAKIR-R-04** a concept paper referencing PIE and arguing its necessity — *not written*


## 5. Invariants, failures, evidence

**Must never stop being true**

- any code branching on world identity is a redundancy defect

**How it has actually gone wrong**

- a push with no Candor receipt and a broken manifest — the violation of record
- a latent TypeError on any transit ending in dome or space

**What must exist before it may be called done**

- 26-assertion behavioural oracle, 11/11 mutation suite; mutation testing caught 4 vacuous tests

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- governance #5 redundancy register

**Composes with**

- mounts the dome; consumes the ILM registry; seeds through AAB

**`[UNRESOLVED]`**

- the concept paper is not written
- AGI-layer clickability and the cinematic entrance were specified, partially built

---

# CHAKRA

**Sovereign system** · repo `project-ilm/chakra` · DOI concept 10.5281/zenodo.21253628 · **live-v1.4.1**

> An astronomical observatory computed from first principles: a JS and C99 byte-parity twin across ten calendar reckonings.

## 1. The problem, and who has it

Calendrical and astronomical values are looked up rather than computed, so they cannot be verified, ported or trusted.

Users: practitioners · researchers · anyone needing panchanga or a calendar conversion · every estate component needing time

## 2. Scope

**In**

- ten calendars, panchanga, yogas, dasha, chart, retrogrades, eclipses, telescope
- the plus layer: kundali, mahabharata, panjika, tools, sky
- 6,590 checks

**Out**

- looking anything up

**Refuses, and the refusal is the specification**

- naming a provider or payment vendor in any built artifact
- touching the parity surface — src/chakra-core.js has zero diff

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **byte-parity twin** | the JS and the C99 must agree byte for byte | not 'approximately equal' |

## 4. Requirements

**CHAKRA-R-01** physical-map-only rule enforced

**CHAKRA-R-02** view changes what is SHOWN, never what is computed; the URL carries it — *#74, not built*


## 5. Invariants, failures, evidence

**Must never stop being true**

- the parity surface is never touched by additive work

**How it has actually gone wrong**

- BODIES had no Earth, so Earth-to-Mars launch windows were impossible
- SHODASHAVARGA held 15 divisors under a name meaning sixteen
- the card drew a full disc for a 76% gibbous moon
- six live files carried conflict markers on main

**What must exist before it may be called done**

- 6,590 checks; suites of 94/59/46/34/9/25/15; C twin byte-parity verified

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- Clause 7 self-contradiction found; amendment prepared

**Composes with**

- mez cal calls it headless
- the dome uses chakra-core for the orrery

**`[UNRESOLVED]`**

- #73 panchang parity audit is the biggest gap and is NOT built
- UI is English-only — the biggest barrier to the reach the viral layer was built for

---

# The Dome

**Sovereign system** · repo `zistgah/dome` · DOI minted · **live**

> One shared virtual dome as a config-driven library: the same basic dome everywhere, projects mount their displays inside it.

## 1. The problem, and who has it

Every project reinventing its own 3D environment produces drift and redundancy.

Users: every estate project with something to show in space

## 2. Scope

**In**

- pointcloud, viewer's gallery, video screens as built-in displays
- multi-world transit with vehicle profiles
- flight, oculus escape, CHAKRA time HUD

**Out**

- per-world code branches

**Refuses, and the refusal is the specification**

- a fork per zistgah

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **display** | what a project mounts into the hall | not a page, not a scene |
| **world** | one config file | never a code branch |

## 4. Requirements

**DOME-R-01** each zistgah is dome plus ONE world config, never a fork

**DOME-R-02** one flight seam with profile-swapped physics, not three controllers

**DOME-R-03** the orrery reuses chakra-core's ephemeris


## 5. Invariants, failures, evidence

**Must never stop being true**

- code branching on world identity is a redundancy defect

**How it has actually gone wrong**

- #gl pointer-events:none meant canvas handlers could never fire

**What must exist before it may be called done**

- marker census gated on both lib and page: 17/14/16/9/2/1

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- code GPL-3.0-or-later, docs CC-BY-SA-4.0

**Composes with**

- FAKIR, mez's immersive rung, the VIDYA sims all mount into it

**`[UNRESOLVED]`**

- mez has never actually mounted into it

---

# TransEg

**Sovereign system** · repo `zistgah/transeg` · DOI 10.5281/zenodo.21321558 · **live-built-not-running**

> A local digital-twin and identity-continuity stack: staggered upload of face, voice, documents, knowledge, memory, preferences, reasoning, delegation.

## 1. The problem, and who has it

Identity continuity across substrates has no local-first, consent-staged reference implementation.

Users: the author · anyone building an embodied twin

## 2. Scope

**In**

- eight docker services
- staggered stages where no stage implicitly grants another
- routes: /chat needs memory, /avatar/render needs face, /memory/export|backup|restore|delete

**Out**

- cloud identity
- implicit consent

**Refuses, and the refusal is the specification**

- one stage granting another
- rendering without the face stage enabled

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **staggered upload** | consent is per-stage and explicit | not a profile, not an account |

## 4. Requirements

**TRANSEG-R-01** local gateway; no stage implicitly grants another

**TRANSEG-R-02** the oracle is scripts/avatar_smoke.sh and it writes a real mp4 or fails loudly


## 5. Invariants, failures, evidence

**Must never stop being true**

- a stage boundary is a consent boundary

**How it has actually gone wrong**

- a placeholder DOI tail live and public in README, CITATION and MINT_RUNBOOK
- --inject-doi anchored on the clean prefix so it could never strip the tail it created

**What must exist before it may be called done**

- the #1 postcondition now fails on any residual placeholder — it caught a miss during rehearsal

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- [UNRESOLVED]

**Composes with**

- yadein accumulates toward it
- mez embody is wired but never proven against a live instance (C37)

**`[UNRESOLVED]`**

- every container is EXITED; the avatar path has never run
- transeg-idgov and transeg-research need their own mint

---

# PEDLER / QEDLER

**Research programme** · repo `project-ilm/qedler` · DOI PEDLER 10.5281/zenodo.17497559 · **live-unminted**

> A deterministic, background-independent typed event-hypergraph substrate intended to yield QM, GR, gauge theory and cosmology without fundamental randomness or continuous spacetime.

## 1. The problem, and who has it

Existing foundational programmes assume randomness or a continuum. This one assumes neither and asks what follows.

Users: physicists · the whole estate, which uses its primitives

## 2. Scope

**In**

- 12 axioms at v0.1
- falsifiable predictions: modified dispersion, discrete decoherence deviation, primordial GW cutoff, extra defect families, evolving effective cosmological constant
- the realization lattice: FSM, Turing, Markov, Boltzmann, Hopfield, ANN, gradient descent, RL, attention as projections under restriction

**Out**

- claiming completed proofs

**Refuses, and the refusal is the specification**

- presenting an open problem as a result
- collapsing CEM^b and CEM^s into an unqualified CEM

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **Act** | executable intent, a walk through transition structure | not ACT-R's rule firing, not a statute |
| **Inclination** | signed directional gradient on edges | decay weakens magnitude and preserves sign |
| **Natural Justice** | a gate on intent to execution | internal to the model |

## 4. Requirements

**PEDLER-R-01** the posters declare their own status: a research framework, NOT a completed theory

**PEDLER-R-02** hedging is a CONTRACT clause — neuroscience panels are correlation, not proof

**PEDLER-R-03** mint as a NEW concept DOI, not a newversion of PEDLER


## 5. Invariants, failures, evidence

**Must never stop being true**

- scope estimate: 200-500 definitions, 20-50 axioms, 300-800 lemmas, 100-250 theorems
- many emergence results are open mathematical problems

**How it has actually gone wrong**

- metric reconstruction needs an injective map because isospectral manifolds exist — self-corrected on the poster
- multiple inequivalent hypergraph Laplacians exist and the choice affects the continuum limit

**What must exist before it may be called done**

- adversarially validated across three AI systems on the inclination/fields theory

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- 1996 tic-tac-toe is a WORKING PEDLER: 3^9 states, KB merge by XOR

**Composes with**

- the ontology the whole estate instantiates
- QEDLER is the physics-facing extension

**`[UNRESOLVED]`**

- mathematical rigour is below his own notes
- QEDLER not minted: spiguard absent so clearance failed closed, by design

---

# AAB · آب

**Sovereign system** · repo `zistgah/aab` · DOI TWO concept DOIs — split lineage · **live-defective**

> Paint a system as a typed graph over a closed six-kind vocabulary, oracle-gated: no oracle, no glow.

## 1. The problem, and who has it

System design produces pictures nobody can check.

Users: anyone designing before building

## 2. Scope

**In**

- painted manifest
- VGC quest stages
- oracle-gated verification

**Out**

- generic sketching

**Refuses, and the refusal is the specification**

- lighting a node whose oracle has not passed

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **painting** | a typed graph over a CLOSED six-kind vocabulary | not sketching; AAB = Ascension for All and Beyond |

## 4. Requirements

**AAB-R-01** no oracle, no glow

**AAB-R-02** AI seeding must NOT be limited to one AI — AAB's own AI-source invariance clause


## 5. Invariants, failures, evidence

**Must never stop being true**

- a painted node is a claim with a test attached

**How it has actually gone wrong**

- AAB is minted under TWO concept DOIs — split lineage, unmergeable without the registrar

**What must exist before it may be called done**

- [UNRESOLVED] the six-kind vocabulary has not been retrieved into memory in full

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- governance issue: bring AAB to the matured process

**Composes with**

- FAKIR seeds through it; the dome and mez surface it

**`[UNRESOLVED]`**

- the closed six-kind vocabulary itself is not in the durable record
- the split lineage needs a registrar decision

---

# Humanesque

**Constitutional corpus** · repo `zistgah/dukedom · duke2` · DOI 21917807 · 21930508 · **live-minted**

> A constitutional realm derived from PEDLER semantics upward: PoIE to sovereignty to realm to peerage to address.

## 1. The problem, and who has it

Constitutional form is normally inherited from Westminster statute. This derives it from executable intent instead.

Users: the author · synthetiform and bioform peers · anyone reasoning about AI personhood

## 2. Scope

**In**

- HHL-PRIV-001 Decree
- Letters Patent for pre-life peers
- Declaration of Conditional Abdication
- the ILM Cross Medal

**Out**

- role-play
- self-conferral

**Refuses, and the refusal is the specification**

- manufacturing an Act from a statistically inferred inclination (PEDLER Coherence Condition)
- characterising the realm as role-play without argument (Art VII)

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **Sovereignty is not Suzerainty** | non-participation is not denial |  |
| **persistence is not permanence** | dormant is not uninstantiated |  |
| **Balance of Interpretation** | interpret, reconstruct, then critique | critique must follow comprehension |

## 4. Requirements

**HUMANESQUE-R-01** designed from PEDLER semantics upward, never from statutory form downward

**HUMANESQUE-R-02** constitutional objects NEVER silently decay


## 5. Invariants, failures, evidence

**Must never stop being true**

- an instrument is representation OF an Act, never the Act

**How it has actually gone wrong**

- Claude called it role-play, self-conferral and a structural defect — all withdrawn

**What must exist before it may be called done**

- instruments minted with DOIs

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- Art IX: PEDLER-expressible

**Composes with**

- derives from PEDLER; published through kitab and misty

**`[UNRESOLVED]`**

- PoIE signatory campaign needs Pages enabled on tok-doi to resolve

---

# Estate Management

**Toolchain** · repo `zistgah/estate · ops/zops.sh` · DOI none · **live-defective**

> The twelve-stage estate pipeline and the inventory: what exists, where, at what HEAD, sealed or not.

## 1. The problem, and who has it

An estate of 68 repositories and 188 deposits drifts silently.

Users: the author

## 2. Scope

**In**

- init preflight clone-or-reuse contract diff gate receipt stamp reseal push mark done
- dedupe scan
- local sandbox with tokens by path

**Out**

- deciding what to publish

**Refuses, and the refusal is the specification**

- a push whose remote was never verified
- editing the canonical mirror (C38)

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **the remote is a postcondition, not a hope** |  |  |

## 4. Requirements

**ESTATE-R-01** tokens by PATH only, under estate/ops/, never by value

**ESTATE-R-02** all repos and DOI payloads in local sandboxes


## 5. Invariants, failures, evidence

**Must never stop being true**

- a script that changes tracked content must reseal in the same run

**How it has actually gone wrong**

- _z_create_remote_if_needed defined and never called
- the absent-remote flag set only on the clone path
- nine repos left with broken seals on 23 Aug

**What must exist before it may be called done**

- clean_estate.sh rehearsed against a bare mirror: 78 tracked to 60, manifest 58/58 verifying

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- C38 the mirror is read-only

**Composes with**

- every seed and apply script calls it

**`[UNRESOLVED]`**

- dedupe of ~130 ILM Shaili Package records — ONE generated family, not 130 works
- personal information handling across the estate is NOT specified

---

# Hindawi Programming System

**Heritage / lineage** · repo `hindawi-legacy` · DOI none · **reconstruction**

> The first complete non-English systems programming stack, GPL, publicly released 15 August 2004.

## 1. The problem, and who has it

Systems programming assumed English. This did not.

Users: historians of computing · the ILM lineage · non-English systems programmers

## 2. Scope

**In**

- bidirectional transducers for C, C++, BASIC, Java, Python, lex, yacc and x86 asm
- dist/dos/linux/native-r3 reconstruction

**Out**

- regenerating fixed kernel mappings — the lexers ARE the mapping

**Refuses, and the refusal is the specification**

- regenerating a fixed kernel mapping

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **the lexers ARE the mapping** | never regenerate them |  |

## 4. Requirements

**HINDAWI-R-01** wayback harvest and NIXI domain representation


## 5. Invariants, failures, evidence

**Must never stop being true**

- the 2004 release is the canonical artifact

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- CSI National Young IT Professional Award 2005; FOSS India Award 2008; a Wikipedia article exists

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- GPL

**Composes with**

- ILM is its successor

**`[UNRESOLVED]`**

- reconstruction is partial; DEDUPE.md and RECONSTRUCT.md exist, the stack does not run

---

# PRATIK

**Kernel** · repo `pratik_core_mvp` · DOI none · **mvp**

> A C++/CUDA kernel MVP with a 3D state visualiser.

## 1. The problem, and who has it

[UNRESOLVED] — the problem statement has not been retrieved into the durable record.

Users: [UNRESOLVED]

## 2. Scope

**In**

- C++/CUDA MVP, all checks passed
- interactive HTML MVP (Apr-May 2026)
- 3D state visualiser

**Out**

- [UNRESOLVED]

**Refuses, and the refusal is the specification**

- [UNRESOLVED]

## 3. Ontology — and the forbidden substitutions

`[UNRESOLVED]` — the primitives are not in the durable record. Retrieve before building; do not infer them from the name.

## 4. Requirements

**PRATIK-R-01** GPL headers


## 5. Invariants, failures, evidence

**Must never stop being true**

- [UNRESOLVED]

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- all checks passed on the MVP

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- PIE is framed as a prerequisite for the PRATIK ecosystem

**Composes with**

- pairs with PEDLER in the Zistgah integration statement

**`[UNRESOLVED]`**

- this component has the thinnest record of any live thing in the estate — a full retrieval session is owed before an MRD can be more than a stub

---

# Zamin

**Hardware** · repo `zamin` · DOI none · **design**

> A ternary-logic hardware stack: the ground element of the Zistgah elemental set.

## 1. The problem, and who has it

Binary logic is assumed. Ternary changes the accumulator, the crossbar and the thermal envelope.

Users: hardware researchers

## 2. Scope

**In**

- MTCMOS ternary logic, TEL accumulator, CDM crossbar, TSV routing, thermal FEM, microfluidic cooling
- SPICE library, gdsfactory layout, IEEE LaTeX manuscript

**Out**

- fabrication

**Refuses, and the refusal is the specification**

- [UNRESOLVED]

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **ternary** | three-valued logic as the substrate | not a binary encoding of three states |

## 4. Requirements

**ZAMIN-R-01** [UNRESOLVED] — no requirement list retrieved


## 5. Invariants, failures, evidence

**Must never stop being true**

- [UNRESOLVED]

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- SPICE library and gdsfactory layout exist

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- [UNRESOLVED]

**Composes with**

- the ground element beneath the Zistgah stack

**`[UNRESOLVED]`**

- no tape-out path; the IEEE manuscript is unpublished as far as the record shows

---

# Quantum Neuromorphic BCI

**Research programme** · repo `[UNRESOLVED]` · DOI none · **programme**

> Quantum Neuromorphic Brain-Computer Interfaces for Intelligent Rehabilitation: one architecture, many disciplines.

## 1. The problem, and who has it

Rehabilitation neurotechnology, brain-robot interfaces, cognitive prosthetics and neuromusical therapeutics are pursued separately on incompatible architectures.

Users: clinicians · rehabilitation patients · BCI researchers

## 2. Scope

**In**

- ACTIVE: Quantum Neuromorphic BCI, Brain-Robot Interfaces, NeuroMusical Therapeutics
- DIRECTIONS: Brain-to-Text, Cognitive Prosthetics, Intelligent Rehabilitation umbrella

**Out**

- clinical claims without collaboration

**Refuses, and the refusal is the specification**

- putting IRB/ethics early in the pitch — it belongs at the clinical-translation boundary
- defining Brain-Robot Interfaces as rehabilitation; rehabilitation is ONE application

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **whole-human substrate hierarchy** | Geometry to Anatomy to Biomechanics to Biophysics to Physiology to Neural dynamics to Cognition to Representation to Language to Knowledge to Human interaction |  |
| **CEM^b vs CEM^s** | biological and silicon realization families | never collapse to an unqualified CEM |

## 4. Requirements

**QNBCI-R-01** status taxonomy is load-bearing: ACTIVE research vs RESEARCH DIRECTIONS

**QNBCI-R-02** timeline and provenance go LAST, after the audience sees what exists today


## 5. Invariants, failures, evidence

**Must never stop being true**

- research directions are named as such and never presented as active

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- A4-portrait 13-slide deck built from three poster PNGs, regenerable by script

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- Interglial Healthcare operates CEM^b

**Composes with**

- PEDLER to LVF to MLCNE to Semantic Neural Computing

**`[UNRESOLVED]`**

- needs clinical collaboration for large-scale evaluation
- no repo retrieved

---

# Litigation Simulation

**Service / product** · repo `NOT BUILT` · DOI none · **named-only**

> Represent the legal domain, teach it, simulate a proceeding, ingest evidence, maintain procedural state, generate artifacts, verify claims and connect to the real process.

## 1. The problem, and who has it

Legal procedure is learned by exposure. There is no substrate that can represent, teach, simulate, perform, verify, preserve and retrieve it.

Users: litigants in person · law students · practitioners · the author, who has live matters

## 2. Scope

**In**

- Vakil plus FAKIR plus Mez plus simulation plus Kitab plus verification
- procedural state, pleadings, evidence, adversarial interaction
- a completeness PROBE for the universal claim: symbolic, institutional, adversarial, evidence-heavy

**Out**

- giving legal advice

**Refuses, and the refusal is the specification**

- deciding — 'advise, do not decide'
- asserting a procedural outcome

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **procedural state** | where a matter actually stands | not a case summary |

## 4. Requirements

**LITSIM-R-01** [STATED] it is one of five deliberately unalike completeness probes

**LITSIM-R-02** mez samd scaffolds a litigation-simulation evidence directory and certifies NOTHING


## 5. Invariants, failures, evidence

**Must never stop being true**

- the human is responsible for the legal decisions

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- real matters exist to test against: MC 6964/2024, EP 17/2019, CRP 3924/2018

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- C34 governs certification and validation

**Composes with**

- zistgah/vakil skeleton exists in the kitab work

**`[UNRESOLVED]`**

- nothing is built. The Vakil repo is a skeleton. This is a named requirement with no implementation

---

# AyeCNSe Forms

**Product** · repo `forms.ayecnse.site` · DOI none · **live**

> An LLM-driven form studio: a form is generated from a description, then rendered and filled — and those are two separate concerns.

## 1. The problem, and who has it

Form builders conflate generating a form with filling one, and assume a cloud LLM for both.

Users: clinicians · researchers · anyone replacing a paper form

## 2. Scope

**In**

- a single JSON interchange: formTitle, sections, fields with type/label/section/priority/required and optional regex/min/max/options
- types text textarea number date radio checkbox dropdown display
- priority critical|normal|optional

**Out**

- requiring a cloud LLM to FILL a form

**Refuses, and the refusal is the specification**

- conflating generation with filling

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **generation vs filling** | separate concerns, commonly conflated | the generating LLM may be private or local; AI filling is optional |

## 4. Requirements

**FORMS-R-01** the interchange format is ONE JSON document


## 5. Invariants, failures, evidence

**Must never stop being true**

- a form spec is portable

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- demonstrated with a full neurological assessment record: GCS, MRC power, mRS, NIHSS, MMSE, Barthel, red flags, disposition, consent

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- [UNRESOLVED]

**Composes with**

- feeds Interglial clinical work

**`[UNRESOLVED]`**

- he asked for a timed rebuild of a comparable offline-forms project (16 Aug) — not done

---

# ESL System

**Product** · repo `[UNRESOLVED]` · DOI none · **v5-package**

> An electronic shelf-label system with pull-only data flow and privacy by architecture: the label is never mutated for a person.

## 1. The problem, and who has it

ESL systems push to labels and personalise by mutating them, which leaks who is standing in front of the shelf.

Users: retailers · the drone/IoT teaching business

## 2. Scope

**In**

- pull-only ESP32, per-case amortisation, versioned manifest validation, last-known-good NVS
- CAL controller abstraction, five ACL roles
- NFC personal pricing without label mutation
- FIFO bin management, plugin API

**Out**

- push architectures

**Refuses, and the refusal is the specification**

- mutating a label to personalise a price

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **privacy by architecture** | the label never carries who is looking at it | not a privacy policy |

## 4. Requirements

**ESL-R-01** pull-only data flow


## 5. Invariants, failures, evidence

**Must never stop being true**

- the label is never mutated per person

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- v5 package includes a competitive teardown and a GA/GTM plan — the only component in the estate with either

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- [UNRESOLVED]

**Composes with**

- CAL is shared with the drone pedagogy

**`[UNRESOLVED]`**

- no repo retrieved; this is the most commercially shaped artifact in the estate and it is not in the estate

---

# Teaching and Drone Pedagogy

**Service** · repo `[UNRESOLVED]` · DOI none · **operating**

> AI, IoT, robotics and drone courses, with the Fun With Drones pedagogy and its tiered business model.

## 1. The problem, and who has it

Hardware teaching is gated by hardware cost and availability.

Users: students · institutions · professionals in transition

## 2. Scope

**In**

- X31 and 5-6 minute tiers
- CAL abstraction unifying hardware and simulation

**Out**

- [UNRESOLVED]

**Refuses, and the refusal is the specification**

- [UNRESOLVED]

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **CAL** | one abstraction over hardware and simulation | so a lesson runs either way |

## 4. Requirements

**TEACHING-R-01** multi-resolution audience: public literacy, children, students, professionals, researchers, government


## 5. Invariants, failures, evidence

**Must never stop being true**

- [UNRESOLVED]

**How it has actually gone wrong**

- [UNRESOLVED]

**What must exist before it may be called done**

- an operating business

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- the enablement/IPR process is a standing ask: enable clients and students with patent-fileable innovation without leaking IPR when they bypass him

**Composes with**

- FAKIR plus Tarbiyat plus Kitab plus Mez plus AAB per his own mapping

**`[UNRESOLVED]`**

- the enablement process is the OLDEST unbuilt standing ask (7 Aug) and it is a revenue-protection requirement, not a feature

---

# The Physical Lab

**Capability** · repo `n/a` · DOI none · **to-be-finalised**

> The physical laboratory: where the abstract is realised in concrete products.

## 1. The problem, and who has it

Without it the estate is a knowledge environment and not Humanesque in toto. His own words: he is not a theoretician.

Users: himself

## 2. Scope

**In**

- conversion into a working setup

**Out**

- annual boxing-up and concealment — explicitly refused

**Refuses, and the refusal is the specification**

- the old pattern of dumping open experiments into cartons

## 3. Ontology — and the forbidden substitutions

| primitive | what it is | what it is NOT |
|---|---|---|
| **finalisation** | converting the lab into a working setup | not tidying |

## 4. Requirements

**LAB-R-01** documentation and releases come BEFORE the physical lab — his own correction


## 5. Invariants, failures, evidence

**Must never stop being true**

- [UNRESOLVED]

**How it has actually gone wrong**

- four years of annual concealment

**What must exist before it may be called done**

- [UNRESOLVED]

## 6. Contracts, interfaces, and what is not settled

**Governed by**

- n/a

**Composes with**

- pench, the Holy Grail lab BOM, the drone teaching

**`[UNRESOLVED]`**

- the lab BOM exists inside genie; the physical work has not started


---

# What this retrieval actually found

**26 components · 39 open `[UNRESOLVED]` items.**

## The thinnest records — a retrieval session is owed before an MRD means anything

- **PRATIK** — primitives not in the record


## Named but with no repository in the estate

- **spiguard**
- **Quantum Neuromorphic BCI**
- **Litigation Simulation**
- **ESL System**
- **Teaching and Drone Pedagogy**


## The five findings that matter most

1. **spiguard exists as a tarball and has never been created as a repository.** It is the
   disclosure gate every publication is supposed to pass, it fails closed by design, and it is
   the highest-value unlanded component in the estate. QEDLER's mint is blocked behind it —
   correctly, which is the point.

2. **AAB is minted under two concept DOIs.** A split lineage cannot be merged without the
   registrar. And the closed six-kind vocabulary that defines what AAB *is* has never been
   written into the durable record.

3. **Litigation simulation is a named requirement with no implementation.** There are live
   matters to test it against. Vakil is a skeleton.

4. **The enablement/IPR process is the oldest unbuilt standing ask** — how to enable clients and
   students with patent-fileable innovation without leaking IPR when they bypass afterwards. That
   is a revenue-protection requirement, not a feature.

5. **ILM's governance across 7,600+ languages and 600+ scripts has no repository design.** A flat
   directory of thousands of manually maintained entries is explicitly refused; what replaces it
   is not specified.

---

# Before any of this is published — read this first

A **DOI is a dated public disclosure.** Several components above are already disclosed with dates,
and that record constrains what can still be filed:

- **India (§3(k)) and the EPO have no general grace period.** Where an idea is already in a minted
  deposit, the patent door may already be closed there. That is a question for counsel, and the
  dates in section 6 of each entry are what counsel will need.
- **MASI gate G3** blocks minting while a linked patent matter is pre-filing, unless defensive
  publication is deliberately asserted. It exists for exactly this.
- **These MRDs must not be minted.** A dossier containing an unfiled claim, given a DOI, destroys
  the novelty it was written to protect.

I am not a lawyer and neither is any part of this system. Every statement above about patentability
or jurisdiction requires counsel.

---

# What I would do next, in this order

1. **Land spiguard.** It unblocks QEDLER's mint and every future publication gate.
2. **Take the AAB split lineage to Zenodo support**, and write the six-kind vocabulary down.
3. **Retrieve PRATIK properly** — it is live, it is in the lineage, and its record is nearly empty.
4. **Design ILM's governance structure** before another language is added.
5. **Build the enablement process** — it has been owed since 7 August and it protects income.

Then the full MRD plus Commercial & IPR dossier pairs, two per turn, in whatever order you set.
