# Install — FROM Reverse Engineer skill

Copy the included `.agents` directory into the **root of the Project FROM Git repository**:

```text
your-from-repo/
├── .agents/
│   └── skills/
│       └── from-reverse-engineer/
│           ├── SKILL.md
│           ├── agents/
│           │   └── openai.yaml
│           └── references/
│               └── conversation-calibration.md
├── AGENTS.md
├── CURRENT_STATE.md
└── ...
```

Codex scans repository-local skills under `$REPO_ROOT/.agents/skills`.

### Explicit invocation

In Codex CLI / IDE you can explicitly invoke it with:

```text
$from-reverse-engineer
```

Then write, for example:

```text
S01E10 - ето какво забелязах...
```

The skill also allows implicit invocation, so a normal FROM episode message should match its description.

### Recommended first run

```text
$from-reverse-engineer
Read the repository state first. Continue our FROM discussion in Bulgarian.
Treat the repo as durable memory, keep the spoiler cutoff absolute, analyze my
observations conversationally first, and then ask whether to update the repo.
```

### Important

Do not paste future plot summaries into the repository. The skill is designed to make the repo itself the durable memory of the analysis while the watched episode cutoff acts as a hard spoiler boundary.
