# Clear Explanations · 把话讲明白

[简体中文](README.md) | **English**

**Make sense of AI answers: understand the point, the reasoning, and what to do next.**

Have you ever read a long AI answer and still been unsure of the point? You ask for a clearer explanation, and it repeats the same thing.

This skill is for those moments. It adapts the explanation to the discussion and the kind of answer you need: a direct answer to a simple question, an overview before a complex task, or precise, professional language for analysis. Use it from the start, or ask it to explain something again when you get stuck.

## Suppose you need to analyze this month's sales

**You ask: “My manager asked me to analyze this month's sales. What should I look at first?”**

You might get an answer like this:

> Examine sales volume, growth trends, product mix, customer segments, and channel performance. Use month-over-month and year-over-year comparisons to identify anomalies, then drill down further.

There are plenty of directions, but the starting point and reasoning are still unclear. Another way to organize the answer:

> **Objective: identify the main sources of this month's sales change and assess the underlying drivers.**
>
> Structure the analysis in four parts:
>
> 1. **Overall performance:** compare this month's revenue with last month's to establish the size of the change. Where seasonality is significant, also use the same month last year to assess the trend.
> 2. **Contribution by segment:** break down the change by product, region, or channel. Identify the largest contributions to the overall increase or decline and prioritize those areas for investigation.
> 3. **Underlying drivers:** examine units sold, actual selling prices, and product mix for the main sources of change. Check explanations against business information such as promotions and supply conditions.
> 4. **Conclusions and recommendations:** summarize the findings, distinguish confirmed causes from hypotheses, and propose corresponding actions or further checks.
>
> If the objective is to explain rising sales but falling profit, include costs and profit and adjust the focus accordingly.

The objective comes first, followed by a clear analytical path. The language stays professional, and the reader can see how each part contributes to answering the question.

*This example was written to illustrate the explanation style. It is not a recorded conversation or a template for every answer.*

## When to try it

- You're learning a concept and want an explanation that starts from something familiar.
- You're reading an analysis or proposal and want the main point before the evidence and detail.
- You're comparing options and want to understand their differences and when each fits.
- You're stuck on one sentence or step and want that gap filled without starting over.

Clarity can take different forms. Everyday conversation can be brief and natural; professional discussion can be precise and concise. Use an overview when you need the full picture, or a local explanation when only one part is unclear. Your requested length, style, and format take priority.

## Download and use

Select **Code → Download ZIP** on the repository page, extract it, and rename the folder to `clear-explanations`. Alternatively, save just [SKILL.md](SKILL.md) inside a folder with that name.

**In Codex:** the user-level installation path in the [current official documentation](https://learn.chatgpt.com/docs/build-skills) is:

```text
~/.agents/skills/clear-explanations/SKILL.md
```

For use in one project only, place it in that project's `.agents/skills/clear-explanations/` directory. Compare or back up an existing skill with the same name before replacing it. Directory conventions can vary by version; follow the documentation for the tool you use.

After installation, try:

```text
$clear-explanations Explain this proposal using professional language. Start with the overall approach.
```

Or follow up in an existing conversation:

```text
$clear-explanations I didn't understand the second step. Please explain just that part.
```

If the skill doesn't appear after installation, restart Codex. The execution instructions are currently in Chinese. The skill has no scripts and needs no additional API key. For other AI tools, follow their installation instructions; you can also try using the body of `SKILL.md` as conversation instructions.

## Why I made this

When working with AI to write code and build products, I often received detailed explanations that still left me unsure why a step was needed or what to do next. Sometimes I was stuck on just one step, but the AI started the whole explanation again.

I made this skill to capture what helped me: a clear starting point, an explanation of why the steps fit together, and a different approach when I got stuck. I'll keep improving it as new problems come up in use. You're welcome to open an Issue with something you found unclear or a suggestion for a better explanation.

A clear explanation can still be wrong. Important facts and conclusions still need checking.

## Use and redistribution

Author: Melody ([mjhmelody](https://github.com/mjhmelody)).

This project uses the [MIT License](LICENSE). You may use, modify, and redistribute it, including in commercial projects. When distributing the project files or modified versions, retain the original copyright notice and MIT license text.

If you share a modified version, you're also welcome to explain what you changed to help others choose.
