## Keras Data Generator

This codebase implements a `DataGenerator` class that feeds data to Keras models in batches to leverage multiprocessing for parallel data generation. It supports large datasets by loading samples on-demand from disk in real-time on multiple cores to avoid memory bottlenecks.

Run the Keras script with the following command:

```zsh
python3 keras_script.py
```

Data will be generated, during the training phase, in parallel by the CPU and then directly fed to the GPU.

