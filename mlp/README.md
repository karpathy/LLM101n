# MLP
- typically at the start of science, math, or engineering degrees, you come across the matrix muliplication in a linear algebra course. 
this is not the fundamental operation in MLPs, but deep learning as a whole relies heavily on matrix multiplication for most of its operations.
- there are tons of videos on matrix multiplication, but I'll give you a quick rundown here. I also believe that when the intent it to familiarize yourself with a concept and its directly uses, you actually takeaway quite a bit more.

## Architecture
- Matmul
    - input matrix times weight matrix (optionally add bias as an element-wise addition)
- Non-linearity
    - GELU
    - ReLU
    - Sigmoid
    - Tanh
    - ensures the model can capture complex patterns rather than just linear ones
- input -> linear layer (matmul) -> non-linearity -> linear layer -> repeat how ever many times you want -> output
- typically we just go input -> linear -> non-linearity -> linear -> output