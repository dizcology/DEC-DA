This is a wrapper around the DEC-DA code open sourced by Xifeng Guo at [https://github.com/XifengGuo/DEC-DA](https://github.com/XifengGuo/DEC-DA), making it an installable package.  Refer to the source for more information.


### Changes from the source:

1. L2-normalize the embedding.

1. Default to `alpha = 100.0`.

1. Use `predict_on_batch`, since `predict` seems to fail to release memory.
