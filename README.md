# Synapse Enhancement Proposals

This repository is a collection of SEPs designed to improve Synapse—detailed ideas intended to spark discussion and achieve consensus.

### SEP Process
All ideas are welcome. A SEP SHOULD start as a pull request to this repository. SEPs that are merged MUST be considered “accepted.”

See the current list of in-progress SEPs [here](https://github.com/SynapseMedia/sep/pulls)

**Process Status:** `EXPERIMENTAL`

This process is in flux and MAY change or end at any point.

---

## SEP-000: SEP Categories and Nomenclature

### SEPs

SEPs MUST fall under one of the following categories:

1. **Architecture**
   - SEPs MUST relate to the internal architecture and software engineering of Synapse, including proposals regarding performance, resiliency, and feature sets.
2. **Standards**
   - SEPs MUST pertain to metadata standards and conventions, including data structures and secure metadata standards.
3. **Security**
   - SEPs MUST address security in the Synapse environment. Proposals related to improvements in distribution, data transmission, encryption, and access control MUST be filed in this category.
4. **Community**
   - SEPs MUST involve external documentation, code of conduct, community engagement, and the SEP process itself.
5. **Economics**
   - SEPs MUST focus on economic and governance mechanisms in Synapse, including token distribution, staking, fee structures, and incentives.

### Anatomy

1. SEPs MUST include a header following the format  `SEP-{PR}:`  followed by the proposal title. Example: **SEP-002: SEP Proposal**.
2. SEPs MUST specify a status that reflects the current condition of the proposal.
3. SEPs MUST indicate the category that provides the context of the proposal.
4. SEPs MUST include a link to the discussion (issue) where the proposal is being followed up.
5. SEPs MUST contain content that consists of at least one complete sentence and MAY follow the conventions of RFC-2119.

Alternatively, you MAY simply follow our [TEMPLATE.md](TEMPLATE.md).

### Consensus

The decision by consensus MUST be evaluated based on the votes and responses in the pull request.

1. Participants SHOULD provide arguments for *why yes* or *why no*.
2. Votes MUST be indicated as a *thumbs up* for +1 or *thumbs down* for -1. The total MUST be the result of subtracting the *thumbs up* - *thumbs down*.
3. The winning argument is determined by the vote count; the proposal MUST be accepted by consensus if there are more upvotes than downvotes, or rejected if downvotes prevail.

**Note:** Proposals MAY be vetoed by the maintainers if they reach a consensus that the proposal violates any law (e.g., privacy or copyright) or contravenes other community standards.

### Numbering

SEPs MUST be numbered using the pull request number in which they are introduced.
For example: `SEP-002: SEP Proposal`

Following RFC-2119:  
<https://datatracker.ietf.org/doc/html/rfc2119>
