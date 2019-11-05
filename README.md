# ![RealWorld Example App](logo.png)

[![RealWorld Frontend](https://img.shields.io/badge/realworld-frontend-%23783578.svg)](http://realworld.io)

> ### [Rust] + [Yew] codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld] spec and API.


### [Demo]&nbsp;&nbsp;&nbsp;&nbsp;[RealWorld]


This codebase was created to demonstrate a fully fledged [WebAssembly] web application built with [Yew] including CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the [Yew] community styleguides & best practices.

For more information on how to this works with other frontends/backends, head over to the [RealWorld] repo.


# How it works

This is an application written in [Rust] that utilizes [Yew] and [WebAssembly] for developing the frontend web app that powers the RealWorld application.

# Getting started

You can view a live demo over at [Demo]

* Install [Rust]
* Install cargo-web
  ```
  cargo install cargo-web
  ```
* Build and start
  ```
  cargo web start -p conduit-wasm
  ```
* Visit http://[::1]:8000
* Build and release
  ```
  cargo web deploy -p conduit-wasm
  ```
  You should find static files at `target/deploy` folder now.

[Rust]: https://www.rust-lang.org/
[Yew]: https://github.com/yewstack/yew
[RealWorld]: https://github.com/gothinkster/realworld
[Demo]:https://jetli.github.io/rust-yew-realworld-example-app/
[WebAssembly]: https://webassembly.org