# solo-io-wasm
Web Assembly tools and SDKs for extending cloud-native infrastructure (master)

WebAssembly (WASM) is the future of cloud-native infrastructure extensibility.

WASM is a safe, secure, and dynamic way of extending infrastructure with the language of your choice. WASM tool chains compile your code from any of the supported languages into a type-safe, binary format that can be loaded dynamically in a WASM sandbox/VM.

In this repo, you will find tooling, SDKs, an OCI-compatible specification, and examples for working with WASM and specifically WASM on Envoy Proxy based frameworks (like Gloo API Gateway or Istio Service Mesh -- but not limited to those).

One of the projects for working with WASM and Envoy proxy is WebAssembly Hub.

WebAssembly Hub is a meeting place for the community to share and consume WebAssembly Envoy extensions. You can easily search and find extensions that meet the functionality you want to add and give them a try.

Please see the announcement blog that goes into more detail on the motivation for WebAssembly Hub and how we see it driving the future direction of Envoy-based networking projects/products including API Gateways and Service Mesh.

In this Repo
Specification
In the /spec folder of this repo, you'll find an OCI image specification for WebAssembly modules. This specification is an extension to OCI and describes how a WASM module is packaged with the appropriate metadata so that it can be distributed and loaded into Envoy-based frameworks/service meshes. For example, some of the metadata include the root-id of the module, the ABI versions that are targeted in Envoy, and basic name of the module. Please see the spec for more details.

SDKs
In the /sdks folder of this repo, you'll find a listing of the available SDKs for building Envoy Proxy based WASM modules. These SDKs implement the Envoy hooks for Envoy extension points in a language-specific way. The following exist today (with more on the way):

C++
Rust
AssemblyScript
TinyGo
Tools
In the /tools folder, you'll find a set of tools for working with WASM modules. Specifically, tools to do the following:

Bootstrap a new WASM project with boilerplate/version alignment/tool chain
Test that a WASM module can correctly be loaded into Envoy
Build your project with the specific tool chain
Publish your WASM module as a WASM OCI image to an OCI-compatible registry or WebAssembly Hub
Load your WASM module into an Envoy-based framework like Gloo or Istio
Other Resources
Extending Envoy Proxy with WebAssembly
WebAssembly Hub Announcement
WebAssembly Hub and Istio
Envoy WASM repo
Envoy WASM ABI
Proxy WASM repo
Community
The WASM projects in this repository are made up of a collaboration between Solo.io and the wider WebAssembly community.

Please join the Solo.io Slack @ #wasm to participate!

