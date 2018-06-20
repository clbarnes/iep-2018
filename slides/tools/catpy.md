# catpy

- Formalised python interface for CATMAID, `pip`-installable
- Documentation available at [catpy.readthedocs.io](https://catpy.readthedocs.io/en/latest/)

```python
from catpy import CatmaidClient

catmaid = CatmaidClient(
    "https://mycatmaidserver.org",
    "mYaP1t0k3nStR1nG",
    project_id=1
)

catmaid.get(
    (catmaid.project_id, "connectors", "links"),
    {"skeleton_ids": [11524047]}
)
```

notes:

- I am primary maintainer
- Allows interaction with CATMAID API and popular image stacks
- Allows reproducible, readable, portable analysis of data
- Installable with one line; designed for extensibility
