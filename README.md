# rmcpp
This is an experiment to map C++ binary interfaces to Rust. While language mapping is never easy, this one is even more complicated because C++ has a complicated ABI and many C++ constructs can not be mapped 1:1 onto Rust. 
The basic assumption here is, that we can - to a pragmatically satisfying degree - model C++ paradigms by Rust constructs. 

We use pygccxml to generate Rust code and the bullet physics library as a real-life example.

Here are some informative links:
* https://internals.rust-lang.org/t/better-c-interoperability/2650/11
