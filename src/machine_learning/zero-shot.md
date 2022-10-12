# Zero-shot Learning

How do develop Zero-shot model, as a fusion of vision + text task:
    1. Train a supervised model that cover most of the classes in dataset.
    2. Leverage semantic information represent by text, in both train (support that contain labeled data) and test (query that contain unseen data).
    3. Predict on test.