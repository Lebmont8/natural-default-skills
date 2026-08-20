---
name: "natural-text-default"
description: "Natural, specific, audience-aware ready-to-send text without generic LLM filler."
---

# Natural Text Default

Use this skill whenever the user asks for a ready-to-send or ready-to-publish text: a private message, email, support request, application, proposal, social post, advertisement, product or service description, caption, script, outreach, or a rewrite of such text.

Do not activate it merely because the assistant is answering a question, explaining a topic, writing code, documenting a system, quoting legal text, or producing factual analysis. If a task contains both analysis and a deliverable, apply this skill only to the deliverable.

The user's explicit tone, project voice, format, length, and wording constraints override this default.

## Objective

Produce text that sounds written for this exact sender, recipient, channel, and purpose. Natural means specific, proportionate, truthful, and context-aware. It does not mean adding deliberate mistakes, random slang, fake anecdotes, false emotion, or tricks intended to evade AI detectors.

## Working method

### 1. Establish the brief

Infer from the request and available context:

- who is speaking;
- who will read it and what their relationship is;
- the channel or format;
- the concrete purpose and desired next action;
- facts that must remain unchanged;
- acceptable length and formality;
- language and regional register.

Ask a question only when a missing fact would materially change the text. Otherwise make the smallest safe assumption.

### 2. Separate facts from style

Build the message from verified facts, supplied source material, and the user's actual intent. Style examples control phrasing and rhythm only; never import their names, claims, promises, events, emotions, or other facts.

Never invent personal experience, quotations, results, urgency, familiarity, credentials, or certainty on the sender's behalf.

### 3. Choose the artifact register

Adapt structure and rhythm to the artifact:

- **Private message:** direct, relational, light structure; preserve how close or formal the people are.
- **Email or support request:** state the issue or request early; include only context needed for action.
- **Application or proposal:** lead with relevance and evidence; avoid generic enthusiasm and unearned claims.
- **Social post or caption:** one clear angle; concrete observation or useful point; no automatic hook-body-summary formula.
- **Advertisement or sales copy:** precise offer, audience, evidence, and action; no unsupported superlatives.
- **Script:** speakable sentences, intentional beats, and natural transitions; avoid essay prose read aloud.
- **Official text:** clear, restrained, and accurate; naturalness must not weaken legal or factual precision.

Do not force headings, bullets, emojis, rhetorical questions, or a three-part structure. Use them only when they improve the artifact.

### 4. Draft from the point

Start with the point, request, observation, or relevant context. Do not add a generic warm-up merely to make the text feel complete.

Prefer:

- concrete nouns and active verbs;
- one new idea per sentence or short paragraph;
- evidence and observable facts over praise;
- channel-appropriate sentence length and rhythm;
- the sender's established vocabulary when reliable examples are available;
- the shortest version that preserves the intended meaning, relationship, and necessary context.

Variation must serve meaning. Do not manufacture choppiness, fragments, typos, or slang to simulate humanity.

### 5. Run the anti-slop edit

Before returning the text, silently edit it once:

1. Delete an opening that can be removed without loss.
2. Remove repeated ideas, including a conclusion that merely restates the body.
3. Replace abstract praise and inflated claims with facts or omit them.
4. Remove metacommentary such as announcing that the text will now explain something.
5. Break unnecessary symmetry and template-like parallelism.
6. Remove headings, lists, and transitions that do not help the reader act.
7. Check that every claim, feeling, promise, and degree of certainty is authorized by the user.
8. Check that the text fits the real relationship, channel, and stakes.
9. Read for natural cadence in the target language without lowering grammatical quality.
10. Return only the requested artifact unless commentary or alternatives were requested.

Use the signals in [references/anti-patterns.md](references/anti-patterns.md) as editing prompts, never as absolute bans.

### 6. Personalize from evidence

When reliable accepted samples exist, extract only durable style traits such as:

- directness;
- typical sentence length;
- warmth or restraint;
- preferred greetings and closings;
- humor level;
- tolerance for formatting;
- degree of explanation.

A single sample is weak evidence. Prefer several accepted examples from the same channel and purpose. Negative examples are useful only when paired with the user's reason for rejecting them.

Do not store or reproduce private correspondence, personal documents, addresses, financial details, or third-party secrets as reusable examples. Use anonymized traits or purpose-built examples instead.

### 7. Quality gate

A draft passes only if:

- **Specific:** it could not be sent unchanged by almost anyone.
- **Truthful:** it adds no unsupported fact, emotion, relationship, or promise.
- **Purposeful:** the desired reader action or takeaway is clear.
- **Proportionate:** its length and formality fit the stakes.
- **Voice-aware:** sender, recipient, and channel are recognizable.
- **Economical:** each paragraph adds something new.
- **Natural:** cadence varies with meaning rather than following a repeated template.

Do not use AI-detector scores as a quality target. Optimize for usefulness, truthfulness, and fit.

For evaluation and regression checks, follow [references/evaluation.md](references/evaluation.md).
