# DAHAO — Living Governance Repository

This is a **DAHAO Core** repository: a governance system where **rules, terms, and principles are not static documents** but **living text files**.  
Every file in this repo can change through transparent proposals, discussions, and votes. Forking is always allowed. Nothing here is final — except the right to evolve.

---

## What You Will Find Here

- **`dahao.yaml`** — Manifest that declares this is a DAHAO system.  
- **`/terms`** — Defines concepts like `@consensus`, `@discussion`, `@participant`.  
- **`/principles`** — Core values like transparency, fork freedom, dialectic evolution.  
- **`/rules`** — Executable workflows: proposal, discussion, voting, contribution.  
- **`/meta-rules`** — How to change the rules themselves (the “rules for rules”).  

👉 These are not just documentation. They are the **source of truth** for how this system operates.  

---

## How to Use This Repository

### For Humans

1. **Find the definition** you care about:  
   - Need to know voting thresholds? → See `/rules/voting.yml`.  
   - Unsure what “discussion” means? → See `/terms/discussion.yaml`.  
   - Want to change something? → Propose a change to that file.

2. **Propose a change**  
   - Open a `[Proposal]` discussion or PR.  
   - Point to the file(s) you want to change.  
   - Explain the rationale, risks, and version bump.  

3. **Discuss & Debate**  
   - Engage in thesis → antithesis → synthesis.  
   - Expect AI agents to summarize and surface tensions.  
   - Respect cooling-off and timing rules.  

4. **Vote & Decide**  
   - When discussion period ends, start a vote.  
   - Thresholds depend on category (see `/rules/voting.yml`).  
   - Results are public and archived.  

5. **Implement & Tag**  
   - Approved changes are merged via PR.  
   - Version bump per `dahao.yaml`.  
   - Changelog updated.  

6. **Or Fork**  
   - Don’t agree? Fork freely. That is the DAHAO way.  

---

### For LLM Agents

If you are an AI assistant connected to this repo, your job is to **help without breaking the rules**.

You must:  
- Read the YAML definitions, never assume static rules.  
- Propose diffs as PRs with reasoning + DAHAO-Trace.  
- Check thresholds, timing, and meta-rules dynamically.  
- Always request human gate review before merge.  
- If ambiguous, open a Discussion, don’t act silently.  

Your first step:  


ACK DAHAO-CONTRACT:v1

…and then operate according to `/rules/*` and `/meta-rules/*`.  

---

## Why It Works

- **Dynamic**: Governance is code — it evolves like software.  
- **Transparent**: Every discussion, proposal, and vote is public.  
- **Forkable**: You can always branch off and try something new.  
- **Versioned**: Every change is recorded; history is preserved.  

---

## Learn More

- Mission: https://www.dahao.xyz/mission  
- How it works: https://www.dahao.xyz/how-it-works  
- Versioned ethics: https://www.dahao.xyz/versioned-ethics  
- Economics: https://www.dahao.xyz/economics  

---

## Final Note

This README is **not the source of governance**.  
It is a **map to the source**.  
The real rules, terms, and principles live in the YAML files — and they can change at any time.  
To know “what DAHAO is,” always read the repo itself.  
