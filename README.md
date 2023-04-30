## Multithreaded Server built in Rust.

Potential to explore further: 
- fork/join model
- single-threaded async I/O model
- multi-threaded async I/O model

- a function named build with the following signature to compare with the new function:
```pub fn build(size: usize) -> Result<ThreadPool, PoolCreationError> {```

- Add more documentation to ThreadPool and its public methods.
- Add tests of the library’s functionality.
- Change calls to unwrap to more robust error handling.
- Use ThreadPool to perform some task other than serving web requests.
- Find a thread pool crate on crates.io and implement a similar web server using the crate instead. Then compare its API and robustness to the thread pool we implemented.
