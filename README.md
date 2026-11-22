# firma-ai

Společné pracoviště pro Claude Code a Codex. Zadání, návrhy změn, kontroly a stav práce zůstávají v tomto repozitáři.

## Zadat práci

Vytvořte [pracovní úkol](https://github.com/lukaspomp-ui/firma-ai/issues/new?template=task.yml), nebo jej zadejte ve své aktivní relaci Claude či Codexu a požádejte o zaznamenání zde. Uveďte požadovaný výsledek a podle čeho poznáte, že je hotovo.

## Předávání práce

1. Claude nebo Codex převezme konkrétní úkol, přečte `AGENTS.md` a založí vlastní větev.
2. Provede změnu, přiměřeně ji ověří a otevře pull request (PR) propojený s úkolem.
3. Codex zkontroluje PR přes připojení GitHubu. Automatické spuštění závisí na zapnutí kontroly pro tento repozitář a odpovídajícím spouštěči. Kontrolu lze vyžádat komentářem `@codex review`.
4. Autor změny v aktivní relaci přečte skutečný výsledek kontroly, opraví oprávněné připomínky a po změně vyžádá kontrolu nové verze.
5. Výsledek ověření a kontroly zaznamená do PR. Sloučení schvaluje majitel.

Na výsledek kontroly čekejte ve skutečné diskusi PR. Samotné odeslání komentáře není dokončená kontrola.

## Nastavení automatické kontroly

V [nastavení Codex Code Review](https://chatgpt.com/settings/code-review) musí být připojený `lukaspomp-ui/firma-ai`, zapnuté **Review code / Automatic review** a odpovídající osobní **Automatic review / Review trigger**. Postup a ruční vyvolání popisuje [oficiální dokumentace](https://learn.chatgpt.com/docs/third-party/github).

Aktuální ověření tohoto pracoviště a zbývající kroky jsou v [úkolu #1](https://github.com/lukaspomp-ui/firma-ai/issues/1). Text tohoto návodu sám o sobě nastavení nezapíná.

## Provoz

GitHub uchovává stav práce. Kontrola Codexem může po zapnutí běžet na GitHubu podle nastavených událostí; další práce Claude vyžaduje aktivní relaci nebo zvlášť nastavenou automatizaci. Trvale běžící spojení desktopových aplikací ani automatické spouštění Claude zde nastavené není.

Používáme existující účty. Pro toto nastavení nepřidáváme nové placené služby ani API klíče. Spotřeba a limity stávajících předplatných platí nadále.

Repozitář je veřejný. Zadávejte sem jen obsah určený ke zveřejnění; neveřejné podklady ponechte ve svém pracovním prostředí.

Pravidla pro oba agenty jsou v `AGENTS.md`.
