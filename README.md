# Client Content

An instruction-only AI skill for articles, personal blog posts, and SEO landing
pages. It uses the active project's client knowledge, audience, language, and voice.

The agent writes and reviews content directly in your conversation. The skill
contains no scripts, executables, package dependencies, or API clients.

## Install

```sh
npx skills add BranislavMateas/write-client-content --skill write-client-content
```

View the listing on
[skills.sh](https://skills.sh/branislavmateas/write-client-content/write-client-content).

For a global Codex installation:

```sh
npx skills add BranislavMateas/write-client-content --skill write-client-content --agent codex --global
```

You can also copy `skills/write-client-content/` into your agent's skills
directory. For a chat tool without skill support, paste
[SKILL.md](skills/write-client-content/SKILL.md) into the conversation as instructions.

## Use

Open the client project, then invoke the skill with your brief:

```text
$write-client-content Write an article about consent management for this client's audience.
```

Other examples:

- "Write three versions with distinct arguments. Use the project's brand guidelines."
- "Interview me before drafting a first-person article about this topic."
- "Research current developments, then write a source-supported article."
- "Revise this landing page. Keep the exact keyword and remove repeated sections."

Invocation syntax depends on the host. You can also ask your agent to use
**Client Content** by name.

## What it does

- Reads the selected client's knowledge and voice from the current project.
- Keeps different clients' material separate.
- Builds one argument around a reader problem.
- Produces distinct angles when alternatives are requested.
- Uses supplied author experiences and verified research.
- Checks factual support, tone, structure, keywords, and approved links.
- Revises identified issues before delivery.
- Returns Markdown by default, or the format requested in the brief.

The instructions are in English. Article language follows the brief or the
client's requirements. Ordinary documents and OKF knowledge bundles are supported.
No fixed directory structure is required.

Character targets guide drafting. Exact counts are reported only when the host
provides a reliable count. The skill does not execute code to verify length.

## Read before use

Review the complete [instructions](skills/write-client-content/SKILL.md).
The skill uses your agent's existing file-reading, search, and writing tools.
It publishes or sends content only when you request that action.

Created by [Branislav Mateáš](https://bmateas.com).
Also available from [bmateas.com/tools](https://bmateas.com/tools).
