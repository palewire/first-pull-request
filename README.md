How to propose changes to open-source software using GitHub [pull requests](https://docs.github.com/en/pull-requests)


- Documentation: [palewi.re/docs/first-pull-request](https://palewi.re/docs/first-pull-request/)
- Issues: [https://github.com/palewire/first-pull-request/issues](https://github.com/palewire/first-pull-request/issues)

## Contributing to the docs

The documentation for this site is published via [Sphinx](https://www.sphinx-doc.org/en/master/) and written in [Markdown](https://www.markdownguide.org/) files in the [`docs` directory](/docs/).

An edit there followed by push to the master branch on GitHub will trigger the docs being redeployed to [https://palewi.re/docs/first-pull-request/](https://palewi.re/docs/first-pull-request/).

### Running the docs locally

Fork the repository and clone it to your computer. Then enter the directory and install the dependencies with pipenv.

```bash
pipenv install --dev
```

Start the test server.

```bash
make
```

Visit localhost:8000 in your browser and you should see the site. Edits you make in the `/docs/` folder should show up automatically.
