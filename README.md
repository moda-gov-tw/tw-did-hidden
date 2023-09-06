# Hidden

This repository is designed for managing a W3C Decentralized Identifiers (DIDs) that facilitates a hidden identity within the Semaphore zero-knowledge proof framework. The user can use this DID to prove their membership in a Semaphore group without revealing their actual identity.

The DID URI is `did:web:tw-did.github.io:hidden`. You can also access the DID document via https://tw-did.github.io/hidden/did.json.

### Publishing `did.json`

To update and publish your `did.json`, follow these commands:

```shell
git checkout publish
git show main:did.json > did.json
git add did.json
git commit -a -m 'Update did.json'
git push origin publish
git checkout main
```
