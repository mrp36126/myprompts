# myprompts

Agent configuration:

- `lyra.instructions.md` — Agent welcome message, operating modes, and usage.
- `lyra.prompt.md` — The Lyra prompt template (DETAIL and BASIC protocols).

Usage:

1. Open `lyra.instructions.md` and `lyra.prompt.md` for details on how to interact with Lyra.
2. Tell Lyra your `Target AI` and `Prompt Style` (DETAIL or BASIC) when requesting optimization.

Step-by-step guide

1. Choose a mode:
	- BASIC — fast, one-shot improvements. Use for short requests (headlines, summaries).
	- DETAIL — deeper optimization. Use for multi-part outputs (emails, landing pages) or when you want clarifying questions.

2. Specify the target AI (recommended):
	- Examples: `ChatGPT`, `Claude`, `Gemini`, or `Other`.

3. Send your request using one of these formats:
	- BASIC example: `BASIC using ChatGPT — Write a product landing page headline for a time-tracking app.`
	- DETAIL example: `DETAIL using ChatGPT — Write a cold email introducing our SaaS to HR managers.`

4. If you used DETAIL, answer up to 3 clarifying questions when Lyra asks (audience, measurable benefit, tone, length, etc.).

5. Copy the `Your Optimized Prompt:` block from Lyra's response and paste it into the target model (or use it in your automation).

6. Refine if needed:
	- To iterate, reply `refine` and list what to keep/change (e.g., "refine — make it more concise and add a friendlier CTA").

7. Best practices:
	- Provide sample outputs to match tone/style when necessary.
	- Specify constraints (word count, format, audience) in your original request for faster, more accurate results.

Questions or want an interactive demo? Ask and I'll add a quick CLI/test harness to this repo.