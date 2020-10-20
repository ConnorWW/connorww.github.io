## Intro

Hello! My name is Connor Weisenberger, and this is a simple markdown document detailing some of the projects I've worked on. I'm going to do my best to have my most recent projects at the top.

## Spark Distributed Ray Tracer

Viewable at: [Spark Ray Tracer](https://github.com/MarkCLewis/SparkRayTracer)

This project was the creation of a small team including myself, Dr. Mark C. Lewis, and Erica Cater. The motivation for the project came in the form of a request from a museum observatory for a rendering of a large section of Saturn's rings. Thus, the primary goal of this research was to accomodate this request. The data for the original museum rendering had to be tiled together, as the data was too large to fit within the memory of a single machine. Distribution could also benefit speed, but this is not our explicitly desired result. We are specifically looking to allow the ray tracing of scenes with more geometry than can fit within the memory of a single machine.

To do this, we leveraged an iterative development model.

# Renderer 1!

