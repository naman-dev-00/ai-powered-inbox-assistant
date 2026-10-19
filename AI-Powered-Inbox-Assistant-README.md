# AI-Powered Inbox Assistant

A workflow configured with ChatGPT Work to help review Gmail conversations, identify messages that may need a reply, flag actionable tasks, and suggest context-aware responses while keeping the user in control.

## Project Overview

Email inboxes can mix important requests, deadlines, announcements, and newsletters. This project explores how an AI assistant can help separate actionable messages from routine email and make responding more efficient.

## Goals

- Review complete email threads rather than isolated messages.
- Identify messages that appear to need a reply.
- Highlight actionable tasks and potential deadlines.
- Prioritize important messages, such as faculty, job, and project-related emails.
- Suggest context-aware reply drafts for human review.
- Keep sending messages and making mailbox changes under explicit human approval.

## Workflow

1. Review the inbox and relevant email threads.
2. Classify messages by whether they need a reply or follow-up.
3. Identify deadlines and actionable tasks when present.
4. Draft a possible response when useful.
5. Let the user review and decide what to send or do.

## Safety and Limitations

- The workflow is an AI-assisted process, not a fully independent email application.
- Suggested replies may need corrections and should be reviewed before sending.
- Email content can be ambiguous; uncertain cases should be surfaced for the user rather than treated as facts.
- Recurring checks and scheduled behavior should be verified in the relevant ChatGPT task settings.
- No credentials, private email contents, or personal mailbox data should be included in this public repository.

## Testing

The workflow was tested with a sample email conversation that explicitly requested a response. The assistant reviewed the thread and proposed a reply. This demonstrates reply-detection and drafting, not comprehensive accuracy across every inbox scenario.

## Future Improvements

- Test with a wider range of email types and ambiguous requests.
- Evaluate false positives and false negatives in reply detection.
- Improve deadline extraction and prioritization.
- Add a clearly documented, secure Gmail integration only if a standalone application is developed.

## Project Type

AI workflow configuration and testing using ChatGPT Work.

This repository documents the workflow and its design. It does not contain a standalone Gmail application or claim to provide a production Gmail integration.
