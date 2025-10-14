# Obsidian Work Log
![owl-logo](attachments/owl-logo.png)
## Introduction
Obsidian Work Log (OWL) is an [Obsidian](https://obsidian.md/) vault template that helps you manage your work. It provides simple, incremental patterns for:
1. Planning your day
2. Organizing your notes
3. Tracking your tasks
## Setup
1. [Download Obsidian](https://obsidian.md/download)
2. Clone this template:
```bash
git clone https://github.com/samhornstein/obsidian-work-log.git
```
3. Open the cloned template [as a vault in Obsidian](https://help.obsidian.md/vault#Open+existing+folder)
## Background
Focusing is:
1. Important for getting work done
2. Hard

OWL helps you focus by providing patterns for prioritizing and planning your days into concentrated periods of work. Specifically, it addresses the following (see links for details):
1. When ([Daily notes](README.md#Daily%20notes))
2. How ([Docs](README.md#Docs))
3. What ([Tasks](README.md#Tasks))

These patterns are implemented as Markdown files and managed with Obsidian features like [daily notes](https://help.obsidian.md/plugins/daily-notes), [internal links](https://help.obsidian.md/links) and [templates](https://help.obsidian.md/plugins/templates).

Everyone works differently, so **feel free to modify this project as you see fit.** You can extend it with additional Obsidian features including [core](https://help.obsidian.md/plugins) and [community](https://obsidian.md/plugins) plugins (see [Additional ideas](README.md#Additional%20ideas)).
## Patterns
### Daily notes
OWL provides a [Daily note template](templates/Daily%20note%20template.md) for planning your days.

Daily notes, for example [2025-10-14](daily-notes/2025-10-14.md), segment your days into [timeboxes](https://en.wikipedia.org/wiki/Timeboxing), which work well with other time management methods like the [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique).

As an example, the [Daily note template](templates/Daily%20note%20template.md) comes with the [properties](https://help.obsidian.md/properties) **quarter**, **week** and **day-of-week** to assist with stand ups and performance reviews.

You can take notes directly within a daily note:
![[2025-10-14#9am-10am]]

Or link to another file:
![[2025-10-14#10am-11am]]

You can even link to a specific header within a file:
![[2025-10-14#11am-12pm]]

In addition to planning, daily notes have the added benefit of tracking your work, useful for activities like billing and progress updates.
### Docs
As shown in [Daily notes](README.md#Daily%20notes), you can link from daily notes to other files. For clarity, these other files will be referred to as **docs**.

Docs provide a focused environment for documenting specific activities. OWL provides a few templates for docs. The [Note template](templates/Note%20template.md) can be used for ad hoc notes, for example [The Answer to the Ultimate Question of Life, the Universe, and Everything](docs/The%20Answer%20to%20the%20Ultimate%20Question%20of%20Life,%20the%20Universe,%20and%20Everything.md). The [Log template](templates/Log%20template.md) can be used for documenting work across multiple days, for example [Major milestone](docs/Major%20milestone.md)
### Tasks
Tasks are managed in [Tasks](Tasks.md). They are simply checklist items, but by using Obsidian's ability to [embed links to a block in a note](https://help.obsidian.md/links#Link+to+a+block+in+a+note), they become a powerful single source of truth for tracking tasks across your vault.

For example, toggle the checkbox in the embedded link below and observe how this change is reflected in [Tasks](Tasks.md):
![[Tasks#^00f181]]

By embedding links to tasks throughout your vault, you ensure updates propagate across all files.

When [Open](Tasks.md#Open) tasks are completed, they can be cut and pasted to [Closed](Tasks.md#Closed). Keeping closed tasks within [Tasks](Tasks.md) maintains any references.

As an example, this project organizes [Closed](Tasks.md#Closed) by year, quarter and week to assist with stand ups and performance reviews.
## Additional ideas
This project is meant to serve as a starting point. Here is a list of ideas to extend its functionality:
1. [Templates](https://help.obsidian.md/plugins/templates)
2. [Properties](https://help.obsidian.md/properties)
3. [Tags](https://help.obsidian.md/tags) (for example #the-answer and #super-important-project/major-milestone )
4. [Hotkeys](https://help.obsidian.md/hotkeys) (OWL comes with two custom hotkeys, `^D` to open today's daily note and `^T` to insert a template)
5. [Bases](https://help.obsidian.md/bases)
6. [Workspaces](https://help.obsidian.md/plugins/workspaces)
