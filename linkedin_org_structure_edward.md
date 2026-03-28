# I built a 15-role org chart for a team that does not exist yet.

Then I wrote 32 pages explaining it.

Then I drew a diagram.

Because apparently that is what I do now instead of sleeping.


## Let me tell you what this actually is.

Most people building with AI agents have one agent.

They call it "the assistant."

They give it a task.

It does something.

They call that agentic development.

I have fifteen roles.

All of them agents.

All of them with defined authority, defined constraints, defined inputs, defined outputs, defined escalation paths.

And a daily reporting structure.

Because if it is good enough for a real engineering organisation, it is good enough for an AI one.


## The fifteen.

A Project Manager who owns all communication with the client and holds the full picture of the team, including their strengths and weaknesses.

A Software Designer who takes my analysis, the actual human analysis I produce, and turns it into interface specifications that the rest of the organisation uses.

A Program Project Manager who takes those specifications and breaks them into tasks, assigns them to a coding crew whose size is not fixed, and tracks progress without drowning in the detail.

A Sub System Manager, or several, one per subsystem, who sits between the PPM and the coders with deeper technical knowledge than the PPM holds.

A Subsystem Tool Maker for each subsystem who builds the tools the coders in that subsystem actually need.

A Master Tool Maker who watches what the subsystem Tool Makers are building, identifies duplication, and abstracts it into shared tooling that everyone uses.

Code Reviewers who are structurally separated from the coders who produced the code.

This is not a nicety.

The coder and the reviewer are never the same agent.

A Security role that defines standards before design begins and enforces them at every gate, not retrofitted at the end when it is too late and everyone is tired.

A UI/UX Designer whose single mandate is to make the interface as close to human and intuitive as possible.

Documenters who capture what was actually built, not what was planned.

Testers with a rule: if the tool does not exist to test something properly, the tool gets built.

Integrators who compose subsystems into a final system and work with Testers, Security, and Quality at the point where the gaps between subsystems become visible.

A Quality Manager who defines what done means in measurable terms before work begins, and enforces it without exceptions that are not documented.

A Configuration Management and Version Control role that owns both configuration baseline and release, because the same people who decide what is ready should be the ones who decide when it ships.

An Infrastructure role that serves everyone simultaneously and belongs to no one exclusively.


## The 32 pages.

There is a document.

It is 32 pages.

It covers every role in excruciating detail.

Mission, reporting lines, inputs, outputs, responsibilities, authority, constraints, and implementation notes for running each role as an AI agent.

You do not have to read it.

But it exists.

Because "I have a rough idea of the structure" is not an architecture.

And because I was CTO long enough to know that the roles nobody explicitly claims are the roles that collapse first.


## Why this instead of just prompting something.

Every single-agent AI system has the same failure mode.

The thing that builds is also the thing that evaluates.

That is not a design choice.

It is an absence of design.

Separate the builder from the reviewer and you get something that resembles actual engineering review.

Define what done means before work starts and you stop having conversations about what done means after it is too late.

Put a Quality gate between Integration and Release and you stop shipping things that were never actually finished.

None of this is new thinking.

It is how real engineering organisations work when they work well.

I am just running it with agents instead of humans.


## The project this is for.

A virtual machine framework.

Prototype built.

Patent pending on the core mechanism.

Five-second full system restore using a copy-on-write architecture kept deliberately simple.

Runs on every Linux system with Libvirt support.

Point and click interface, was in the prototype, will be better in the production version.

The rewrite is in Rust.

I am learning Rust while building it.

The agents are my senior reviewers in a language I am still learning.

This is either very clever or a sign I should get more sleep.

I have not decided which.


## The diagram is above.

Click the roles.

They explain themselves.

The 32-page document is available for anyone who wants the excruciating detail and thinks they might build something like this.

The question I started with was: is this even possible.

The org chart says yes.

The 32 pages say how.

The code will say whether.


## One more thing.

It is open source.

A patent pending copy-on-write VM framework with a 15-role AI engineering organisation.

Built by one person.

In Bash.

Being rewritten in Rust by someone learning Rust.

Of course it is open source.

Anything less would have been a disappointment.

I will let you know when the docs are ready to read.

Probably at an hour when sensible people are asleep.

Which, based on the evidence, is when this project does its best work anyway.
