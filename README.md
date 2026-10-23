# ULU teams

Teams of AI agents shared by people who use [ULU](https://ulu.software), the
desktop app that designs, builds and runs Claude Code agent teams.

Every folder in `teams/` is one team, shared from ULU with the **Share your
team** button, which opens a pull request here.

```
teams/<author>-<team>/
  team.yaml        who shared it, what it is for, its stack
  design.json      the team as a ULU design: agents, steps, skills
  .claude/         the team's agents, skills, commands and workflow
```

## What is never shared

ULU leaves out anything that belongs to the project or to a person: keys and
secret files, `.env*`, `.mcp.json`, `settings.local.json`, agent memory,
the project's own code and docs. The person sees every file before the pull
request is opened.

## Review

A team is merged when it is project-agnostic (no product facts in agents or
skills), has no secrets, and its design passes ULU's check. Good teams can
become ready teams in ULU.

## License

Each team is shared under the MIT license unless its `team.yaml` says
otherwise.
