# Soil Biology Weekly

[Complete repository directory tree](docs/DIRECTORY.md)

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
