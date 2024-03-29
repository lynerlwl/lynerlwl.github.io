# Terms

[**Artificial intelligence**](http://www-formal.stanford.edu/jmc/whatisai/) is the science and engineering of making intelligent machines, especially intelligent computer programs. 

**Intelligence** is the ability of a system to acquire and process information.(黄铁军, 科学之路 - 序言)

**Learning** is the process of gradually reducing systematic errors. (黄铁军, 科学之路 - 序言)

[**Metadata**](https://en.wikipedia.org/wiki/Metadata) is "data that provides information about other data", but not the content of the data.

[**Backpropagation**](https://brilliant.org/wiki/backpropagation/), short for "backward propagation of errors" is an algorithm for supervised learning of artificial neural networks using gradient descent.

[**Latent space**](https://en.wikipedia.org/wiki/Latent_space), also known as a **latent feature space** or **embedding space**, is a vector space spanned by the latent variables. Latent variables are variables which are not directly observable.
- Position within the latent space can be viewed as being defined by a set of latent variables that emerge from the resemblances from the objects.
-  The construction of a latent space is an example of dimensionality reduction, which can also be viewed as a form of data compression.

[**Manifold**](https://en.wikipedia.org/wiki/Manifold) is a topological space that locally resembles Euclidean space near each point.
- One-dimensional manifolds include lines and circles, but not lemniscates.
- Two-dimensional manifolds are also called surfaces. Examples include the plane, the sphere, and the torus, and also the Klein bottle and real projective plane.

[**Topological space**](https://en.wikipedia.org/wiki/Topological_space) is a geometrical space in which closeness is defined but cannot necessarily be measured by a numeric distance.

[**Topology**](https://en.wikipedia.org/wiki/Topology) is a structure allows defining continuous deformation of subspaces, and, more generally, all kinds of continuity.
Topology studies how a shape or object is connected.

If we have a notion of distance then we can say when things are close to each other. However, distance is not necessary to determine when things are close to each other.

[**Invariant**](https://en.wikipedia.org/wiki/Invariant_(mathematics)) is a property of a mathematical object remains unchanged after certain operations.

A binary operation is **commutative** if changing the order of the operands does not change the result.

Compositionality 组合性

Stationarity 平稳性 is a properties of unconditional joint probability distribution does not change when shifted in time.

Translation mean each point/pixel in the image has been moved the same amount in the same direction.

Region in an image is a group of connected pixels with similar properties.

An **adjacent** vertex of a vertex v in a graph is a vertex that is connected to v by an edge.

**Symmetry group** of a geometric object is the group of all transformations under which the object is invariant, endowed with the group operation of composition. 

[**Message passing**](https://neurips.cc/virtual/2021/tutorial/21897) algorithms are distributed algorithms that operate on graphs, where each node uses only information present locally at the node and incident edges, and send information only to its neighbouring nodes. 

Representation learning transform raw data into suitable internal representation.

**Computation geometry** is a geometry in extracting useful information from physical shapes tiled with polygons on visual scenes.

**Computational topology** useful in establishing the nearness or apartness of nonempty sets of **cell complexes** (connected vertices, edges and filled triangles). 

cellular complexes (collections of vertices, line segments, filled triangles, cycles, vortexes, nerves)

**Homology** focuses on how space is connected that provide insights into how the pieces of a visual scene can be connected to each other.

**Group** $G$ is a nonempty set equipped with a binary operation * that is associative and in which there is an identity element e and every member a in G has an inverse b, i.e., a * b = e.

**Cyclic group** H is a group in which every member of G can be written as a positive integral power of a single element called a **generator**. Cyclic groups are useful in representing how the pieces of a visual scene that are attached to each other and connected together.

Cyclic group is **Abelian**, provided a * b = b * a, for every pair elements in G.

**Free abelian group** is an Abelian group with multiple generators

**Betti numbers** counts of the number of generators in a free Abelian group.

**Hausdorff space** is a nonempty set in which every point resides in a neighbourhood that is disjoint from every other neighbourhood of the points in the space.

**Contours** is a curve joining all the continuous points (along the boundary)having same color or intensity. 

**Structure** means some meaningful collection of the parts of an image \cite{peters2014topology}.

**Collection** connotes a grouping the pixels in an image based on some scheme \cite{peters2014topology}.

**Feature** is a piece of information about the content of an image.

[**Spatial relation**](https://en.wikipedia.org/wiki/Spatial_relation) specifies how some object is located in space in relation to some reference object.

A region in an image is a group of connected pixels with similar properties.

Compression ~ Dimension Reduction ~ Cell Collapsing

Fine & coarse segmentation

pixel also picture element

Global modeling is a machine learning approach that aims to learn models that can make predictions based on the entire input, rather than just a local patch or region of the input. 

Convolution in a CNN is performed by sliding a small window or kernel across the input and applying a set of weights to the values within the window to produce a new output value. This process is repeated for each location in the input, and the resulting outputs are combined to form a new feature map.

Contrastive learning is a machine learning approach that aims to learn representations of data that are robust to variations in the data. This is typically achieved by training a model to maximize the similarity between similar examples in the dataset and minimize the similarity between dissimilar examples.

Long-range context relationships refer to the relationships between elements in a dataset that are distant from each other in terms of their position or location. In an image, long-range context relationships may involve the relationships between pixels that are far apart from each other in the image.

Feature pyramid is a multi-scale feature extractor that is used to extract features from the input image at multiple scales.

how is affinity matrix related
- An affinity matrix is a matrix that represents the relationships or connections between elements in a dataset. In the context of image segmentation, an affinity matrix is often used to represent the relationships between pixels in an image, with each element in the matrix representing the similarity or "affinity" between a pair of pixels.
- The affinity matrix can be used in a variety of ways in the context of image segmentation. For example, it can be used to define the edges of a graph that represents the image, with the elements of the affinity matrix defining the weights of the edges. The affinity matrix can then be used to compute the graph Laplacian, which can be used to smooth or regularize the image.
- The affinity matrix can also be used to compute the pairwise distances between pixels in the image, which can be used to define the similarity between pixels. This similarity can then be used to cluster the pixels into different groups or regions, which can be useful for tasks such as image segmentation or object detection.

A walk in a graph is a sequence of edges that connects a sequence of vertices. It can start and end at different vertex, and a vertex may be visited more than once. The order in which the vertices and edges are traversed is important. A walk can be open, if it starts and ends at different vertex, or closed, if it starts and ends at the same vertex.

Pyramid method is a technique used to reduce the resolution of an image while retaining important details. The pyramid method involves creating a series of images of the same scene, each at a lower resolution than the previous one. This is typically done by repeatedly applying a smoothing filter and then downsampling the image. The resulting images form a pyramid, with the original image at the top, and each successive level of the pyramid having a lower resolution.

In image processing, the Non-local algorithm is used to improve the quality of images that have been degraded by noise or other distortions. It does this by considering the similarity of each feature position to all other feature positions in the image.

