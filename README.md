<!-- @format -->

# MrewyOrg community files

<img src="assets/mrewyorg-icon.png" alt="MrewyOrg logo" width="160" height="160">

This repository contains the [MrewyOrg organization profile](profile/README.md), branding, and
shared community files for repositories without their own equivalents.

- [Contributing](.github/CONTRIBUTING.md)
- [Support](.github/SUPPORT.md)
- [Code of conduct](.github/CODE_OF_CONDUCT.md)
- [Security](.github/SECURITY.md)

## Update this repository

Use the Node.js version in `.nvmrc`, then run:

```sh
npm ci
npm run prettier
npm run check
```

The public organization profile lives in `profile/README.md`. Keep its image URL absolute so the
logo also resolves on the organization overview. The current logo is `assets/mrewyorg-icon.png`.
