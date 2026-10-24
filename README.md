[CUDA for LLMs MEAP](https://www.manning.com/books/cuda-for-llms?continue) + press button "look inside"

- PyTorch: the standard library most deep learning code is built on.
- Hugging Face Transformers: the library most people use on top of PyTorch to load and run popular models.
- Popular models: Llama or GPT-style architectures.


In CUDA programming, you're always working with two separate computing environments that you must coordinate:
- Host: your CPU and its associated system memory (RAM). This is where your main program runs and where you manage the application flow
- Device: your GPU and its dedicated video memory (VRAM). This is where the parallel magic happens
- VRAM: The hardware architecture was built to accelerate graphics, with thousands of simple cores for parallel processing, is perfect for the massive, parallel computations required to train and run neural networks. So, the "Video" RAM became the workhorse for AI.

- MLP: Multi Layer Perceptron. Neural network with an input layer, one or several hidden layers and an output layer. The 'hello, world' of neural networks
- MNIST: Modified National Institute of Standards and Technoloy. Refers to the normalized dataset with 70000 handwritten digits 0-9
