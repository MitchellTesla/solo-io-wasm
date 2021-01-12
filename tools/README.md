WASM Tools
The subdirectories here contain tools for working with WASM projects.

Test-loader: A test to ensure the Envoy WASM filters can be loaded by Envoy.
WASME: A CLI tools for working with WebAssembly Hub and WASM modules.
wasme cli
The wasme CLI provides a tool for building and sharing Envoy WebAssembly extensions.

Installation   |   Documentation   |   Blog   |   Slack   |   Twitter

How does it work?
The WebAssembly Hub, in combination with the wasme CLI, provides an easy way to build, push, pull, and share Envoy WebAssembly Filters.

The WebAssembly Hub acts as an image registry for WebAssembly Filters hosted at https://webassemblyhub.io. Use the wasme CLI to:

compile Envoy WebAssembly filters on a local machine (the only dependency is docker)
push filters to https://webassemblyhub.io
pull filters from https://webassemblyhub.io
publish filters to the catalog at https://webassemblyhub.io/extensions/
Getting Started
See the Getting Started tutorial to build, push, and run your first WebAssembly Filter!

Next Steps
Join us on our Slack channel: https://slack.solo.io/
Follow us on Twitter: https://twitter.com/soloio_inc
Check out the docs: https://docs.solo.io/web-assembly-hub/latest
Contribute to the Docs
