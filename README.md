# Python Packaging Essentials

The aim of this site it to provide all the must known practices when it comes to create a Python package. It offers **multiple blog posts**, where each of them covers one topic with a few key points. The goal here is to empower anyone with just basic Python knowledge.

The site is live [here](#)

<br><br>

### Progress

| Post                  | Section          | State |
| --------------------- | ---------------- | ----- |
| Intro to packaging    | Create a package | ✅    |
| Organize a package    | Create a package | ✅    |
| Handling dependencies | Create a package | ✅    |
| Unit tests            | Code quality     | ❌    |
| Writing documentation | Code quality     | ❌    |
| Errors and warnings   | Code quality     | ❌    |
| API design            | Code quality     | ❌    |
| Github Actions        | Workflow         | ✅    |
| Pre-commit hooks      | Workflow         | ✅    |
| Publish to PyPI       | Workflow         | ❌    |

<br><br>

### Build from source

### Set up environment

In order to follow the steps below, you'll need to have both [Git](https://git-scm.com/downloads), [uv](https://docs.astral.sh/uv/getting-started/installation/) and [Quarto](https://quarto.org/) installed on your machine.

- Fork the [Github repo](https://github.com/yellow-sunflower/python-packaging-essentials/)
- Git clone it:

```bash
git clone https://github.com/YourUsername/python-packaging-essentials.git
```

- Create a new Git branch

```bash
git checkout -b branch-name
```

- Set up your environment

#### MacOS/Unix-like

```bash
uv python install
uv sync
source .venv/bin/activate
```

#### Windows

```bash
uv python install
uv sync
.venv\Scripts\activate
```

### Make changes

Each blog post lives in a Quarto file (`.qmd`). It's a mix of markdown and chunk of code.

You can preview locally your changes with:

```bash
quarto preview
```

If not done automatically, open your browser at [http://localhost:4000/](http://localhost:4000/)
