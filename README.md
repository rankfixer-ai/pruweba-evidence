# Pruweba — Public Evidence Records

This repository contains public verification evidence from the Pruweba API.

**Every record is cryptographically hash-linked. Tampering is detectable.**

## Verify the Chain

```bash
curl https://api.pruweba.com/chain/verify
# {"valid": true}
```

## Latest Attestations

```bash
curl https://api.pruweba.com/attestations
```

## How It Works

1. **Claim** — An agent asserts a state transition
2. **Verify** — Checked against invariants
3. **Prove** — SHA-256 proof chain generated
4. **Attest** — Immutable evidence record written

Pruweba is the verification layer of MetaLoop. The engine is proprietary. The evidence is public.
