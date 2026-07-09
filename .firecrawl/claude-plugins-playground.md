[Skip to content](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground#start-of-content)

You signed in with another tab or window. [Reload](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground) to refresh your session.You signed out in another tab or window. [Reload](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground) to refresh your session.You switched accounts on another tab or window. [Reload](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground) to refresh your session.Dismiss alert

{{ message }}

[anthropics](https://github.com/anthropics)/ **[claude-plugins-official](https://github.com/anthropics/claude-plugins-official)** Public

- [Notifications](https://github.com/login?return_to=%2Fanthropics%2Fclaude-plugins-official) You must be signed in to change notification settings
- [Fork\\
1.1k](https://github.com/login?return_to=%2Fanthropics%2Fclaude-plugins-official)
- [Star\\
10.7k](https://github.com/login?return_to=%2Fanthropics%2Fclaude-plugins-official)


## Collapse file tree

## Files

main

Search this repository

/

# playground

/

Copy path

## Directory actions

## More options

More options

## Directory actions

## More options

More options

## Latest commit

[![claude](https://avatars.githubusercontent.com/u/81847?v=4&size=40)](https://github.com/claude)[claude](https://github.com/anthropics/claude-plugins-official/commits?author=claude)

[Add Apache 2.0 LICENSE files to all internal plugins](https://github.com/anthropics/claude-plugins-official/commit/aecd4c852f10b466245f18383fa6aad8c0b10d57)

Open commit detailssuccess

3 weeks agoFeb 19, 2026

[aecd4c8](https://github.com/anthropics/claude-plugins-official/commit/aecd4c852f10b466245f18383fa6aad8c0b10d57) · 3 weeks agoFeb 19, 2026

## History

[History](https://github.com/anthropics/claude-plugins-official/commits/main/plugins/playground)

Open commit details

[View commit history for this file.](https://github.com/anthropics/claude-plugins-official/commits/main/plugins/playground) History

/

# playground

/

Top

## Folders and files

| Name | Name | Last commit message | Last commit date |
| --- | --- | --- | --- |
| ### parent directory<br> [..](https://github.com/anthropics/claude-plugins-official/tree/main/plugins) |
| [.claude-plugin](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground/.claude-plugin ".claude-plugin") | [.claude-plugin](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground/.claude-plugin ".claude-plugin") | [Rename artifact plugin to playground](https://github.com/anthropics/claude-plugins-official/commit/4e459fbe7425a1880142a1b919cd62d719f657f4 "Rename artifact plugin to playground") | 2 months agoJan 29, 2026 |
| [skills/playground](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground/skills/playground "This path skips through empty directories") | [skills/playground](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground/skills/playground "This path skips through empty directories") | [Rename artifact plugin to playground](https://github.com/anthropics/claude-plugins-official/commit/4e459fbe7425a1880142a1b919cd62d719f657f4 "Rename artifact plugin to playground") | 2 months agoJan 29, 2026 |
| [LICENSE](https://github.com/anthropics/claude-plugins-official/blob/main/plugins/playground/LICENSE "LICENSE") | [LICENSE](https://github.com/anthropics/claude-plugins-official/blob/main/plugins/playground/LICENSE "LICENSE") | [Add Apache 2.0 LICENSE files to all internal plugins](https://github.com/anthropics/claude-plugins-official/commit/aecd4c852f10b466245f18383fa6aad8c0b10d57 "Add Apache 2.0 LICENSE files to all internal plugins  - Added Apache 2.0 license to the root of each plugin directory - Ensures compliance with open-source licensing requirements") | 3 weeks agoFeb 19, 2026 |
| [README.md](https://github.com/anthropics/claude-plugins-official/blob/main/plugins/playground/README.md "README.md") | [README.md](https://github.com/anthropics/claude-plugins-official/blob/main/plugins/playground/README.md "README.md") | [Rename artifact plugin to playground](https://github.com/anthropics/claude-plugins-official/commit/4e459fbe7425a1880142a1b919cd62d719f657f4 "Rename artifact plugin to playground") | 2 months agoJan 29, 2026 |
| View all files |

## [README.md](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground\#readme)

Outline

# Playground Plugin

[Permalink: Playground Plugin](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground#playground-plugin)

Creates interactive HTML playgrounds — self-contained single-file explorers that let users configure something visually through controls, see a live preview, and copy out a prompt.

## What is a Playground?

[Permalink: What is a Playground?](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground#what-is-a-playground)

A playground is a self-contained HTML file with:

- Interactive controls on one side
- A live preview on the other
- A prompt output at the bottom with a copy button

The user adjusts controls, explores visually, then copies the generated prompt back into Claude.

## When to Use

[Permalink: When to Use](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground#when-to-use)

Use this plugin when the user asks for an interactive playground, explorer, or visual tool for a topic — especially when the input space is large, visual, or structural and hard to express as plain text.

## Templates

[Permalink: Templates](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground#templates)

The skill includes templates for common playground types:

- **design-playground** — Visual design decisions (components, layouts, spacing, color, typography)
- **data-explorer** — Data and query building (SQL, APIs, pipelines, regex)
- **concept-map** — Learning and exploration (concept maps, knowledge gaps, scope mapping)
- **document-critique** — Document review (suggestions with approve/reject/comment workflow)

## Installation

[Permalink: Installation](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/playground#installation)

Add this plugin to your Claude Code configuration to enable the playground skill.

You can’t perform that action at this time.