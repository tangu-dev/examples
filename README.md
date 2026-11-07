# Tangu Language Examples

A collection of examples for the Tangu programming language.

## Examples

- [`fibonacci`](fibonacci/main.tan) — Iterative, recursive (`when` pattern matching), and Binet's analytic ($\varphi$) Fibonacci implementations.
- [`gcd`](gcd/main.tan) — Iterative and recursive Euclidean Greatest Common Divisor (`gcd`) and Least Common Multiple (`lcm`).
- [`http-service`](http-service/main.tan) — HTTP web server using `/web/app` declarative routing, `#shtml` markup, reverse routing (`url-for`), and JSON responses.
- [`mandelbrot`](mandelbrot/main.tan) — Mandelbrot fractal renderer outputting a 256-color RGBA PNG via `/math/complex`, `Slab`, and `/image/png`.
- [`raytracer`](raytracer/main.tan) — Monte Carlo path-tracing renderer supporting Lambertian diffuse, metal, and dielectric glass materials, outputting an RGB PNG via `/vec`, `/rng`, `Slab`, and `/image/png`.

## Run the Examples

```sh
tangu run fibonacci
tangu run gcd
tangu run http-service
tangu run mandelbrot
tangu run raytracer
```

## Run the Tests

```sh
tangu test
tangu test --release
```

## Status

This is an _experimental_ project, not intended for production use.

## Contributing

Pull requests, issues, and comments are welcome! Make sure to add tests for new
features and bug fixes.

## License

This work is licensed under the Apache-2.0 License with LLVM Exceptions. See
[LICENSE.txt](LICENSE.txt) or <https://spdx.org/licenses/LLVM-exception.html>
for details.

## Copyright

Copyright © 2024–2026 [Georgios Moschovitis](https://gmosx.com).
