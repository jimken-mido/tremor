---
sidebar_position: 0
---

# Tremor

Think about Tremor as an event- or stream-processing engine. It receives input data from various [Connectors], turns the data into streams of structured events with the help of [Preprocessors](reference/preprocessors) and [Codecs]. Those events are then handled by one or more [Pipelines](language/pipelines), which can inspect, mutate and route the event and implement arbitrarily complex application logic. Events are either dropped (e.g. for rate-limiting or traffic-shaping) or sent to downstream systems via various [Connectors]. Before actually leaving the system, those streams of structured events need to be serialized using [Codecs] and [Postprocessors](reference/postprocessors).
