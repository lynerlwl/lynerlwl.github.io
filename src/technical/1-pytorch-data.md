---
hide:
 - footer
---

We can subclass the `Dataset` class from `torch.utils.data` to customise our data. There are four must-have functions: 
1. __init__: retrieve images path and filename.
2. __len__: return length of dataset.
3. load: This self-define function is to read the image from the machine and convert it to numpy array.
4. __getitem__: run the defined load function and return the files as tensor. Note: the file must be in numpy array for tensor conversion.

 