## Hi there 👋

<!--
**vivekpawar002006-svg/vivekpawar002006-svg** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
You are a senior technical writer and full-stack developer. Create a professional, well-structured README.md for this project.

FIRST, analyze the codebase (do not guess):
- Read the root package.json, pnpm-workspace.yaml, tsconfig files, and every package.json inside artifacts/ and scripts/.
- Identify which artifact is the GAME and which is the CHATBOT. Read their entry points, components, API routes, and .env files.
- Only write what actually exists in the code. If something is unclear, add a "TODO" note instead of inventing details.

KNOWN FACTS:
- pnpm monorepo workspace (name: "workspace", MIT license, TypeScript ~5.9). npm and yarn are blocked by a preinstall script, so only pnpm works. Say this clearly in the install steps.
- Scripts: `pnpm run build`, `pnpm run typecheck`, `pnpm run typecheck:libs`.
- The workspace contains two projects: (1) a Game and (2) an AI Chatbot.
- The chatbot is a general Q&A bot that gives professional answers. It is likely built with the Groq API, developed on Replit and deployed on Vercel. Verify this in the code before writing it.
- Dependency: @replit/connectors-sdk. Dev tools: Prettier, TypeScript.

README STRUCTURE (clean Markdown, headings, tables, code blocks):
1. Title + one-line description + badges<img width="2760" height="1720" alt="ai_chatbot_illustration" src="https://github.com/user-attachments/assets/d4bacf33-6492-49ff-ada9-2497a26d8953" />
