# catpy

- Formalised python interface for CATMAID
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