# Soil Biology Weekly

## Find your way in

| If you are… | Start here | Try this |
| --- | --- | --- |
| A grower | [Read the issue worksheet](examples/issue.json) | Separate an observation from an interpretation. |
| An editor | [Inspect the renderer](src/render.py) | See how a sourced Friday brief is assembled. |
| A contributor | [Explore the project tree](docs/DIRECTORY.md) | Suggest one clearer sentence using fictional field notes. |

[Complete repository directory tree](docs/DIRECTORY.md)

## A Friday note worth revisiting next Friday

The best soil question is often small enough to come back to. A keeper can record how a bed looked after watering, then discover a week later that their first explanation was too simple. Good field writing leaves room for that second observation.

The [issue worksheet](examples/issue.json) separates the question, dated observation and source. The [renderer](src/render.py) turns that structure into a readable brief. This is the editorial kit; a filled-in template is not evidence of a published issue or a measured change in the soil.

Take a fictional field note and underline the part another person could actually see. Put the interpretation on a separate line and name the next observation that could change it. A useful edit fixes one sentence and explains why.

**Editorial research kit.** Translate one observable living-soil question into a sourced, readable Friday brief.

### Setup and usage

Python 3.10 or newer. The project uses the standard library.

```sh
python3 src/render.py examples/issue.json
```

Submit one reviewed field question. Work from an identified observation, a named source and its limits. Obtain consent before quoting a reader or including a grow photograph.

### Developer entry points

A structured issue template links a grower's observation, a published source and the limits of the interpretation. Readers can compare it with the next dated observation. Explore `examples/`, `src/`, `tests/` in the full tree.

### Verification

The commands below ran in a clean test context using local files and fixtures.

```sh
python3 -m unittest discover -s tests
```

### Release scope

This release provides the editorial starter. A complete reviewed issue archive was not located in the selected sources. Founder brief for the recurring Friday Soil Biology Weekly series. The issue template and renderer are newly authored. No historical issue or empirical result is reproduced.

[Technical whitepaper](docs/WHITEPAPER.md) · [Marketing and sales plan](docs/MARKETING.md) · [Dated developer log](docs/BUILD-LOG.md)

Existing asset and code terms remain applicable. Public access to a recording, illustration, brand or manuscript does not itself grant commercial reuse rights.
