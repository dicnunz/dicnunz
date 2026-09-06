# Nicholas Dunzelman

Computer science student at Florida Tech and Community Lead at Krea.

## Current work

**[Folio](https://github.com/dicnunz/folio)** is my senior project with Caleb Brooks. We are building a student planning app that turns coursework into editable plans and a shared daily or weekly schedule, with optional task-completion rewards.

The project is in development. The repository currently contains our project plan, presentation, and course website.

[Project website](https://dicnunz.github.io/folio/) · [Project plan](https://github.com/dicnunz/folio/blob/main/docs/documents/first-semester/project-plan/project-plan-2026-08-30.pdf)

## Selected contributions

**[Bifrost: streaming stop reasons](https://github.com/maximhq/bifrost/pull/3640)** — merged upstream. Tool-call completion information could be lost when converting chat responses through the Responses API format to Anthropic's format. The fix carries that information through the conversions and adds regression tests, including streams containing both text and tool calls.

**[Booklogr: equivalent ISBN lookup](https://github.com/Mozzo1000/booklogr/pull/95)** — merged upstream. A book saved under an ISBN-10 should also be found using its equivalent ISBN-13. The change normalizes identifiers, validates check digits, converts equivalent ISBNs, and checks both forms while keeping the lookup scoped to the current user.

## Technical experiment

[Asyncio thread cancellation](https://github.com/dicnunz/asyncio-thread-timeout-lab) reproduces why cancelling an awaiter does not stop its running thread, and compares a semaphore with a dedicated worker pool. Includes a runnable demo and six tests.

[Website](https://dicnunz.github.io/) · [LinkedIn](https://www.linkedin.com/in/nicdunz/) · [X](https://x.com/nicdunz)
