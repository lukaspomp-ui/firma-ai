# firma-ai

Společné pracoviště pro Clauda (Claude Code) a Codex (OpenAI).

## Jak to funguje

1. Lukáš zadá úkol Claudovi (claude.ai/code).
2. Claude udělá práci ve vlastní větvi a otevře pull request.
3. Codex pull request automaticky zkontroluje a napíše připomínky.
4. Claude připomínky opraví (nebo Lukáš napíše `@codex fix …` a opraví je Codex).
5. Lukáš schválí a sloučí hotový výsledek.

Pravidla pro oba agenty jsou v `AGENTS.md`.
