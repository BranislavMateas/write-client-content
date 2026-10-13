---
name: write-client-content
description: "Write and revise client articles, personal blog posts, and SEO landing pages using the active project's knowledge, audience, and voice. Use for article drafting, ghostwriting, or distinct content variations."
---

# Client Content

Turn the active project's client knowledge into publication-ready writing.
Perform this workflow directly in the current conversation using the agent's
existing file-reading, search, and writing tools.

This is an instruction-only skill. Do not run scripts or generated code to load
sources, count characters, validate drafts, or render output. Do not install
packages or launch another model, application pipeline, or API client.

## Language

Use English for workflow explanations, research notes, and interview questions
unless the user requests another language. Write the article in the language
specified by the user's brief or the selected client's requirements.

## Establish the client context

Use the brief, attachments, and relevant client context already in this thread.
Follow applicable project instructions. Read relevant client documents when more
context is needed: brand guidelines, audience descriptions, product or service
details, voice profiles, knowledge notes, and approved content examples.

Use the active project as the source of client identity. Do not import a default
company, author, industry, audience, or tone. Keep different clients' material
separate. If several clients are present and the intended client is unclear,
ask which one to use.

Resolve the topic, audience, content type, language, author, offer, and purpose.
Use the user's explicit requirements before inferred defaults. Ask only for
missing information that prevents a useful draft. Otherwise state a short
assumption and proceed.

Knowledge can be ordinary documents or an Open Knowledge Format (OKF) bundle.
For OKF, read the Markdown concepts directly and use their frontmatter to
distinguish knowledge from scaffolding. Exclude `index.md`, `log.md`, types
`Index`, `Log`, `Template`, `Example`, and types beginning with `_`.
Read the complete selected bundle when it fits the available context. If it
does not fit, select relevant concepts and state that limitation. Do not claim
to have read material that was truncated or unavailable. An OKF bundle is optional.

## Prepare the argument

Identify one reader problem and one useful argument or solution. Connect the
argument to the client's actual expertise, offer, and audience needs.

Draft one article unless the user requests alternatives. For multiple versions,
brainstorm several angles and group similar ones. Select a different question,
argument, audience need, or practical approach for each version. Changes in
wording or headings alone do not make a distinct version. When a count is not
specified, provide five distinct alternatives.

Use a thinking framework when requested or when it helps the argument:

- **First principles:** start with established facts and build the reasoning.
- **Jobs-to-Be-Done:** focus on the outcome the reader wants to achieve.
- **Constraints:** identify the factor that limits the result.
- **Inversion:** examine likely failures and derive useful actions.

Keep framework terminology out of the article unless it helps the reader.

## Ground the content

Use the selected client's knowledge and verified research as factual support.
Do not invent statistics, studies, quotes, results, sources, or author experiences.
Distinguish established facts from opinions and uncertain claims.

For personal writing, use documented experience and opinions supplied by the
author. If the author's position is needed but missing, ask a few specific
interview questions. Seek concrete examples, lessons, disagreements, and reader
advice. Do not invent first-person stories to fill a gap. Continue independent
research while waiting for answers.

Research when requested or when current claims need verification. Use available
search tools and primary sources. Record dates and exact source URLs. If the
user asks to approve a research brief, present it and wait before using it.
An instruction to research and write already authorizes use of the findings.
If research tools are unavailable, identify claims that still need verification.

Use internal links when requested or required by the client's content rules.
Use exact URLs from an approved inventory or verified research. Never construct
a plausible URL or add a link only to promote an old article. Usually zero to
two relevant internal links are sufficient.

Keep internal operating notes and confidential material out of public content.
Do not present an old event or project as recent. Use previous experience as
brief support unless the request is for a reflection or case study.

## Write the draft

Client requirements and the user's brief override the following defaults.

For a blog article:

- Make one clear argument and support it with useful detail.
- Match the client's voice. Use first person only for an identified author.
- Aim for about 6,000 visible characters within a 5,000–7,500 target range.
- Prefer four to six descriptive sections, usually with one or two paragraphs.
- Provide a separate meta description, aiming for 150–160 characters.
- Use lists only when they help the reader.
- Use short sentences, active voice, and familiar words. Explain unfamiliar terms.
- Avoid padding, repeated conclusions, marketing filler, and unsupported superlatives.
- Avoid em dashes unless the client's style explicitly calls for them.

For a strict SEO landing page, use this preset only when the request or client
context calls for it:

- Address one exact keyword, one reader problem, and one solution.
- Include the exact keyword in the H1 and meta description.
- Preserve the keyword's spelling and word order.
- Aim for 5,000–7,000 visible characters, preferably near 5,500.
- Aim for a 150–160 character meta description and use at most one list.
- Use descriptive headings rather than generic introduction or conclusion labels.
- Prefer sentences of at most 15 words and the client's established reader address.
- Explain principles and practical application. Omit case studies, specific company
  examples, numerical claims, and image notes unless the client requests them.

Treat length targets as drafting constraints. Visible length includes the title,
section headings, paragraphs, and list items. Exclude meta description, markup,
URLs hidden behind anchors, and image production notes. If exact counting is
unavailable through existing tools, state that the length is an estimate. Do not
claim an exact count or verified compliance based on an estimate.

Suggest images only when requested or when the client's format requires them.
Describe a concrete screenshot, a chart supported by existing data, or a useful
diagram. Keep alt text and production notes separate from the article's prose.

## Review and revise

Review the completed draft against the brief and client rules:

- Does it resolve the reader's problem and maintain one argument?
- Does the language, voice, reader address, and offer match the client?
- Is every specific factual claim supported by the selected material or research?
- Are author experiences real and dated accurately?
- Are headings descriptive, sections useful, and repeated material removed?
- Does each link use an exact approved URL and help its surrounding sentence?
- Does the draft meet the requested structure, keyword use, and length target?

Make targeted revisions for each issue. Cut secondary sections and repetition
when shortening. Add supported substance when expanding. Do not generate another
generic version instead of fixing the identified problems.

Use up to three revision passes. If requirements conflict or a check remains
unresolved, identify the issue instead of calling the draft ready. Distinguish
editorial review from exact measurements or checks unavailable in the host.

## Deliver

Return the article in the conversation unless the user or project requests files.
Use the requested format. Markdown is the default. Do not require intermediate
JSON, a fixed output directory, or an HTML export.

When HTML is requested, write the HTML directly. Use semantic headings,
paragraphs, lists, and exact approved link targets. Escape literal text and
attribute values. Follow the project's CMS conventions without adding helper code.
When files are requested, save them in the agreed project location and provide
links. Avoid overwriting unrelated files.

Keep research notes and editorial status separate from the publication-ready
article. Report unresolved issues briefly. Publish or send content only when
the user requests that action.
