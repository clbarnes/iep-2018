# Babies and bathwater

1. Brains &rarr; physical connectomes
2. Neurons &rarr; skeletons
3. Synapses &rarr; points
4. Connectivity &rarr; graph

notes:

A great deal of nanoscale connectomic analysis has been based on some or
all of these simplifications.

1. Firstly, we tend to focus on connections we can see in the EM.
This may leave out a wealth of extrasynaptic interactions,
especially neuromodulatory transmitters, which can have profound effects
on a network's behaviour.
2. To speed up the conversion of raw image data to morphological
approximations, neurons are often collapsed down to tree structures
which capture their branching nature and gross morphology, but not
internal features.
3. Again to accelerate reconstruction of circuits, synaptic terminals
 are usually reduced from rich 3D structures into a single point.
4. And finally, those points and trees are collapsed down further into
a connectivity matrix: every neuron is treated as a point, and its 
entire suite of synapses with any given partner as a single value.

All of these dimensionality reductions have value: often understanding
can only really be gained through such incisive models.

Furthermore, connectomes of the scale we have access to today would not
have been possible without these measures.

However, efforts must be made to ensure that the information we are
throwing out is not in itself hiding valuable insights into circuit
function.
