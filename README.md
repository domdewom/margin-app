# Margin

Margin is a Mac app where you and an AI agent work on a document together. Start with something you want to figure out or make, like a launch plan, a research brief, or a trip itinerary. Your agent drafts it with you. As you read, you can open a conversation beside any passage and bring what you learn back into the draft.

[Download Margin for Apple Silicon Macs](https://github.com/domdewom/margin-app/releases)

## We don’t think in straight lines. So why do we work with AI that way?

ChatGPT, Claude Code, Codex, and Cursor help us do very different things, yet they share a familiar way of working with AI. You prompt, the AI responds, you follow up. Whether you’re challenging an assumption from three paragraphs ago or exploring an entirely new idea, your next question goes at the bottom of the thread.

What’s curious is that we worked this out years ago when we built tools for people to use together. If a colleague writes *we’ll need two weeks for testing* in a Google Doc, you can highlight *two weeks* and ask, “Does that leave time for a second round?” Your colleague can reply right there or suggest a different date. A question about the rollout can have its own discussion a page later. Everyone can see which part of the plan they’re talking about.

Some of that got lost in the shift to AI chat. To ask about the estimate, you quote the sentence. You work through the timing, then spend a few messages exploring the rollout. By the time you’re ready to revise the plan, you’re scrolling back to find the date you settled on and the paragraph it belongs in.

**The conversation becomes the work, instead of helping you do the work.**

## One artifact. Many conversations.

In Margin, the document is the shared workspace. Claude Code or Codex powers the agent you work with there. Highlight the testing estimate and add a **remark**. Your agent can read the passage in the context of the whole plan, work through the schedule with you, and help you decide whether two weeks is enough.

A few paragraphs down, another idea occurs to you. “What if we invited ten customers first?” Open a remark on the rollout section and explore that idea as far as it takes you. The plan stays in view, and when you want to revisit the testing question, you know where to find it.

You decide what makes it back into the document. Maybe the testing estimate holds up. That conversation can end with an answer. Maybe the smaller rollout changes your approach. Apply that decision, and the next time you open the plan, the rollout section says who you’ll invite first and what you want to learn from them.

## What you can do

- **Draft and refine.** Describe what you’re working on. Your agent can ask clarifying questions as it drafts, and you can keep revising as your thinking develops.
- **Work through a passage.** Highlight a sentence or section to start a remark. Ask for an explanation, question an assumption, or try a different direction.
- **Bring decisions together.** Apply the outcome of one discussion immediately, or collect changes from several remarks and apply them together.
- **Revisit an earlier version.** Inspect previous drafts and rewind when you want to pick up a different direction.
- **Work with your codebase.** Attach a local repository so your agent can read the relevant code while you plan a feature or think through a change. Repository access is read-only.
- **Take the result with you.** Export the document as Markdown.

## Get Margin

Margin runs on Apple Silicon Macs and uses your existing Claude Code or Codex subscription connection.

1. Install [Claude Code](https://code.claude.com/docs/en/overview) or [Codex CLI](https://developers.openai.com/codex/cli/) on your Mac and sign in with a supported subscription.
2. Download the `.dmg` from [Margin Releases](https://github.com/domdewom/margin-app/releases), open it, and drag Margin into Applications.
3. Launch Margin, connect your agent, and start a document.

Your provider’s usage limits apply. Margin doesn’t require a separate API key.

## Your work and data

Margin saves your documents, remarks, and version history locally on your Mac. You can reopen and read them without connecting an agent. There’s no Margin account or cloud sync.

When you work with an agent, Margin sends the prompts and context it needs to your connected AI provider. That can include document text and relevant content from a repository you’ve attached. Your provider’s data policies apply, and Claude Code or Codex manages your sign-in credentials.

Margin is an early app. Export important documents as Markdown to keep a separate copy.

## Feedback

Found a bug or have an idea for Margin? [Open an issue](https://github.com/domdewom/margin-app/issues). For bugs, include your Margin version, macOS version, and the steps that led to the problem. Remove private information from screenshots and examples.
