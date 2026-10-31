# macos-runner-bench

GitHub-hosted side of a macOS runner benchmark: the same job (a clean `swift build` of
[apple/swift-nio](https://github.com/apple/swift-nio) at tag 2.104.0) on GitHub's `macos-latest`
and on a self-hosted Mac Studio. Public so the GitHub-hosted minutes are free.

The workflow only runs on `workflow_dispatch`; it never runs on pushes or pull requests.
