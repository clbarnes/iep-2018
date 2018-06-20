# Partner classification

- False positive rate of synapse-skeleton associations is high
- Synapse and partner detections are undirected

notes:

Using this pixelwise methodology, no distinction is made between the pre- and post-synaptic side,
leaving us with an undirected synapse,
which is an impediment to its utility in automated reconstruction of circuits.
There are also a lot of false positives in the synapse-skeleton association
as membranes adjacent to the synapse tend to be included.

I made an attempt to address this with a post-processing step:
I wanted something which would run pretty quickly, without having to generate too much extra data
like extra ilastik projects etc.

This was a short-term effort, so I used an existing implementation of a neural network known to
generalise well to image classification tasks, the ResNet.

Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. Deep residual learning for image recognition.
CoRR, abs/1512.03385, 2015.
