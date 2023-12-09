

### Values 
- individual freedom
- self-development and constant improvement 
- democratizing access to AI and Knowledge  
- property right 
- privacy right 

---

### AI Challenges 

- Computation power 
	- Electricity 
	- GPU and silicon
-  Data 
	- Hunger 
	- Ownership
	- Privacy
	- fair reward 
 
---

### Data -  AI Fuel 

- Open data 
- Quality data 
- personal/closed data 

---

### Data Ownership 
- web2 - Soviet union like state of data ownership 
- web3 - give ownership back 
- web5 - give privacy and selective sharing  to ownership

[learn more about webX](https://medium.com/@volodymyrpavlyshyn/toot-is-a-mastodon-tweet-500-characters-long-fcb54807e11e)

---

###  Self Sovereign Principles
Foundational needs 
- **Existence** — exist in real life  
- **Control** — control their identities.  
- **Access** — access to their data  
-  **Persistence** - must be long-lived.  
---
### Self Sovereign Principles 
Open protocol and technologies
- **Transparency** -  Systems and algorithms must be transparent.  
- **Portability** - identity must be transportable  
-  **Interoperability** — Identities should be as widely usable as possible.  
---
###  Self Sovereign Principles 
Privacy and Security 
- **Consent** -  Users must agree to the use of their identity.  
- **Minimization** -  Disclosure of claims must be minimized  
-  **Protection** — The rights of users must be protected

[Self Sovereign Identity in 7 Toots](https://medium.com/@volodymyrpavlyshyn/self-sovereign-identity-in-7-toots-c29fff0f7961)

---
#### WEB 5
- WEB3 + WEB2
- SSI on steroids 
- DIDs (identity) + DWNs (data)

[What web5 is about](https://medium.com/@volodymyrpavlyshyn/what-is-web5-about-and-why-does-it-matter-in-the-post-ai-and-post-blockchain-world-bca8148b0766)

---

###  DID
- [Dezentralized Identifier](https://identity.foundation/faq/) 
 - crypto-based verifiable identifier 
 - autonomous 

```
did:ion:EiAdGwEUhV-SPP7TKMGME1hijDUMa_EyTNfBl72tBWYISw
```
---

### DID Document 

```
{
  "id": "did:ion:EiAdGwEUhV-SPP7TKMGME1h",
  "@context": [
    "https://www.w3.org/ns/did/v1"
  ],
  "service": [
    {
      "id": "#dwn",
      "type": "DecentralizedWebNode",
      "serviceEndpoint": {
        "encryptionKeys": [
          "#dwn-enc"
        ],
        "nodes": [
          "https://dwn.tbddev.org/dwn2"
        ],
        "signingKeys": [
          "#dwn-sig"
        ]
      }
    }
  ],
  "verificationMethod": [
    {
      "id": "#dwn-sig",
      "controller": "did:ion:EiAdGwEUhV-SPP7TKMGME1hijDUMa_EyTNfBl72tBWYISw",
      "type": "JsonWebKey2020",
      "publicKeyJwk": {
        "crv": "Ed25519",
        "kty": "OKP",
        "x": "a3Xi1AAXRLFxnV3a7dLFngvBLetnfV680Gzae1AXSkc"
      }
    },
    {
      "id": "#dwn-enc",
      "controller": "did:ion:EiAdGwEUhV-SPP7TKMGME1hijDUMa_EyTNfBl72tBWYISw",
      "type": "JsonWebKey2020",
      "publicKeyJwk": {
        "crv": "secp256k1",
        "kty": "EC",
        "x": "NMHmwS6fjGbxDlH5zZcClzBQq2rS6XwOBtQMIZpXCag",
        "y": "Lcekf50knaHQy1azzlvbCsfO5ihNMZYTLca_yx4x85c"
      }
    }
  ],
  "authentication": [
    "#dwn-sig"
  ],
  "keyAgreement": [
    "#dwn-enc"
  ]
}
```
---
### Decentralized Web Nodes 

DWN = Secured storage + Permissions + message relay

![](![[Pasted image 20231209105131.png]])

---

## DWN 
Protocols and open technology
![[Pasted image 20231209105402.png]]

---

### AI use cases of SSI and WEB5

- learning on  private data 
- data economy 
- Authentic sensors — how to prove nongenerative content
-  ZKML — proof of Model use

[Self-Sovereign Data and AI/ML](https://medium.com/@volodymyrpavlyshyn/with-the-current-boom-in-artificial-intelligence-ai-and-large-language-models-the-intersection-28cdcf5f4153)

---
### Personal AI usecases 
- personal ai,
- proof of personhood
- personalized experiences without risking privacy
---

### KIN 

- personal 
- private 
- build on top of web5 




