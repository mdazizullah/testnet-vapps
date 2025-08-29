# vApp Submission: ProofID

## Verification
```yaml
github_username: "mdazizullah"
discord_id: "1048800099268050955"
timestamp: "2025-08-29"
```

## Developer
- **Name**: azizullah
- **GitHub**: @mdazizullah
- **Discord**: azizullah#5323
- **Experience**: 3+ years in full-stack blockchain development, specializing in decentralized identity (DID) and zk-proofs. Contributed to open-source Web3 projects integrating wallet auth and verifiable credentials.

## Project

### Name & Category
- **Project**: ProofID
- **Category**: identity/social
### Description
ProofID is a decentralized identity verification system that allows users to prove credentials without revealing private data. Instead of sharing sensitive documents (like KYC), users generate zk-proofs anchored to the Soundness Layer (SL), ensuring trustless verification.

= Example: A DAO can verify a user is “over 18 and from region X” without storing any personal data.

= Use cases: DeFi onboarding, gated communities, gaming KYC-lite, DAO voting.

### SL Integration  
- Zero-Knowledge Proofs: Leverage SL’s zk stack for efficient credential proofs.

- Sound Wallet Integration: Bind proofs to wallet addresses for seamless Web3 login.

- Data Integrity Layer: Store hashes of verifiable credentials on SL for tamper-proof verification.

## Technical

### Architecture
1. User Wallet → connects to SL-enabled dApp.

2. Proof Generator → creates zk-proof of credential.

3. Verifier Smart Contract (on SL) → validates proof without revealing data.

4. Frontend UI → clean React-based login/verification flow.

### Stack
- **Frontend**: React + Next.js
- **Backend**: Node.js (for off-chain credential issuance)  
- **Blockchain**: Soundness Layer (SL) + optional Ethereum L2 for interoperability
- **Storage**: WALRUS for encrypted credential blobs, IPFS for metadata

### Features
1. Private KYC: Prove identity attributes without revealing full documents.

2. Age/Region Proofs: On-chain proof for compliance (e.g., DeFi age checks).

3. DAO & dApp Login: “Sign-in with ProofID” button using SL + zk.


## Timeline

### PoC (2-4 weeks)
- [ ] Build wallet-based login flow
- [ ] Integrate SL zk-proof verification contract
- [ ] Simple React UI for demo

### MVP (4-8 weeks)  
- [ ] Add multiple credential types (age, nationality, membership)
- [ ] WALRUS storage integration
- [ ] Launch pilot with DAO login & DeFi KYC-lite flow
- [ ] User testing and bug fixes


## Innovation
Unlike centralized KYC, ProofID enables privacy-preserving verification. Users control their data, dApps get compliant proofs, and SL ensures trustless security. This reduces friction for onboarding while protecting user privacy.

## Contact
DC= azizullah#5323

**Checklist before submitting:**
- [ ] All fields completed
- [ ] GitHub username matches PR author  
- [ ] SL integration explained
- [ ] Timeline is realistic
