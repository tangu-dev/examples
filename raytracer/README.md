# Raytracer

A Monte Carlo path-tracing renderer based on *Ray Tracing in One Weekend*, supporting Lambertian diffuse, metal, and dielectric glass materials, outputting `scene.png`.

## Run

```sh
tangu run raytracer
```

## Compile & Run (Native)

```sh
tangu compile --target native raytracer
./raytracer/main
```

## Test

```sh
tangu test raytracer
```

## Todo

- Add support for concurrency, multi-threading.
