# fm-skills

Mes petits skills, un dossier par skill. Chaque skill est un `SKILL.md` en markdown simple, utilisable avec n'importe quel LLM.

| Skill | Usage |
|---|---|
| `brainstorm` | Brainstorming à partir d'une question ouverte, en amont d'un projet |
| `cadrage` | Cadrage d'un projet métier sur une page, pour aligner l'équipe projet |
| `souvenirs` | Dépôt d'un souvenir de vie quand il remonte, dans un recueil qui grandit avec le temps |

## Installer sur une machine (Claude Code)

```bash
git clone https://github.com/fmaine/fm-skills ~/Desktop/Work/fm-skills
ln -s ~/Desktop/Work/fm-skills/brainstorm ~/.claude/skills/brainstorm
```

Un lien par skill. Puis `/brainstorm` dans une session.

## Avec un autre LLM

D'autres outils d'agents lisent le format `SKILL.md`. Dans un chat web : coller le contenu du `SKILL.md`, puis poser la question.
