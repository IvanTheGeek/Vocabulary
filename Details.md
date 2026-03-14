The Terms
Paradigm — the deepest level. A paradigm is a foundational worldview or framework that shapes what questions are even askable, what counts as a valid answer, and what the basic units of reality are. It's pre-theoretical. You don't usually choose a paradigm consciously — you operate from inside one.

Examples: Event sourcing as a paradigm (state is derived, not stored), object-oriented thinking, scientific empiricism, theological worldviews
Scope: Everything. A paradigm is a lens through which all other things are interpreted.
Key trait: Paradigms don't argue with each other well — they talk past each other because they share no common ground.

Domain — a bounded territory of knowledge, practice, or concern. A domain exists within one or more paradigms and has its own vocabulary, rules, and patterns. It's the field you're operating in.

Examples: Trucking logistics, accounting, healthcare, software architecture
Scope: Wide but bounded — a domain has edges
Key trait: Domains define what problems exist within them. "Detention pay" is a problem in trucking. It doesn't exist in accounting unless trucking data crosses over.

Context — the specific situation or circumstance you're currently in. Context is a narrowing of domain — it's the active instance, not the general territory.

Examples: "A driver filing IRS documentation at a truck stop" is a context within the trucking domain. "A laundry run at a Flying J on a layover" is even more specific.
Scope: Narrow and situational
Key trait: Context is what makes a general domain rule concrete. The same construct (like "expense") behaves differently depending on context.

Construct — a deliberately defined concept, model, or abstraction built and named within a domain or paradigm. Constructs are the vocabulary of a field — the named things you reason with.

Examples: "Event," "Projection," "Slice" in NEXUS; "Gross income," "deduction" in tax law; "Session," "Machine," "PaymentMethod" in LaundryLog
Scope: Concept-level — a single named thing
Key trait: Constructs are invented to carve reality at useful joints. The same underlying reality can have different constructs in different paradigms. Two paradigms looking at the same thing will name different constructs.

Perspective — a particular angle from which something is observed or interpreted. Unlike paradigm (which is largely unconscious), a perspective is a chosen or assigned viewpoint. You can hold multiple perspectives and switch between them.

Examples: The driver's perspective on a laundry expense vs. the IRS auditor's perspective vs. the app developer's perspective. All three see the same event differently.
Scope: Can operate at any level — you can take a paradigmatic perspective or a very narrow situational one
Key trait: Perspective is relational — it implies there are other perspectives. It's always "a perspective," never "the perspective."

Audience — the specific people who will receive, use, or be affected by what you're producing. Audience is contextual — it shapes how you express constructs and which perspectives you surface.

Examples: Truck drivers (LaundryLog users), IRS auditors reviewing records, developers reading NEXUS docs, a non-technical shipping coordinator reading an onboarding proposal
Scope: Communicative — it shapes form and language, not underlying content
Key trait: The same construct explained to different audiences requires different framing, vocabulary, and depth. The content doesn't change; the expression does.

Role — a defined function within a system or domain, carrying responsibilities, permissions, and expected behaviors. Role is more formal than perspective — it's a position, not just a viewpoint.

Examples: Driver, dispatcher, accountant, admin, system owner, consultant
Scope: Functional — a role defines what you do, what you're responsible for, and what you have access to
Key trait: Roles can be occupied by different people with different perspectives. The role is the function; the person brings the perspective.

The two axes interact. A role exists within a domain. A perspective is shaped by both role and paradigm. Audience is determined by context. A construct means different things depending on perspective.

A Concrete Example (LaundryLog)
TermInstanceParadigmEvent sourcing — state is derived from events; nothing is mutatedDomainTrucking / IRS expense documentationContextDriver on a layover at a TA Travel Center, running laundryConstructLaundrySession, MachineUsed, ExpenseRecordedPerspectiveDriver sees "I spent $4 on a dryer" / IRS sees "business expense requiring documentation"AudienceTruck drivers who aren't developers and don't care about event sourcingRoleThe driver as expense recorder in the system (vs. the auditor as expense reviewer)
The driver doesn't know or care about the paradigm. The paradigm shapes the constructs. The constructs power the UI. The UI is designed for the audience. The audience interacts through a role. The role activates certain perspectives. All of it happens in a context within a domain.

The most common confusion is between perspective and role (role is structural; perspective is experiential) and between domain and context (domain is the territory; context is where you're standing in it right now).