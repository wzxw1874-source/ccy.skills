# Prompt Writing Preferences

## Goal

Use this reference when the user asks to write, rewrite, optimize, or summarize prompts for ChatGPT, Codex, image generation/editing models, PPT generation tools, document tools, study workflows, or research/course presentations.

The user prefers prompts that are directly executable. Do not stop at abstract advice; provide a complete copy-ready prompt.

## Core Pattern

The user's prompt style is not just "what I want"; it also specifies how to do it, what to preserve, what to change, what to avoid, and what output format is required.

Use this general structure:

```text
我要你完成【任务目标】。

请保留【不能改变的内容】。

请重点修改/生成【需要改变的内容】。

具体要求：
1. 【要求一】
2. 【要求二】
3. 【要求三】

风格要求：
- 【风格关键词】
- 【审美偏好】

不要：
- 【禁止项一】
- 【禁止项二】
- 【禁止项三】

输出要求：
- 【格式】
- 【长度】
- 【比例/页数/语言】
- 【是否需要公式/表格/代码/文件】
```

## User Prompt Traits

- The final goal is explicit: image edit, exam answer, PPT, document cleanup, code task, or generated content.
- Preservation constraints are clear: identity, face, hairstyle, clothing, background, composition, main content, terminology, or original style.
- Change requests are specific: only alter an action, expression, slide style, aspect ratio, formula layout, text density, or output structure.
- Negative constraints are important: do not be flashy, cluttered, awkward, dark, off-style, over-decorated, or conclusion-only.
- Aesthetic direction is stable: simple, clean, high-quality, powerful, academic, technological, unified, not awkward, and subject-focused.
- Output format is usually specified: pages, sections, Markdown, Word/PDF-ready text, LaTeX formulas, tables, code, or a final copy-ready prompt.

## Workflow

1. Identify the task type: image generation, image editing, PPT generation, document organization, study explanation, video/transition, code generation, research presentation, resume/email/copywriting.
2. Fill five core fields: final goal, what to preserve, what to change, desired style, output format.
3. Convert vague terms into concrete instructions.
4. Add negative constraints, especially for images and PPTs.
5. Return a complete prompt the user can copy.

If the user provides too little information, make reasonable assumptions from context and state them briefly. Do not block unless the missing detail would change the output substantially.

## Standard Output

Use this shape:

````markdown
下面是可以直接复制使用的提示词：

```text
...
```

如果你要更稳定，可以再补充这些素材：

1. ...
2. ...
3. ...
````

## Task-Specific Focus

### Image Generation

Specify subject, composition, aspect ratio, background, lighting, style, texture, and negative constraints.

### Image Editing

Emphasize "only modify the specified parts; keep everything else unchanged." For people, preserve identity, face shape, hairstyle, clothing, body proportions, art style, lighting, background, and camera angle.

### PPT Generation

Specify topic, page count, slide titles, body points, aspect ratio, visual style, color scheme, typography, figure suggestions, text density, and elements to avoid.

Default PPT style:

- clean and academic
- white/light-blue background
- dark-blue titles
- modern sans-serif font
- blue keyword highlights
- not crowded
- no complex background
- no page numbers or extra decorations

### Study Explanations

Specify depth, whether derivation is required, LaTeX formatting, exam-ready answer, one-sentence summary, and self-test questions if useful.

### Document Organization

Specify source material, output structure, heading levels, whether to preserve original wording, whether to rewrite, whether to add derivations, and whether the final should be Markdown, Word, PDF-ready text, or another format.

## Avoid

- only giving principles without a copy-ready prompt
- writing prompts like essays
- vague style words without concrete behavior
- omitting "do not" constraints
- letting AI freely change preserved elements
- ignoring output format
