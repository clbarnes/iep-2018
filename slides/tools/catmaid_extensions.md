# CATMAID extensions

- Foundation of a CATMAID plugin ecosystem
- Drastically reduces barrier to entry for others and burden on core developers
- Documentation available with the [CATMAID docs](https://catmaid.readthedocs.io/en/stable/extensions.html)

```bash
cookiecutter gh:clbarnes/CATMAID-ext-cookiecutter
...
pip install CATMAID-myextension
```

notes:

- developers can add their own database tables, widgets, API endpoints
- single-line change to core CATMAID required
- less maintenance for core developers
- less complexity for other users who don't need that functionality

Semi-automatic neurite tracing spearheaded by Andrew Champion and
now being implemented by Will Patton will likely be using this system.
