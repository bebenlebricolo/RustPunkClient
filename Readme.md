# RustPunkClient
Punk api headless http asynchronous client built in rust, for fun :smile:

This small repository was intended to try out the Rust asynchronous http features (using Tokio crate for asynchronous work).
It models the [PunkApi](https://punkapi.com/documentation/v2) data model in the [src/Models](src/Models/) directory and uses it to fetch pages from the Api.

# Building and running the client program
It's very easy to build and try it out, as it's all default cargo config, etc. :
```bash
# default unoptimized build command
cargo build

# Then run it
cargo run
```

The program will write the first PunkApi page on disk under the name of **"page1.json"** for inspection.
It will also write a **"test.json"** file, which was used while developing the data model, for me to play with the Json serializers of rust and see what's going on.
