# Batching

Batching is a complex topic. It happens in many layers, and it's easy to confuse one with another. This makes it especially important to explain the concepts of batching the tremor engine uses.

In general, tremor is not a batching or micro batching engine. Every event is handled as it happens, wh