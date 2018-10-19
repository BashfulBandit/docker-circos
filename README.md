# docker-circos

This is the Git repo of a Docker image for [circos](http://circos.ca/). 

## What is circos?

Circos is a software package for visualizing data and information. It visualizes data in a circular layout — this makes Circos ideal for exploring relationships between objects or positions. There are other reasons why a circular layout is advantageous, not the least being the fact that it is attractive.

Circos is ideal for creating publication-quality infographics and illustrations with a high data-to-ink ratio, richly layered data and pleasant symmetries. You have fine control each element in the figure to tailor its focus points and detail to your audience. 

[Source](http://circos.ca/)

## Usage

```console
$ docker run -it -v $(pwd)/example:/home/circos/input dtempleton/circos:latest
```

This will present you with a bash terminal inside the Docker container to run your circos command.

## Contributors

* [Oliver Grant](https://github.com/gitoliver) - Provided the example.
