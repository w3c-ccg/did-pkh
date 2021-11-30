# did-pkh

We would like to open up the design process for the did:pkh [**method specification**](did-pkh-method-draft.md) to a more  consultative/deliberative conversation for the broader W3C-CCG community.

## Meetings

Regular meetings for this CCG work item will be held every two weeks on Thursdays at [1.30PM Eastern Time](https://www.timeanddate.com/worldclock/), on a 
[workitem-specific jitsi room](https://meet.w3c-ccg.org/didpkh) hosted by the CCG.  Minutes will be published 
in a [running markdown file](agenda1.md) here in the repo.  

Our **standing agenda** is first [PR](https://github.com/w3c-ccg/did-pkh/pulls) review, then 
[issue](https://github.com/w3c-ccg/did-pkh/issues) review (prioritized by labels, then by 
[stalest-first](https://github.com/w3c-ccg/did-pkh/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-asc)). 
At least one of three work item owners will moderate PR review and issue review (respectively) at each meeting,
with the prioritization of the latter at the discretion of the chairs. Implementers, researchers, and community
members are welcome to open issues if they would like clarification of the intended or possible usages of the 
method. We will use the "next meeting" tag for issues and PRs that we want to discuss soon, so the 
[next meeting label](https://github.com/w3c-ccg/did-pkh/labels/next%20meeting) view is the fastest way to see
an up-to-date agenda for the upcoming meeting(s). We are also glad to take requests for older issues to 
*receive* that label at the end of all meetings.

When agendas of interest to the general community (including ratification and review period resolutions) come 
up, we will manually set an agenda on the CCG mailing list in addition to this GitHub-based tracking. 

## Include Link to Abstract or Draft 

Draft spec [here](./did-pkh-method-draft.md) (plain markdown)

## List Owners

Juan Caballero, Spruce, @bumblefudge 
Charles Lehner, Spruce, @clehner
Joel Thorstensson, 3Box/Ceramic, @oed

## Work Item Questions

### Explain what you are trying to do using no jargon or acronyms.

We would like to open up the design process for did:pkh to a more open and consultative/deliberative conversation in the open.

did:pkh is a generative "pseudo-DID method" like did:key that generates a DID document from blockchain addresses, conformant with the CAIP-10 specification for expressing blockchain addresses (usually based on public key hashes or "pkh").  This allows the keypairs driving most major blockchain identity systems to generate instantaneously a "pseudo-DID" (essentially a did:key) with an account.  This allows short-lived, low-security DIDs to be generated on the spot anywhere a blockchain "web wallet" can be used, leaving security, account recovery, and other hard problems on the side of the blockchain that governs the address.

2. How is it done today, and what are the limits of the current practice?

Today, each blockchain needs to have its own DID method(s), and create additional software to run these.  This DID method exists to create a "bridge" to blockchain-specific identity systems (and wallets, and wallet/dApp ecosystems).

3. What is new in your approach and why do you think it will be successful?

Our approach builds on other pragmatic "cross-chain" efforts in the blockchain space, including the CAIP-10 specification that it relies on to abstract out the relationship between keypairs and addresses, making it easier and more ergonomic to support many blockchains. 

4. How are you involving participants from multiple skill sets and global locations in this work item? (Skill sets: technical, design, product, marketing, anthropological, and UX. Global locations: the Americas, APAC, Europe, Middle East.)

We are hoping that by opening up our DID method design process to be more open, we will hear from business and technical voices far and wide, particularly since the dApp ecosystem is fairly international and open-source in nature. If many weeks pass without input, we may do active outreach via the ethereum community and DIF.

5. What actions are you taking to make this work item accessible to a non-technical audience?

We have tried to craft a did method specification draft that is accessible and welcome PRs if it can be made more accessible.
