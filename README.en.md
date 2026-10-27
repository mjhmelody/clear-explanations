# Clear Explanations · 把话讲明白

[简体中文](README.md) | **English**

**Make sense of AI answers: understand the point, the reasoning, and what to do next.**

Have you ever read a long AI answer and still wondered what it was trying to say? You ask for a clearer explanation, and it gives you the same answer with a few words changed.

This skill is for those moments. Use it from the start of a conversation, or when you want something explained again. Try it when learning something new, discussing work, or asking AI to help you figure something out.

## Suppose you need to analyze this month's sales

Here's an everyday work question to illustrate two ways of explaining something.

**You ask: “My manager asked me to analyze this month's sales. What should I look at first?”**

You might get an answer like this:

> Examine sales volume, growth trends, product mix, customer segments, and channel performance. Use month-over-month and year-over-year comparisons to identify anomalies, then drill down further.

Those are reasonable areas to investigate. But you may still be unsure what to do first, or why.

Another way to explain it:

> Start with one core question: **Did sales rise or fall this month, where did most of the change come from, and why?**
>
> Work through four steps:
>
> 1. **See the overall change.** Compare this month's revenue with last month's. If the business has strong seasonal patterns, compare with the same month last year too, so you don't mistake a seasonal shift for an operating problem.
> 2. **Find where it happened.** Break the figures down by product, store, or channel. Identify which parts contributed most to growth or decline to narrow your investigation.
> 3. **Investigate why.** For the parts with the biggest changes, start with units sold and actual selling prices, then check possible explanations such as promotions or stock shortages. Data gives you leads; events happening together don't establish causation.
> 4. **Explain what to do next.** State the overall change, where it came from, and which causes you've confirmed. Make recommendations supported by those findings, and identify the information still needed for unresolved questions.
>
> If your manager's real question is “Why did we sell more but make less money?”, include costs and profit and adjust the analysis accordingly.

You know what question you're answering and can follow a path: overall change → where it happened → why → what next. Each step has a purpose, and you can see when the direction needs to change.

*This example was written to illustrate the explanation style. It is not a recorded conversation.*

## When to try it

- AI has explained a concept, but you still don't understand what it means.
- You've received a long analysis and want to know what matters most.
- AI recommends something, and you want to understand why and whether it fits your situation.
- You've already said “I don't understand” and want a different explanation rather than a repeat.

The skill doesn't require long answers. Simple questions get direct answers. You can ask for less detail, more detail, or an example first.

## Download and use

Select **Code → Download ZIP** on the repository page, extract it, and rename the folder to `clear-explanations`. Alternatively, save just [SKILL.md](SKILL.md) inside a folder with that name.

**In Codex:** place the folder in your skills directory. The default path is:

```text
~/.codex/skills/clear-explanations/SKILL.md
```

If you configured `CODEX_HOME`, use its `skills/` subdirectory. Compare or back up any existing files with the same name before replacing them.

After installation, try this in your next conversation turn:

```text
$clear-explanations Please explain: [your question]
```

Or follow up in an existing conversation:

```text
$clear-explanations I didn't understand this part. Could you explain it with a different example?
```

The execution instructions are currently in Chinese. The skill has no scripts and needs no additional API key. For other AI tools, follow their own installation instructions; you can also try using the body of `SKILL.md` as conversation instructions.

## Why I made this

When working with AI to write code and build products, I often received detailed explanations that still left me unsure why a step was needed or what to do next. Sometimes I was stuck on just one step, but the AI started the whole explanation again.

I made this skill to capture what helped me: a clear starting point, an explanation of why the steps fit together, and a different approach when I got stuck. I'll keep improving it as new problems come up in use. You're welcome to open an Issue with something you found confusing or a suggestion for a clearer explanation.

A clear explanation can still be wrong. Important facts and conclusions still need checking.

## Use and redistribution

Author: Melody ([mjhmelody](https://github.com/mjhmelody)).

This project uses the [MIT License](LICENSE). You may use, modify, and redistribute it, including in commercial projects. When distributing the project files or modified versions, retain the original copyright notice and MIT license text.

If you share a modified version, you're also welcome to explain what you changed to help others choose.
