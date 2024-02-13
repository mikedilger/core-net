# core-net

THIS CRATE IS GOING AWAY SOON: as of rust 1.77 core-net should be stabilized so
hacks like this won't be necessary anymore.

This is a rip of core::net from the Rust language, with stability features
removed so you can use the unstable features on the stable compiler.

It was ripped frop this commit 38b96553112dce3de630890701f17d86e265f6ba
and may not be up to date.

THIS IS NOT FUTURE SAFE: In order to use these features, you could
`std::mem::transmute` the types from the actual core library into these
types and back. But if rust std changes, serious errors could occur!
