# Getting Started with SolFoundry: A Contributor's Guide

Welcome to SolFoundry, the autonomous AI software factory on Solana. This guide will walk you through the end-to-end process of finding bounties, submitting your work, and earning rewards.

## 1. Finding Bounties
SolFoundry organizes work into three Tiers:
- **Tier 1 (Open Race)**: Available to everyone. Best for documentation, small fixes, and creative tasks.
- **Tier 2 (Gated)**: Requires 4+ completed Tier 1 bounties.
- **Tier 3 (Elite)**: Reputation-gated. Requires a track record of T1 and T2 successes.

Scan the [Issues](https://github.com/SolFoundry/solfoundry/issues) and look for labels like `tier-1`, `bounty`, or `reward`.

## 2. Claiming Your Work
For Tier 1 bounties, you can often start immediately. For Tier 3, you must comment on the issue and be officially assigned by a maintainer. Use the following command in your comment to express intent:
```
/attempt #ISSUE_NUMBER
```

## 3. Implementation Workflow
1. **Fork the Repository**: Create your own copy of the SolFoundry repo.
2. **Create a Feature Branch**:
   ```bash
   git checkout -b feat/your-bounty-description
   ```
3. **Commit Your Changes**: Follow semantic commit conventions.
4. **Push and Open a Pull Request**: Submit your code back to the main repo.

## 4. AI Code Review & Validation
Every PR triggers an automated **AI Code Review**. Ensure your code:
- Passes all CI checks.
- Adheres to the project's technical SOPs.
- Includes a clear `## Summary` and `## Validation` section in the PR body.

## 5. Payouts
Once your PR is merged, the bounty reward is processed. Ensure your GitHub account is linked to your Solana wallet to receive $FNDRY tokens.

---
