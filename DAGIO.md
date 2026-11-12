# Dagio Miniflare releases

Dagio publishes `@dagio-ai/surface-miniflare` from this fork in GitHub Packages. The remote binding
proxy uses the Dagio Cap’n Web release to close one-use RPC sessions after their calls and capabilities
have drained. The upstream HTTP proxy and other Cap’n Web consumers retain their existing behavior.

Each `dagio-v<version>` tag records the exact upstream base and the Dagio source changes. The publish
workflow uses the upstream Miniflare build and remote proxy tests before packing the scoped npm package.
