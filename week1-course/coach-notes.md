# Week 1 Coach Notes

**Course:** AI Gameplan Week 1, Setup 101
**Student:** Reagan
**Last Updated:** 2026-05-16
**Sources:** CJ direction in Telegram, Hermes Agent setup reference, LangGraph supervisor reference, selected YouTube metadata checked with yt-dlp.

## CJ intent

This week is setup 101. Reagan needs to walk through the real setup, not just understand vocabulary. The first project is her own AI workspace.

## Important wording note

After the Telegram agent setup lesson, stop making every concept sound like it belongs to one product. Skills, commands, tools, APIs, MCPs, memory, and agent orgs can exist in Claude, Codex, and other agent systems. Teach the concept first, then the specific app.

## End of week outcome

By the end, Reagan should have:

1. Claude account created or logged in.
2. Codex account created or logged in.
3. Telegram installed and secured.
4. Telegram agent connected and responding.
5. Hermes installed in terminal.
6. Codex subscription auth completed through `hermes login --provider openai-codex`.
7. Saved sessions understood with `hermes sessions list`, `hermes --continue`, and `hermes --resume`.
8. A basic explanation of LLMs vs agents.
9. A basic explanation of MD, skills, commands, tools, APIs, MCPs, memory, models, agents, orchestrators, and proof.
10. An agent org chart with orchestrator, chief, CFO, content agent, research agent, and proof checker.
11. A finished My AI Workspace setup guide with proof.

## Coach emphasis

- Every lesson now has at least one visual aid: video, graphic, docs image, or online reference card. Use the visual first, then teach the concept.

- Do not let this become theory only.
- The setup section should be slow and literal.
- Do not expose Telegram bot tokens, API keys, passwords, OAuth codes, or private data in screenshots.
- CJ should approve pairing, bot, or auth steps.
- She needs to know how to come back tomorrow and find her work.

## Agent org examples

- CJ style org: orchestrator routes, chief decides priority, CFO watches money, content helper drafts, inbox triage flags messages, wiki keeper saves knowledge, proof checker verifies.
- LangGraph supervisor pattern: a central supervisor routes tasks to specialized agents.
- Crew style pattern: agents have roles, goals, tasks, and process.
- AutoGen style pattern: multiple agents talk through a task and hand off work.

## Red flags

- She watched videos but did not create accounts.
- She cannot install or explain the terminal setup steps.
- She thinks building blocks belong to one app instead of understanding the concept.
- She can repeat words but cannot explain them simply.
- The Telegram agent is not reachable by the end.
- No saved session proof.
- No screenshots or proof.
- She thinks the agent makes final decisions for her.

## Review questions for CJ

1. What is the difference between an LLM and an agent?
2. Show me Claude working.
3. Show me Codex working.
4. Show me the Telegram agent answering.
5. Show me Hermes installed in terminal.
6. Show me how Codex auth was connected without exposing secrets.
7. Show me how you find a saved session.
8. What does `/new` do?
9. What is a skill?
10. What is an MCP?
11. Walk me through your agent org chart.
12. Where is your My AI Workspace guide?

## Passing standard

She passes Week 1 if she can open the tools, explain the basics, show proof, find saved work, and walk CJ through her setup guide in 2 minutes.
