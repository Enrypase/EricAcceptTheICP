1) Figure out if extensions are separated (if we can call metamask from our extensions) - *Breach* magic with mobilephone - Even web2 stuff it's acceptable
2) GRPC for messages
3) Serverless architecture
4) Rust for the backend
5) Decentralized Edge Database
6) For the frontend NextJS (if SSR/RSC/SSG are required) otherwise react/solidjs
7) History of the message will be kept only if we have time to implement it

- If we have additional time, implement other channels based on ownership of NFTs/Tokens/Other

Note:
- https://akash.network/


# Architecture
## Messaging
Consists of a stand-alone processing service. Handles connections, messages redirection, service signaling (*pinning*, *off-load*)
## Persistance
Covers local (client-side, secured by passphrase) and remote (decentralized) storage. Represented by background service that egresses the data to target layer.
## Privacy preserving (?)
- Waku relayer
- [PSE](https://pse.dev) frameworks

# Other sutff
- Decentralized data-layer: Ceramic
Edge computing