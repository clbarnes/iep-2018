# Synapse detection

- Random forest pixelwise membrane/synapse/other predictions
- Pre-process or on request
- Pixel predictions are cached and used for partner assignment

notes:

- Ilastik 2-stage autocontext for predictions
- Ilastik multicut for partner assignment
- Preprocessing the entire larva could take < 2 weeks now that
performance problems are largely resolved
- Partner assignment depends on tracing, but is very quick with
pre-cached pixel predictions (which can also be viewed thanks to H2N5)

Issues:

- Most annotations don't actually mark the synapse
    - Connector edge intersection is not sufficient
    - Segmentation-based
    - Technical limitation in CATMAID has been overcome, making it
    easier to mark the synapse itself
