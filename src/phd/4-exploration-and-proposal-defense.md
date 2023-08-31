---
hide:
 - footer
---

# Exploration and Proposal Defense

In my PhD, I am working on representation learning. I find a way to represent an image as a graph for semantic segmentation. Image is the RGB or grayscale picture we can view on our computer. The graph here is not the visualisation chart but a structure comprising node and edge. Semantic segmentation is an image segmentation that separates the foreground (object) and the background into a semantic category (like human and sky).

Usually, an image is represented as a grid of pixels on the computer. In dealing with images, the go-to technique is a convolutional network. So, I trained a convolutional model to segment the liquid spray images. The model works as it finds the corresponding objects in the image. However, from the predicted result, I see some false contouring, which will falsely increase the number of objects in the image. This false increase in the number of predicted objects will mess up the decision of whether to service an engine that the spray comes out from.

Through a few readings, I realise that convolution in grid representation will cause topological errors. Then I thought, if I change the image representation, will the problem be resolved? Motivated by how humans recognise an object in a scene, I believe using a graph to represent an image is promising. I will need to work on my first-year defence writing (proposal defence), so I didn't manage to run an experiment to prove that. You might wonder why it sounds like I need a long time for that. The thing is, IT IS. 

You realise what you missed when writing. We do not learn from the research paper on learning a new concept. We identify the gap and trend from the article, then learn the fundamentals from the textbook. Learning takes time, quite some time. Why so? If you know a bit of something, then quickly go to the next concept. What's the implication? It will cause a learning gap, a serious problem we must solve. For example, we know 80% of Concept 1 and then learn Concept 2. That missing 20% is crucial to understanding Concept 2.

Let's talk about the proposal defense. At this stage, the proposal differs from the document you submitted for PhD admission. This proposal is the draft thesis of chapters one to three (Introduction, Literature Review, and Methodology). You must showcase your problem and hypothesis to convince others that your research direction is clear. It is best to do your preliminary experiment at least to validate the research hypothesis. Usually, 20 minutes will be given to present your proposal. Remember, you must tell a story to convince others that your direction is firm. Writing thesis is NOT the same as writing article, thought both are a kind of report. Thesis is meant for everyone to read, have to write clearly. Article is for expert to get the latest update.