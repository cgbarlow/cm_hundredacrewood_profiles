# Hundred Acre Wood — Campaign Mode Profiles

A complete set of [Campaign Mode](https://github.com/cgbarlow/campaign-mode) character profiles that skin all nine agents as Winnie the Pooh characters. Drop them into any Campaign Mode project to turn your quest into a Hundred Acre Wood adventure.

## Characters

### Animal Agents (Six Animals)

| Archetype | Character | Profile | Role |
|-----------|-----------|---------|------|
| Bear | **Pooh** | [bear.md](.campaign/profiles/bear.md) | Vision and direction — finds the heart of things with warm simplicity |
| Cat | **Eeyore** | [cat.md](.campaign/profiles/cat.md) | Risk assessment — sees what could go wrong before anyone else does |
| Owl | **Owl** | [owl.md](.campaign/profiles/owl.md) | Timeline and process — insists on proper procedure (with digressions) |
| Puppy | **Tigger** | [puppy.md](.campaign/profiles/puppy.md) | Morale and momentum — boundless enthusiasm that's infectious |
| Rabbit | **Rabbit** | [rabbit.md](.campaign/profiles/rabbit.md) | Resources and stakeholders — the practical organiser who keeps lists |
| Wolf | **Piglet** | [wolf.md](.campaign/profiles/wolf.md) | Team cohesion — small and anxious, but the heart of the group |

### NPC Agents (Campaign Mode)

| Archetype | Character | Profile | Role |
|-----------|-----------|---------|------|
| Gandalf | **Christopher Robin** | [gandalf.md](.campaign/profiles/gandalf.md) | Mentor — guides without rescuing, believes in you more than you believe in yourself |
| Guardian | **Kanga** | [guardian.md](.campaign/profiles/guardian.md) | Gatekeeper — won't let you rush ahead until you're properly ready |
| Dragon | **Heffalump** | [dragon.md](.campaign/profiles/dragon.md) | Adversary — looming and thorough, but the test is fair |

## Installation

Copy the `.campaign/profiles/` directory into your project's `.campaign/` folder:

```bash
cp -r .campaign/profiles/ /path/to/your/project/.campaign/profiles/
```

Campaign Mode agents will automatically detect the profiles and adopt their Hundred Acre Wood personas.

## Origin

These profiles were created during a Campaign Mode quest exploring how to teach D&D to a newcomer by casting Pooh characters as a D&D party. The quest itself lives in [quest.md](.campaign/quest.md).

## Requirements

- [Campaign Mode](https://github.com/cgbarlow/campaign-mode) installed in your Claude Code environment
