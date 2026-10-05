# service-cog-vsk-mesh-optimizer

A container predictor that simplifies a binary glTF model with meshoptimizer's packer and returns the smaller file.

## What it is for

It takes a `.glb`, simplifies and quantizes it, and returns the result, so models arrive with fewer triangles and smaller buffers. The scale and error targets are inputs of the predictor.

## Build and run

```sh
cog predict -i model_file=@model.glb
```

## Licence

MIT; see `LICENSE`.
