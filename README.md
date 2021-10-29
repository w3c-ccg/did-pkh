# did-pkh-
We would like to open up the design process for did:pkh to a more open and consultative/deliberative conversation in the open.

## Include Link to Abstract or Draft 

Draft spec [here](https://github.com/spruceid/ssi/blob/383cb7b3e4e8dace1c527585f8767f882ce81a55/did-pkh/did-pkh-method-draft.md) (plain markdown)

## List Owners

Juan Caballero, Spruce, @bumblefudge 
Charles Lehner, Spruce, @celehner
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
