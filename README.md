![Khang Le: web engineering and developer tools](assets/banner.png)

I'm Khang, a frontend engineer based in Vietnam. I've built web products since 2018. Today I work on VietnamWorks, one of the country's largest job sites, and Navigos Talent One, its employer recruitment platform.

Production work I'm proud of:

- Built the frontend for AI job posting on Talent One. Employers give it a short prompt, an uploaded JD file or a link, and it drafts the job post.
- Built the frontend of Talent One's hiring-page builder, a paid add-on employers use to publish their own recruitment pages. Banks and an international talent program run their hiring pages on it.
- Designed how Talent One's pages are wired together. Every page, layout, access check and English or Vietnamese web address lives in one typed list, so a developer adds a screen with one entry and a broken link is caught before it ships.
- Built the app foundations Talent One runs on: the whole app switches between English and Vietnamese without reloading, and features can react to each other (a permission prompt, a profile switch, a warning about unsaved work) without being tied together in code. I later open-sourced these pieces as [Refract](https://refract.khangle.dev) and [React utilities](https://github.com/khanglvm/react).
- I make the technical decisions for Talent One's seven-person product squad and mentor two engineers.
- Built the frontend for AI candidate recommendations and AI screening on VietnamWorks Employer, which suggest candidates for a job and screen the people who apply.

My strengths are frontend architecture for large products and shipping AI features to real users. I can also take a feature end to end, from the screens people use to the server behind them.

I also build AI agent harnesses: the setup that lets AI coding assistants handle real tasks. I work on my own tickets with mine, and I published it for my team.

Outside work I build websites for clients, such as [UWANT Vietnam](https://uwant.com.vn) and [FIX Partner](https://fixpartner.co).

### Tools I build

- [Refract](https://refract.khangle.dev): my own state library for React. When many parts of a screen share the same data, such as a form or an editor, each part updates only when the piece it shows changes, and every change can be undone.
- [React utilities](https://github.com/khanglvm/react): ready-made building blocks for web apps made with React, a popular way to build web interfaces. They handle shared data, multiple languages and common screen behavior, so new screens take less code. [npm](https://www.npmjs.com/package/@khanglvm/react)
- [Relay](https://github.com/khanglvm/relay): lets you review an AI coding assistant's work visually. You pin comments on the exact part of a page or image, and the assistant gets your feedback where it applies. [npm](https://www.npmjs.com/package/@khanglvm/relay)
- [hookmux](https://github.com/khanglvm/hookmux): AI coding assistants such as Claude Code and Codex can run your own command at set moments, for example right before they run a terminal command. hookmux lets you write that behavior once, as a small plugin, and use it in each of them, such as a rule that stops a forced `git push`. [npm](https://www.npmjs.com/package/hookmux)
- [figma-lens](https://github.com/khanglvm/figma-lens): helps AI coding assistants read designs made in Figma, a popular design tool, so the screens they build match the design. It also checks the finished screens against it. [npm](https://www.npmjs.com/package/figma-lens)
- [Jira CLI](https://github.com/khanglvm/jira-cli): lets people and AI assistants update tasks in Jira, a common project tracker, with short commands. Every change can be previewed before it's sent. [npm](https://www.npmjs.com/package/@khanglvm/jira-cli)
- [Outline CLI](https://github.com/khanglvm/outline-cli): lets people and AI assistants find and edit pages in an Outline team wiki quickly, without overwriting anyone's newer changes. [npm](https://www.npmjs.com/package/@khanglvm/outline-cli)

Most of my work uses TypeScript, React, Next.js, Angular, and Node.js. I care about code that stays easy to change and interfaces that feel right.

[Portfolio & CV](https://khangle.dev) · [LinkedIn](https://www.linkedin.com/in/le-vu-minh-khang/) · [npm packages](https://www.npmjs.com/~levuminhkhang)
