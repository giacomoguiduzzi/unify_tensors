# unify_tensors
Tiny package to implement a safety function that moves all the tensors passed to the same device. Useful when a part of a big model has been offloaded and there's a risk of a runtime error because of tensors on different devices.
