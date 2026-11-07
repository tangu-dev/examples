# Mandelbrot

An example Mandelbrot fractal renderer generating `mandelbrot.png`.

## Run

```sh
tangu run mandelbrot
tangu run mandelbrot 256
```

## Test

```sh
tangu test mandelbrot
```

## Region Presets

```tangu
; Center
(let region (compute-region 0.0 0.0 2.0))
; Seahorse Valley
(let region (compute-region -0.75 0.1 0.5))
; Elephant Valley
(let region (compute-region 0.3 0.5 0.2))
; Double Spiral Valley
(let region (compute-region -0.076 0.6557 0.2))
```
