las-rs
======

![Continuous Integration](https://github.com/gadomski/las-rs/actions/workflows/continuous-integration.yml/badge.svg)
![Crates.io version](https://img.shields.io/crates/v/las)
[![Documentation](https://docs.rs/las/badge.svg)](http://docs.rs/las)

Read and write [ASPRS las files](http://www.asprs.org/Committee-General/LASer-LAS-File-Format-Exchange-Activities.html) natively with rust.

```toml
[dependencies]
las = "0.8"
```

To include [laz](https://laszip.org/) support:

```toml
[dependencies]
las = { version = "0.8", features = ["laz"] }
```
