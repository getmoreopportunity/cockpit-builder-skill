# Start here: free Cockpit Builder

You'll need about 20 minutes and the AI you already use (ChatGPT, Claude, Grok, Gemini or similar). No account, install or server needed.

## Option A: copy-paste prompt (easiest)
1. Open a new chat in your AI.
2. Copy everything in [PROMPT.md](PROMPT.md) and paste it in.
3. Answer its 10 questions, one at a time. "I don't know" is fine.
4. Check the map it shows you (you → your businesses → your offers → your priority). Correct anything wrong.
5. Save the three files it writes: `LLM.md`, `BRAIN.md` and `START-HERE.md`.
6. Let it help you finish one real task tied to your priority.

## Option B: give it the skill file
If your AI can't open links, open [fpf-cockpit-builder/SKILL.md](fpf-cockpit-builder/SKILL.md), copy the whole file, paste it into the chat and say:
> Use this Cockpit Builder skill to build my cockpit around my business.

If your AI supports skills natively (for example Claude skills or Codex), you can add the `fpf-cockpit-builder` folder as a skill. Follow that product's current instructions.

## After that
Start new AI work by attaching or pasting your `LLM.md` and `BRAIN.md` and saying:
> Read these files, tell me what you understand, then help me complete my current priority.

Update `BRAIN.md` when your priority changes.

## Good to know
- Pasting a file doesn't give your AI permanent memory or connect your accounts. Your files are the memory; you keep them.
- Keep passwords, API keys and private customer data out of these files.

## Example
Maya runs a design studio, sells an offer-page sprint to service founders, uses one AI and wants to draft her offer page this week. Her cockpit records only those facts. Price and customer proof stay marked as unknown until she supplies them. If she gives no answers, the AI asks the first question instead of inventing a business.
