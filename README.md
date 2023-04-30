## Multithreaded Server built in Rust.

Potential to explore further: 
- fork/join model
- single-threaded async I/O model
- multi-threaded async I/O model

- a function named build with the following signature to compare with the new function:
```pub fn build(size: usize) -> Result<ThreadPool, PoolCreationError> {```