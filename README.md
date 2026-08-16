# AAA_2026
Welcome to the repository of the course "Advanced Analytics and Applications (AAA)" in Summer Semester 2025. We will use this space as the central point for sharing code, data and instructions with you over the course of this semester.

You should check this repo regularly to view and/or download newly released or updated files. If you have experience using git or if you want to learn how to work with a state-of-the-art version control system, you may wish to fork and regularly pull updates to the repository onto your local machine for convenience.

To get up and running with the code, please install [`uv`](https://docs.astral.sh/uv/) which we use for dependency management in this repository. Think of it like `conda` or `pip`, but cooler 😎. Then, simply run 

```bash
uv sync
```

which will create a `.venv` virtual environment in your working directory. VSCode and other IDEs usually automatically pick that up.
If you want to run a local Jupyter Lab instance, you can do so with `uv run jupyter lab` which will also automatically use your project's environment.

A good first stop for all questions that are not subject-related but relate to how to use these kinds of tools you can have a look here (and request new guides by using issue templates): [IS3 Teaching Repository](https://github.com/IS3UniCologne/teaching-material)
