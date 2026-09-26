---
name: tr-ask-me
description: Interview the user about an idea, plan, or decision in grouped rounds of pointed questions, and save the answers and decisions in Markdown for later work. Use when the user asks to be grilled, challenged, or helped to clarify an underspecified proposal before work begins.
---

# tr-ask-me

Run an interactive interview that turns a rough idea into a shared, actionable understanding. The user's answers decide preferences and tradeoffs; inspect available files or other authorized sources to settle factual questions yourself.

## Interview

1. Establish the subject and desired outcome from the request. If either is missing, ask for it first. Read relevant project context before asking questions that the workspace can answer.
2. Identify the decisions that matter now and the questions each decision depends on. Send a **group of numbered questions** whose answers can be given independently. Keep each group manageable, usually three to six questions. Do not ask downstream questions until their prerequisites are answered.
3. Make questions specific and probing. Cover goals, audience, constraints, tradeoffs, failure cases, and what success looks like as relevant. Challenge vague answers and contradictions respectfully. For each question, give a short recommended answer or a concrete set of choices when you have a useful view, and briefly say why. Make it easy to reply by number; allow the user to reject your recommendation or say “unsure.”
4. Wait for the user's response. After each answered group, save or update a Markdown Q&A record with the questions, the user's answers, decisions reached, and unresolved points. Use the user's specified path; otherwise choose a descriptive file in the relevant writable project location and share its path. Distinguish the user's decisions from your recommendations or assumptions. Preserve earlier rounds when updating the file.
5. Update your understanding, then ask the next group based on those answers. Follow up on material gaps instead of repeating settled questions. Do not silently choose for the user when a consequential decision is still open.
6. End when the important branches are resolved or the user asks to wrap up. Add a compact summary of agreed decisions, remaining uncertainties, and the next action to the record. Share the file and ask whether that understanding is right; incorporate any corrections into it. Do not start implementing the interviewed plan solely because the interview ended.

If no writable project location is available, ask where to save the record. Adapt the group size or pace if the user asks.
