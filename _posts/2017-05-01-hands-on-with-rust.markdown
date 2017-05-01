---
layout: post
title:  "Introducing Hands-On Rust"
date:   2017-04-30 21:17:19 -0700
categories:
---
Hello, fellow devs. Thanks for stopping by.

[Hands-On Rust](handsonrust.com) was created for developers interested in learning the [Rust Programming Language](https://www.rust-lang.org/en-US/). Whether you are a brand new software developer or an experienced developer looking to pick up a new language, my hope is that you will find this site as a useful resource in learning a fun new low-level language.

As I write this post, I myself have only completed the [Hello World](http://rustbyexample.com/hello.html) exercise!

With little Rust programming experience under my belt, I hope to help you learn by sharing my journey in learning the language. First, we'll start with the basics and work our way into some of the more challenging concepts. Assuming I manage to stay motivated and continue to blog, I have many exciting project ideas lined up that will really make your Rust programming experience come alive!

### Let's Get Started
Before writing a single line of code, you need to make sure you have a working installation of the Rust toolchain on your machine. Head on over to the [Rust Installation](https://www.rust-lang.org/en-US/install.html) page and follow the instructions to get Rust installed.

Once Rust is installed, you can quickly generate a "Hello World" app using [Cargo](http://doc.crates.io), the Rust Package Manager:

```cargo new hello_world --bin```

This will create a new Rust binary project (as opposed to a Library) in a folder called `hello_world`.

To run this example, simply `cd hello_world` and run `cargo run`. This will build the application and run it.

If all goes well, you should see the following output from your terminal:

```bash
> cargo run
   Compiling hello_world v0.1.0 (file://sandbox/hands_on_rust/examples/hello_world)
    Finished dev [unoptimized + debuginfo] target(s) in 0.92 secs
     Running `target/debug/hello_world`
Hello, world!
```

#### Examples
For the duration of this blog, I plan to share the examples discussed in the posts in the [examples]({{ site.github_url }}/examples) folder.

For example, the complete source code for the "Hello World" example above can be found [here]({{ site.github_url }}/examples/hello_world).

--

Thanks again for stopping by and I hope you find learning Rust to be as fun as it is for me!
