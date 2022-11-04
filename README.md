# Albatross

Description.

## AI features

- Natural language task input?
- Clean up these (meeting) notes
- Encouragements on completion, completion of 5/10/20/50 tasks in one day
- "How should I start this step?" / "Encourage me!" / "Break it into subtasks"

## Development

Like many of my projects, Albatross is built and managed with [Oak](https://oaklang.org/). There's a short [Makefile](Makefile) that wraps common `oak` commands:

- `make` runs the Flask web server, and is equivalent to `flask run`
- `make fmt` or `make f` auto-formats any tracked changes in the repository
- `make build` or `make b` builds the client JavaScript bundle from `src/app.js.oak`
- `make watch` or `make w` watches for file changes and runs the `make build` on any change


