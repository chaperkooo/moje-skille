# Moje skille / My skills

🇵🇱 Kolekcja skilli (umiejętności) dla Claude i innych agentów AI. Każdy skill ma swój folder w `skills/` z plikiem `SKILL.md`.

🇬🇧 A collection of skills for Claude and other AI agents. Each skill has its own folder in `skills/` with a `SKILL.md` file.

## Lista / List

| Skill | Co robi / What it does | Źródło / Source |
|-------|------------------------|-----------------|
| [find-skills](skills/find-skills/SKILL.md) | Szuka i instaluje nowe skille ze skills.sh / Finds and installs new skills from skills.sh | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| [ai-video-generation](skills/ai-video-generation/SKILL.md) | Tworzy filmy AI (Veo, Seedance, Wan i inne) przez CLI inference.sh / Makes AI videos (Veo, Seedance, Wan and more) via the inference.sh CLI | [101-skills/superpowers](https://github.com/101-skills/superpowers) |
| [midjourney-prompting](skills/midjourney-prompting/SKILL.md) | Poradnik promptów Midjourney V7/V8.2: budowa promptu, parametry, odniesienia do postaci / Midjourney V7/V8.2 prompt guide: prompt structure, parameters, character references | [mike-coulbourn/claude-vibes](https://github.com/mike-coulbourn/claude-vibes) |
| [book-illustrator](skills/book-illustrator/SKILL.md) | Ilustracje do książek dla dzieci: style wg wieku, kolory, postacie, zasady druku / Children's book illustration: styles by age, color, characters, print rules | [jamesrochabrun/skills](https://github.com/jamesrochabrun/skills) |
| [character-design-continuity](skills/character-design-continuity/SKILL.md) | Ta sama postać na każdym obrazku: biblia postaci, kontrola błędów / Same character in every image: character bible, drift checks | [calesthio/generative-media-skills](https://github.com/calesthio/generative-media-skills) |

## Jak zainstalować / How to install

```bash
npx skills add vercel-labs/skills --skill find-skills
npx skills add 101-skills/superpowers --skill ai-video-generation
npx skills add mike-coulbourn/claude-vibes --skill midjourney-prompting
npx skills add calesthio/generative-media-skills --skill character-design-continuity
npx skills add jamesrochabrun/skills --skill book-illustrator
```

🇵🇱 Uwaga: `ai-video-generation` wymaga konta na inference.sh i programu `belt`.

🇬🇧 Note: `ai-video-generation` needs an inference.sh account and the `belt` CLI.
