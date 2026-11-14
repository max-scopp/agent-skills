# Agent Skills

Personal agent skills for the Zed editor / GitHub Copilot, kept in `~/.agents/skills`
and synced across machines via this repository.

## Restore on a new machine

```bash
git clone https://github.com/max-scopp/agent-skills.git ~/.agents/skills
```

## Skills

| Skill | Purpose |
| ----- | ------- |
| [aspire](aspire/SKILL.md) | .NET Aspire: CLI, AppHost orchestration, service discovery, integrations, MCP server, dashboard, deployment |
| [aspnet-minimal-api-openapi](aspnet-minimal-api-openapi/SKILL.md) | ASP.NET Minimal API endpoints with proper OpenAPI documentation |
| [containerize-aspnetcore](containerize-aspnetcore/SKILL.md) | Dockerfile + .dockerfile customized for ASP.NET Core projects |
| [containerize-aspnet-framework](containerize-aspnet-framework/SKILL.md) | Dockerfile + .dockerfile customized for ASP.NET (.NET Framework) projects |
| [csharp-async](csharp-async/SKILL.md) | C# async programming best practices |
| [csharp-docs](csharp-docs/SKILL.md) | XML doc comments and documentation best practices |
| [csharp-mstest](csharp-mstest/SKILL.md) | MSTest 3.x/4.x unit testing best practices |
| [csharp-xunit](csharp-xunit/SKILL.md) | xUnit unit testing best practices, including data-driven tests |
| [dotnet-best-practices](dotnet-best-practices/SKILL.md) | .NET/C# code best-practices checks |
| [dotnet-design-pattern-review](dotnet-design-pattern-review/SKILL.md) | Design pattern implementation review with suggestions |
| [dotnet-timezone](dotnet-timezone/SKILL.md) | .NET timezone handling (TimeZoneInfo, DateTimeOffset, NodaTime, cross-platform IDs) |
| [dotnet-upgrade](dotnet-upgrade/SKILL.md) | .NET upgrade analysis and execution prompts |
| [ef-core](ef-core/SKILL.md) | Entity Framework Core best practices |
| [fluentui-blazor](fluentui-blazor/SKILL.md) | Microsoft Fluent UI Blazor component library guide |
| [i-have-adhd](i-have-adhd/SKILL.md) | Shapes output for a reader with ADHD (invoke with `/i-have-adhd`) |
| [microsoft-code-reference](microsoft-code-reference/SKILL.md) | Microsoft API reference lookups and working code samples |
| [microsoft-docs](microsoft-docs/SKILL.md) | Microsoft Learn docs, tutorials, and code examples |
| [noob-mode](noob-mode/SKILL.md) | Plain-English translation for non-technical CLI users |
| [nuget-manager](nuget-manager/SKILL.md) | NuGet package management with the dotnet CLI |
| [premium-frontend-ui](premium-frontend-ui/SKILL.md) | Immersive, high-performance web UI craftsmanship |
| [tldr-prompt](tldr-prompt/SKILL.md) | tldr summaries for prompts, agents, MCP servers, and docs |
| [web-design-reviewer](web-design-reviewer/SKILL.md) | Visual website inspection to find and fix design issues |

## Notes

- Each skill lives in its own directory with a `SKILL.md` (front matter: `name`, `description`).
- Skills with extra material keep it in a `references/` subfolder next to `SKILL.md`.
