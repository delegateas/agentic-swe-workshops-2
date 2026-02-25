# Agents, MCP & Skills

En praktisk workshop hvor vi udforsker den nye verden af agentic software engineering.

En konsulent fra Context& guider jer igennem arkitekturen bag agents, Model Context Protocol (MCP) og Skills – med hands-on øvelser i hvert modul.

## Agenda (ca. 3,5 timer)

| Tid | Emne | Øvelser |
|-----|------|---------|
| 20 min | Intro, Recap & Polyglot Notebooks | |
| 70 min | Agenter - teori og byg din egen | **Øvelse 1:** Tool Execute-funktioner, **Øvelse 2:** Human-in-the-loop |
| 20 min | *Pause* | |
| 45 min | Abstraktionsstigen – MCP | **Øvelse 3:** AIFunction Tools |
| 20 min | Extension: get_nearest_station | **Øvelse 4:** Nyt tool |
| 25 min | Skills – teori og prøv med GitHub Copilot | SKILL.md |
| 10 min | Afrunding | |

## Forberedelse

Installer venligst inden workshoppen:

- VS Code
- Polyglot Notebooks extension (men .NET Extension Pack er nemmest)
- .NET 9 SDK (påkrævet for OllamaSharp 5.x)
- **Ollama** – lokal LLM inference
  - Installer: `winget install Ollama.Ollama`
  - Download model: `ollama pull llama3.1:8b`
  - Verificer: `ollama list` (skal vise llama3.1:8b)
- GitHub Copilot (NB. Ikke påkrævet.)

## Domæne

Vi arbejder med et fiktivt EV-ladenetværk som case.
