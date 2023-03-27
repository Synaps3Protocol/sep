# SSP

Synapse Standards Proposals

This repository is a collection of SSP to improve Synapse Network - detailed ideas intended solicit discussion that leads to consensus.

SSP Process
All ideas are welcome. An SSP should start as a pull request to this repo. Merged SSP should be considered "accepted".

See the current listing of in-progress SCPs [here](https://github.com/Synapse/SSP/pulls)

Process Status: `EXPERIMENTAL`

This process is itself in flux and may change or end at some point.

## SSP-001: SSP Nomenclature

### Anatomy

1. SSPs MUST have a header made up of the format SSP-{PR}: followed by the title of the SSP. eg: **SSP-002: SSP Proposal**. [See TEMPLATE.md](TEMPLATE.md)

### Consensus

The decision by consensus MUST be evaluated according to vote in the response given to the PRs.

1. People SHOULD respond with their arguments for *why yes* or *why no*.
2. Votes to response MUST be given as *thumbs up* for +1 or *thumbs down* for -1 and the total MUST be the result of subtraction of *thumbs up* - *thumbs down*.
3. The winning response is based on the votes, the proposal MUST be accepted by consensus if the response argument was for "yes" or rejected if it was for "no".

`Note`: Proposals MAY be vetoed by the maintainers if it is determined by consensus among themselves that the proposal violates any type of law against e.g. privacy or copyright, or if the proposal violates other community standards.

### Numbering

SSPs MUST be numbered the same as the pull request which they are introduced.
eg. SSP-002: SCP Proposal

Following RFC-2119:
<https://datatracker.ietf.org/doc/html/rfc2119>
