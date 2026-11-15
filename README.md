# Margin

**Think through an idea. Work out the details in the margin.**

Margin is a Mac app for creating and refining artifacts with your favorite AI. Right now, it connects to Claude Code or Codex. An artifact can be a plan, an email, a document, a recipe, or a piece of research: something you want to work on and come back to.

Start with an idea, a question, or a problem. Plan how to build an app, work out a trip, or draft an email. Margin turns it into an artifact you can read, question, and revise.

Highlight any passage to add a **remark** and open a side conversation. Ask for an explanation, challenge an assumption, or explore another approach. When you're happy with the result, apply it back to the artifact.

Your main artifact stays in view, and each remark, including its side conversation, stays attached to the part it's about.

## What you can do

- **Create a first draft.** Describe what you want to make or figure out. Margin drafts an artifact and can ask clarifying questions along the way.
- **Add remarks where they matter.** Highlight a sentence or section and add a remark. The AI has the selected passage and the main artifact as context for the side conversation.
- **Apply what you've worked out.** A remark can help you understand a passage or lead to a change. Apply its outcome to the artifact immediately, or collect changes and apply them together.
- **Revise and revisit.** Keep refining the artifact, inspect earlier versions, and rewind when you want to take another direction.
- **Bring your codebase into the discussion.** Attach a local repository so the connected agent can read relevant code while helping you plan an app or think through a change. Repository access is read-only.
- **Take the artifact with you.** Export it as Markdown to use wherever you work next.

## What could you make?

- **An app plan.** Work through features, question technical choices in remarks, and refine the scope before you start building.
- **A trip itinerary.** Draft a route, add a remark to a busy day, and explore a slower alternative before updating the itinerary.
- **A recipe.** Start with an idea for dinner, discuss ingredient substitutions in a remark, and apply them to the recipe.
- **An email or document.** Draft what you want to say, highlight a paragraph, and use a remark to work on its tone or clarity.
- **A research brief.** Explore a topic, question an assumption, and use remarks to dig into specific findings before revising the brief.

## A typical session

1. Start with something like: **“Help me plan a relaxed three-day trip to Lisbon.”**
2. Read the first draft and answer any clarifying questions.
3. Highlight a day's activities, click **Add remark**, and ask: **“Could we do less travel this day and spend more time in one neighborhood?”**
4. Explore the options in the remark's side conversation, then apply the changes to the itinerary.
5. Keep adding remarks and refining the artifact, or export it when you're ready to use it.

**Doc** shows the current artifact. **Thread** shows the prompts, revisions, and versions that led to it. Your previous artifacts are available in the sidebar.

## Get Margin

Visit the [Releases page](https://github.com/domdewom/margin-app/releases) for Margin downloads and release notes.

The current desktop build targets **Apple Silicon Macs** (M-series chips). Intel Mac, Windows, and Linux builds are not currently available.

Installation:

1. Download the `.dmg` from Releases.
2. Open it and drag **Margin** into **Applications**.
3. Launch Margin and connect a supported agent.

## What you need

Margin connects to **Codex CLI or Claude Code installed on your Mac**, with a supported subscription login. Install at least one:

- [Install Codex CLI](https://learn.chatgpt.com/docs/codex/cli)
- [Install Claude Code](https://code.claude.com/docs/en/setup)

Follow the tool's installation and sign-in instructions, then open Margin to connect it. You'll need an account with subscription access to the tool you choose.

The desktop app uses those subscription connections; it doesn't require a separate AI API key. Provider usage limits still apply. You don't need this project's source code, Node.js, or Bun to run Margin itself.

## Your work and data

Artifacts, remarks, and version history are saved locally on your Mac. There is no Margin account or cloud sync, and saved artifacts remain readable without a connected agent.

**Local storage doesn't mean offline AI.** Prompts, document context, and relevant repository content may be sent to your connected AI provider to generate responses. That provider's data policies apply. Sign-in credentials are managed by Codex or Claude Code.

Margin is an early app. Export important artifacts as Markdown to keep a separate copy.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/domdewom/margin-app/issues). For bugs, include your macOS version, Margin version, and the steps to reproduce the problem. Remove private information from screenshots and examples.

This repository is the public home for Margin's downloads, release notes, and feedback. The application source code is maintained separately.
