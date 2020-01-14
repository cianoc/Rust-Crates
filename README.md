# Rust-Crates
Crates that seem useful to me. Plus links to useful tutorials and stuff. Very personal, probably not useful to anyone else.

## Data Structures
### Dash Map
https://crates.io/crates/dashmap

A concurrent hashmap. Focus on speed.

### Static Vec
https://crates.io/crates/staticvec

Implements a fixed-capacity stack-allocated Vec alternative backed by an array. Supports const. Also has static string support. 

### Generic Array
https://docs.rs/generic-array/0.13.2/generic_array/

This crate implements a structure that can be used as a generic array type [T; N], where N is an int type.

Good for when you want a generalized struct whose size can be defined at compile time. Particularly useful if you want the array to be part of the struct.

## Generic Programming

### Typenum
https://docs.rs/typenum/1.11.2/typenum/index.html

This crate allows you to make numbers part of a type. Super useful for generic programming.

## Operating System

### Sysinfo
https://crates.io/crates/sysinfo

Useful for getting system level info (e.g. number of disks, network info, etc). Cross platform.

## Web Front End
### Yew
Elm like front end that compiles to Webassembly. One of the more mature options.

https://crates.io/crates/yew

## Creative Coding
### 3D Graphics
https://docs.rs/luminance/0.38.0/luminance/

Easily the best choice for a creative 3D framework. Great tutorial, written by experienced demoer with a Haskell background. Plus fun.

### Noise-RS
https://github.com/Razaekel/noise-rs

A procedural noise generation library for Rust.

## Numerical Simulation
### Rust Sim
https://www.rustsim.org/

Most of the good stuff is here.

## Games
### GGEZ
Simple game engine
http://ggez.rs/

### Amesthyst

#### 3D rendering example
https://github.com/amethyst/amethyst/tree/master/examples/renderable

### Sound Effects
https://github.com/bzar/sfxr-rs
Procedural sound effects

## Scripting
### Lua
https://github.com/kyren/rlua

Safe Lua scripting.

## Audio
### Org/vorbis
https://github.com/RustAudio/lewton

## Video
### SMFL Bindings
https://github.com/jeremyletang/rust-sfml

## Iterators
### itertools
https://docs.rs/itertools/0.7.11/itertools/

## Randomize
### Rand
https://docs.rs/rand/0.6.1/rand/

## Command Line Args
### Clap
https://docs.rs/clap/2.32.0/clap/

## Graphics
### Image
Working with images (not drawing, but standard decoding/encoding/colorspace/etc).

### SVG
https://github.com/RazrFalcon/resvg

# Investigate
 lazy_static, log, rand, num, smallvec, serde (+json +yaml), strum, rental, regex, backtrace, itertools, error-chain, sdl2, gl, png, ogg-sys, vorbis-sys, vorbisfile-sys, twox-hash, rlua
