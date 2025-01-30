# SEP

## Synapse Enhancement Proposals

This repository is a collection of SEPs to improve Synapse - detailed ideas intended to solicit discussion that leads to consensus.

### SEP Process
All ideas are welcome. An SEP should start as a pull request to this repo. Merged SEPs should be considered "accepted".

See the current listing of in-progress SEPs [here](https://github.com/SynapseMedia/sep/pulls)

**Process Status:** `EXPERIMENTAL`

This process is itself in flux and may change or end at some point.

---

## SEP-000: SEP Categories and Nomenclature

### SEPs

SEPs MUST pertain to several different categories:

1. **Architecture**
   - SEPs MUST relate to the internal architecture and software engineering of Synapse. Proposals regarding performance, resiliency, and feature sets are submitted in this category.
2. **Standards**
   - SEPs MUST relate to metadata standards and conventions, including data structures and secure metadata standards.
3. **Security**
   - SEPs MUST relate to security in the Synapse environment. Proposals related to improvements in distribution, data transmission, encryption, and access control are filed in this category.
4. **Community**
   - SEPs MUST relate to external documentation, code of conduct, community engagement, and the SEP process itself.
5. **Economics**
   - SEPs MUST relate to the economic and governance mechanisms of Synapse, including token distribution, staking, fee structures, and incentives.

### Anatomy

1. SEPs MUST have a header made up of the format `SEP-{PR}:` followed by the title of the SEP. e.g., **SEP-002: SEP Proposal**.
2. SEPs MUST have a status that defines the current condition of the proposal.
3. SEPs MUST have a category that defines the context of the proposal.
4. SEPs MUST have a discussion (issue) link to follow up the proposal.
5. SEPs MUST have content that consists of one full sentence and MAY follow RFC-2119.

Or just follow our [TEMPLATE.md](TEMPLATE.md).

### Consensus

The decision by consensus MUST be evaluated according to votes in the responses given to the PRs.

1. People SHOULD respond with their arguments for *why yes* or *why no*.
2. Votes in response MUST be given as *thumbs up* for +1 or *thumbs down* for -1, and the total MUST be the result of subtracting *thumbs up* - *thumbs down*.
3. The winning response is based on the votes; the proposal MUST be accepted by consensus if the response argument was for "yes" or rejected if it was for "no".

**Note:** Proposals MAY be vetoed by the maintainers if it is determined by consensus among themselves that the proposal violates any type of law (e.g., privacy or copyright) or if the proposal violates other community standards.

### Numbering

SEPs MUST be numbered the same as the pull request in which they are introduced.  
e.g., `SEP-002: SEP Proposal`

Following RFC-2119:  
<https://datatracker.ietf.org/doc/html/rfc2119>
