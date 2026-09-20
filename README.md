# Tommy's VS Code profile

My portable VS Code settings and extension set for Windows and Linux.

## Import

1. Download [`Tommy.code-profile`](./Tommy.code-profile).
2. In VS Code, open **Manage → Profiles → Import Profile**.
3. Select the downloaded file, review the contents, and choose **Create**.

VS Code installs the included extensions and applies the settings through its built-in
Profiles system. No setup scripts or platform-specific tooling are required.

## Update

Use **Manage → Profiles → Export Profile**, choose **Local**, and replace
`Tommy.code-profile` in this repository.

The profile deliberately excludes credentials, machine-specific paths, caches, and
workspace history.
