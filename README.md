# ipdid-did-resolver
This DID document resover for IPDID domain can work with [did-resolver](https://github.com/decentralized-identity/did-resolver)
# build
To build the ipdid-did-resolver library
```
yarn
yarn build
```
# deploy
```
npx np
```
# demo
```
cd example/react-app
yarn
yarn start
```
To press "resolve" button to resolve the following did for a did document respectively.
```
did:ipdid:QmQy3t3odW3wUmJdCwbMAQTRCVjX5VrcSegNkCewXEVdbM
```
DID Document
```
{
  "@context": "https://w3id.org/did/v1",
  "id": "did:ipdid:QmQy3t3odW3wUmJdCwbMAQTRCVjX5VrcSegNkCewXEVdbM",
  "publicKey": [
    {
      "id": "did:ipdid:QmQy3t3odW3wUmJdCwbMAQTRCVjX5VrcSegNkCewXEVdbM",
      "type": "Ed25519VerificationKey2020",
      "controller": "did:ipdid:QmQy3t3odW3wUmJdCwbMAQTRCVjX5VrcSegNkCewXEVdbM",
      "publicKeyMultibase": "zBW6drJM5ErsqLZQkZL7XAcKFaJhVK1C4bB5GviSFftuD"
    }
  ]
}
```
# universal resolver driver
This code similar to universal resolver driver supported in [did-universal-resolver-driver for IPDID method](https://github.com/IPDID/ipdid-dumb-contract/tree/master/packages/universal-resolver-driver)
