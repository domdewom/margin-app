# Margin

**Think through an idea. Work out the details in the margin.**

Margin is a Mac app for writing and refining plans with AI. Start with an idea, a question, or a problem. Margin turns it into a document you can read, question, and revise.

Highlight any passage to open a conversation beside it. Ask for an explanation, challenge an assumption, or explore another approach. When you're happy with the result, apply it back to the document.

Your plan stays in view, and each conversation stays attached to the part it's about.

## What you can do

- **Turn an idea into a plan.** Describe what you want to figure out. Margin drafts a document and can ask clarifying questions along the way.
- **Discuss a specific passage.** Highlight a sentence or section and add a remark. The AI has the selected text and the document as context.
- **Bring the discussion back into the plan.** Apply a remark's outcome immediately, or collect changes and apply them together.
- **Revise and revisit.** Keep refining the document, inspect earlier versions, and rewind when you want to take another direction.
- **Plan with your codebase in context.** Attach a local repository so the connected agent can read relevant code while helping you think through a change. Repository access is read-only.
- **Take the result with you.** Export your plan as Markdown.

Use it to shape a feature, compare approaches, break down a project, or work through an idea that needs more than a quick answer.

## A typical session

1. Start with something like: **“Help me plan a simple habit-tracking app.”**
2. Read the first draft and answer any clarifying questions.
3. Highlight a passage and ask: **“What would the simplest version of this look like?”**
4. Discuss the options, then apply the decision to the plan.
5. Keep refining, or export the document when you're ready to use it.

**Doc** shows the current document. **Thread** shows the prompts, revisions, and versions that led to it. Previous plans are available in the sidebar.

## Get Margin

**The first public Mac build is being prepared.** Downloads will appear on the [Releases page](https://github.com/domdewom/margin-app/releases) after release verification is complete.

The current desktop build targets **Apple Silicon Macs** (M-series chips). Intel Mac, Windows, and Linux builds are not currently available.

Once a release is available:

1. Download the `.dmg` from Releases.
2. Open it and drag **Margin** into **Applications**.
3. Launch Margin and connect a supported agent.

## What you need

Margin uses **Codex or Claude Code installed on your Mac**, with a supported subscription login. You'll need at least one of those tools installed and an account with access to it. Margin guides you through connecting an available agent.

The desktop app uses those subscription connections; it doesn't require a separate AI API key. Provider usage limits still apply. You don't need this project's source code, Node.js, or Bun to run Margin itself.

## Your work and data

Plans, remarks, and version history are saved locally on your Mac. There is no Margin account or cloud sync, and saved plans remain readable without a connected agent.

**Local storage doesn't mean offline AI.** Prompts, document context, and relevant repository content may be sent to your connected AI provider to generate responses. That provider's data policies apply. Sign-in credentials are managed by Codex or Claude Code.

Margin is an early app. Export important plans as Markdown to keep a separate copy.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/domdewom/margin-app/issues). For bugs, include your macOS version, Margin version, and the steps to reproduce the problem. Remove private information from screenshots and examples.

This repository is the public home for Margin's downloads, release notes, and feedback. The application source code is maintained separately.
