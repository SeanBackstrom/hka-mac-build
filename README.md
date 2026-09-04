# hka-mac-build

Build automation only. This repository holds no application source, no model
files, and no release artifacts. Its workflow checks out a private repository
with a repository secret at run time, builds a macOS disk image on a hosted
Apple Silicon runner, and publishes the result to private object storage.
