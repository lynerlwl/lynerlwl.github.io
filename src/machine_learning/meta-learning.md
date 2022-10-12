# Meta-Learning

Mata is one level of abstraction above.
    - Meta-data (data about data) is data that provides information about data.
    - Meta-learning (learning about learning) is learning how to learn.

Meta-learning is about 
    1. learning to learn 
    2. learning something that you usually don't directly learn (e.g. the hyperparameters), where learning is roughly a synonym for optimization.

As an example, in the context of binary image classification:
    - Supervised learning is learning to classify an image.
    - Meta-learning is learning how to classify an image, which learn the concept of classification rather than the task.

Learning by:
    - *Examples*: Supervised / Unsupervised.
    - *Experience*: Reinforcement.
    - *Learning*: Meta.

Where do meta-learning fit in ML pipeline? As common steps of ML:
    1. Data Preparation.
    2. Model Definition. *Meta-learning automate this.*
    3. Training / Fine-tuning.
    4. Optimization.
    5. Deployment / Run.

We can use meta-learning with other ML algorithm. We show lots of datasets to learn a concept. Output of meta-learning algorithm is a ML model. We can say meta-learning is a ML algorithms that learn from the output of other ML algorithms.

**Meta-learning algorithms** refer to
    - ensemble learning algorithms.
    - algorithms that learn how to learn accross a suite of related prediction tasks [multi-task learning].


MAML: find the best _ algorithm that generalize to any _ task.

