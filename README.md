# What is this?

While planning the [Chaincode Residency](https://residency.chaincode.com/), we put considerable effort into finding the best resources and creating a curriculum around Bitcoin protocol development. You can find all of our published materials on our [resources page](https://residency.chaincode.com/resources.html#resources).

Bitcoin is constantly evolving, and so we expect maintenance of this document to be an ongoing task. We could use your help. Please **consider opening a pull-request or [opening an issue](https://github.com/chaincodelabs/bitcoin-curriculum/issues/new)** to keep this document relevant.

There are two portions to this curriculum:
1. [Study Groups](https://github.com/chaincodelabs/study-groups#bitcoin) designed to provide grouped subjects that you can either complete bookclub style or alone.
2. [Bitcoin Syllabus](#bitcoin-syllabus) a collection of resources grouped by subjects.


# Bitcoin Syllabus

| Subject                       | Topic  | Sources |
|-------------------------------|--------|---------|
Introduction|White Paper|[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)|
Introduction|If I'd Known What We Were Starting (2017)|[If I'd Known What We Were Starting](https://www.linkedin.com/pulse/id-known-what-we-were-starting-ray-dillinger/)|
Introduction|Bitcoin's Academic Pedigree (2017)|[Bitcoin's Academic Pedigree](https://queue.acm.org/detail.cfm?id=3136559)|
Introduction|Intro to Blockchain|[What is blockchain anyway?](https://www.youtube.com/watch?v=on5ySFK0aoY)|
Introduction|Intro to Blockchain|[Electronic cash explained for developers video](https://www.youtube.com/watch?v=TrF9RmfyLbw)|
Introduction|The Economic Limits of Bitcoin and the Blockchain|[The Economic Limits of Bitcoin and the Blockchain](https://faculty.chicagobooth.edu/eric.budish/research/Economic-Limits-Bitcoin-Blockchain.pdf)|
Introduction|Proof of work|[The Anatomy of Proof-of-Work](https://bitcointechtalk.com/the-anatomy-of-proof-of-work-98c85b6f6667), [Bitcoin Developer Reference](https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf)|
Introduction|Difficulty adjustment|[What keeps the average block time at 10 minutes?](https://bitcoin.stackexchange.com/questions/855/what-keeps-the-average-block-time-at-10-minutes/857#857)|
Introduction|Byzantine generals problem|[The Byzantine Generals Problem](http://diyhpl.us/~bryan/papers2/bitcoin/The%20Byzantine%20generals%20problem%20-%20Lamport%20-%201982.pdf)|
Introduction|Running a full node|[Full Node Question](https://www.reddit.com/r/BitcoinBeginners/comments/3eq3y7/full_node_question/ctk4lnd/)|
History & Philosophy of Bitcoin|History of Bitcoin Development| [The Incomplete History of Bitcoin Development](https://b10c.me/The-incomplete-history-of-Bitcoin-development/)|
History & Philosophy of Bitcoin|What is consensus?| [Consensus Algorithms, Blockchain Technology and Bitcoin](https://www.youtube.com/watch?v=fw3WkySh_Ho)|
Soft Forks & protocol overview|On Unstoppability of Softforks|[On Unstoppability of Softforks](https://zmnscpxj.github.io/bitcoin/unpreventable-softforks.html)|
Soft Forks & protocol overview|Example soft forks|[Softfork wiki page](https://en.bitcoin.it/wiki/Softfork)|
Soft Forks & protocol overview|Forking signaling and Activation|[Forks, Signaling, and Activation](https://medium.com/@elombrozo/forks-signaling-and-activation-d60b6abda49a)|
Soft Forks & protocol overview|Fork categorization (soft, hard, evil, etc.)|[Better Fork Terminology](http://www.truthcoin.info/blog/protocol-upgrade-terminology/), [Forced Soft Forks](https://petertodd.org/2016/forced-soft-forks)|
Soft Forks & protocol overview|Flag day upgrades|[UASF: User Driven Protocol Development](https://medium.com/@bergealex4/uasf-user-driven-protocol-development-da4e886832d)|
Soft Forks & protocol overview|IsSuperMajority signaling|[BIP 65](https://github.com/bitcoin/bips/blob/master/bip-0065.mediawiki)|
Soft Forks & protocol overview|BIP9 signaling|[BIP9: versionbits In a Nutshell](https://rusty.ozlabs.org/?p=576), [BIP 9](https://github.com/bitcoin/bips/blob/master/bip-0009.mediawiki)|
Soft Forks & protocol overview|BIP148 and BIP149|[BIP 148](https://github.com/bitcoin/bips/blob/master/bip-0148.mediawiki), [BIP 149](https://github.com/bitcoin/bips/blob/master/bip-0149.mediawiki), [UASF BIP148 Scenarios and Game Theory](https://medium.com/@jimmysong/uasf-bip148-scenarios-and-game-theory-9530336d953e), [User Activated Soft Forks: the BIP 148 alternative](https://medium.com/segwit-co/user-activated-soft-forks-the-bip-148-alternative-28e87ffdb76f)|
Soft Forks & protocol overview|BIP91|[BIP 91](https://github.com/bitcoin/bips/blob/master/bip-0091.mediawiki)|
Security Models|Overview|[Security models seminar video](https://youtu.be/6gGcS4N5Rg4), [Overview of Security Concerns](https://diyhpl.us/wiki/transcripts/scalingbitcoin/overview-of-security-concerns/), [Danger! Bitcoin Threat Models](https://www.youtube.com/watch?v=ddN58UqKPx0#t=750), [Bitcoin’s Security Model: A Deep Dive](https://www.coindesk.com/bitcoins-security-model-deep-dive), [Weaknesses](https://en.bitcoin.it/wiki/Weaknesses), [Speed-Security Tradeoffs in Blockchain Protocols](https://pdfs.semanticscholar.org/ac1a/918fc933b767d34574ec2cc6a33b4223dc1a.pdf), [The Onion Model of Blockchain Security](https://insights.deribit.com/market-research/the-onion-model-of-blockchain-security-part-1/)|
Security Models|Checkpoints, assumevalid, minimumchainwork|[Bitcoin's Diversity of Use-Cases and Security Models](https://bluematt.bitcoin.ninja/2017/02/28/bitcoin-trustlessness/), [Dave Harding Tweet on assumed valid blocks and minimum chainwork](https://twitter.com/hrdng/status/869206705548271616)|
Security Models|Defining SPV and lightclients|[Light Clients](https://gist.github.com/ariard/1034cd7624805d53334e80d4712fb8ee)|
Security Models|BIP 37 (bloom filters)|[BIP 37](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki), [On the Privacy Provisions of Bloom Filters in Lightweight Bitcoin Clients](https://eprint.iacr.org/2014/763.pdf)|
Security Models|Neutrino |[BIP 157](https://github.com/bitcoin/bips/blob/master/bip-0157.mediawiki), [Neutrino: The Lighter Side of Lightning](https://blog.lightning.engineering/posts/2018/10/17/neutrino.html), [Index for BIP 157 block filters](https://github.com/bitcoin/bitcoin/pull/14121)|
Security Models|Committed bloom filters|[Committed bloom filters for improved wallet performance and SPV security](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2016-May/012636.html)|
Security Models|Fraud proofs|[Fraud Proofs (2018)](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/fraud-proofs/), [Fraud Proofs: Improving the ability of SPV clients to detect invalid chains (gist)](https://gist.github.com/justusranvier/451616fa4697b5f25f60), [Bitcoin Wizards Fraud Proof thread](https://people.xiph.org/~greg/bitcoin-wizards-fraud-proof.log.txt), [Improving SPV security with PoW fraud proofs](https://www.mail-archive.com/bitcoin-dev@lists.linuxfoundation.org/msg07913.html)|
Security Models|Committed UTXO hashes|[UTXO set commitment hash](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-October/011638.html)|
Security Models|Assume UTXO|[Assume UTXO FAQs](https://github.com/jamesob/assumeutxo-docs/tree/2019-04-proposal/proposal), [Assume UTXO (video)](https://youtu.be/PoEoG6sP1hw)|
Security Models|Utreexo|[ELI5: Utreexo](https://medium.com/@kcalvinalvinn/eli5-utreexo-a-scaling-solution-9531aee3d7ba), [A description of research by Thaddeus Dryja](https://dci.mit.edu/utreexo)|
Security Models|Alternative UTXO Set Proposals|[Alternative UTXO Set Proposals seminar video](https://youtu.be/F3BCP0wiYOw)|
Mining|Poisson distribution/Progress-free-ness|[The Poisson Distribution and Poisson Process Explained](https://towardsdatascience.com/the-poisson-distribution-and-poisson-process-explained-4e2cb17d459)|
Mining|Block arrivals in the Bitcoin blockchain|[Block arrivals in the Bitcoin blockchain](https://arxiv.org/pdf/1801.07447.pdf)|
Mining|Fee Sniping| [nSequence and opt-in ReplaceByFee](https://www.reddit.com/r/Bitcoin/comments/47upgx/nsequence_and_optin_replacebyfee_difference/d0g612x/?context=5)|
Mining|Selfish Mining| [On the Instability of Bitcoin Without the Block Reward](https://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf), [Majority is not Enough: Bitcoin Mining is Vulnerable](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf), [How to Mine Bitcoin Profitably - 2015](https://scalingbitcoin.org/transcript/montreal2015/how-to-mine-bitcoin-profitably), [Why Bitcoin Mining Pools Aren’t Incentivized to Broadcast Blocks Quickly](https://bitcoinmagazine.com/articles/why-bitcoin-mining-pools-aren-t-incentivized-to-broadcast-blocks-quickly-1475249510/), [Optimal Selfish Mining Strategies in Bitcoin](http://diyhpl.us/~bryan/papers2/bitcoin/Optimal%20selfish%20mining%20strategies%20in%20bitcoin.pdf), [If There Is an Answer to Selfish Mining, Braiding Could Be It](https://bitcoinmagazine.com/articles/if-there-is-an-answer-to-selfish-mining-braiding-could-be-it-1482876153/)|
Mining|51% attacks|[Bitcoin’s Attack Vectors: 51% Attacks](https://medium.com/chainrift-research/bitcoins-attack-vectors-51-attacks-a96deac43774)|
Mining|BetterHash|[BetterHash Mining Protocol(s)](https://github.com/TheBlueMatt/bips/blob/betterhash/bip-XXXX.mediawiki)|
Mining|No Reward Mining Overview|[On the Instability of Bitcoin Without the Block Reward](http://randomwalker.info/publications/mining_CCS.pdf)|
Mining|Pool overview|[Analysis of Bitcoin Pooled Mining Reward Systems](http://diyhpl.us/~bryan/papers2/bitcoin/Analysis%20of%20Bitcoin%20pooled%20mining%20reward%20systems%20-%20Rosenfeld%20-%202011.pdf)|
Mining|Pool Hopping|[Pay Per Last (luck) N Shares - PPLNS](https://bitcointalk.org/index.php?topic=39832)|
Mining|PPS As a Real-World Business Solution|[Pooled mining](https://en.bitcoin.it/wiki/Pooled_mining#The_Pay-per-Share_approach)|
Mining|Trustless Pools|[P2Pool](https://en.bitcoin.it/wiki/P2Pool)|
Mining|Payment Channel Payouts|[Payment Channel Payouts: An Idea for Improving P2Pool Scalability](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-August/014893.html)|
Mining|ASICBoost|[AsicBoost: A Speedup for Bitcoin Mining](https://arxiv.org/pdf/1604.00575.pdf), [The Problem with ASICBOOST](http://www.mit.edu/~jlrubin//public/pdfs/Asicboost.pdf), [Inhibiting a covert attack on the Bitcoin POW function](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-April/013996.html)|
Mining|BCH Mining/Difficulty Adjustment|[Bringing Stability to Bitcoin Cash Difficulty Adjustments](https://medium.com/@Mengerian/bringing-stability-to-bitcoin-cash-difficulty-adjustments-eae8def0efa4), [Bitcoin Cash Difficulty Adjustments](https://medium.com/@jimmysong/bitcoin-cash-difficulty-adjustments-2ec589099a8e), [Difficulty Adjustment Algorithm Update](https://www.bitcoinabc.org/2017-11-01-DAA/)|
Mining|Tumblebit|[TumbleBit: An Untrusted Bitcoin-Compatible Anonymous Payment Hub](https://open.bu.edu/bitstream/handle/2144/29224/575.pdf?sequence=2&isAllowed=y)|
Attacks|Dust attacks|[Dust Attacks](https://medium.com/chainrift-research/bitcoins-attack-vectors-dust-attacks-9040edee2986)|
Consensus approaches|Overview|[On Consensus](https://medium.com/scalar-capital/on-consensus-e47920cd8914)|
Consensus approaches|GHOST|[The GHOSTDAG protocol](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/ghostdag/), [Secure High-Rate Transaction Processing in Bitcoin](https://eprint.iacr.org/2013/881.pdf), [Modified GHOST Implementation](https://github.com/ethereum/wiki/wiki/White-Paper#modified-ghost-implementation)|
Consensus approaches|Braiding|[Braiding the blockchain](https://diyhpl.us/wiki/transcripts/scalingbitcoin/hong-kong/braiding-the-blockchain/)|
Consensus approaches|Byzantine Fault Tolerance|[Byzantine Fault Tolerance](https://medium.com/loom-network/understanding-blockchain-fundamentals-part-1-byzantine-fault-tolerance-245f46fe8419)|
Consensus approaches|Bitcoin-NG/PoW+BFT|[Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf)|
Consensus approaches|Proof of Stake|[Proof of Work & Proof of Stake](https://medium.com/loom-network/understanding-blockchain-fundamentals-part-2-proof-of-work-proof-of-stake-b6ae907c7edb), [Proof-of-Stake & the Wrong Engineering Mindset](https://medium.com/@hugonguyen/proof-of-stake-the-wrong-engineering-mindset-15e641ab65a2)|
Consensus approaches|Sidechains|[Enabling Blockchain Innovations with Pegged Sidechains](https://blockstream.com/sidechains.pdf), [Sidechains](https://diyhpl.us/wiki/transcripts/scalingbitcoin/milan/sidechains/), [Proof-of-Work Sidechains](http://diyhpl.us/~bryan/papers2/bitcoin/Proof-of-Work%20sidechains%20-%202018.pdf)|
Consensus Changes & Hard Forks|History|[A complete history of Bitcoin’s consensus forks](https://blog.bitmex.com/bitcoins-consensus-forks/), [March 2013 Chain Fork Post-Mortem](https://github.com/bitcoin/bips/blob/master/bip-0050.mediawiki)|
Consensus Changes & Hard Forks|Extension blocks|[Auxiliary block: Increasing max block size with softfork](https://bitcointalk.org/index.php?topic=283746.0), [How Bitcoin Extension Blocks Are Backward Compatible — and How They’re Not](https://bitcoinmagazine.com/articles/how-extension-blocks-are-backward-compatible-and-how-theyre-not/)|
Consensus Changes & Hard Forks|Hard forks: Potential dangers|[Network Partitioning](https://medium.com/@jimmysong/network-partitioning-321b7f159868)|
Consensus Changes & Hard Forks|Replay protection|[Replay Attacks Explained](https://bitcointechtalk.com/replay-attacks-explained-e3d6d2ea0ab2), [How to Protect Against Replay Attacks](https://bitcointechtalk.com/how-to-protect-against-replay-attacks-7a00bd2fe52f), [2017_optin_replay code on btc1](https://github.com/btc1/bitcoin/commit/a3c41256984bf11d95a560ae89c0fcbadfbe73dc)|
Consensus Changes & Hard Forks|Wipeout protection||
Consensus Changes & Hard Forks|Light nodes|[Lightweight node wiki page](https://en.bitcoin.it/wiki/Lightweight_node)|
Consensus Changes & Hard Forks|Current research (spoonnet, etc)|[Spoonnet: another experimental hardfork](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-February/013542.html)|
Cryptography|The 3 Seminal Events In Cryptography|[The 3 Seminal Events In Cryptography](http://doctrina.org/The-3-Seminal-Events-In-Cryptography.html)|
Cryptography|An Overview of Public Key Cryptography|[An Overview of Public Key Cryptography](https://ee.stanford.edu/~hellman/publications/31.pdf)|
Cryptography|Finite fields, Elliptic Curves, ECDSA, Schnorr| [Finite fields, Elliptic Curves, ECDSA, Schnorr Cryptography](https://www.youtube.com/watch?v=DcGm_4-ig1o), [Elliptic Curve Cryptography Explained](https://fangpenlin.com/posts/2019/10/07/elliptic-curve-cryptography-explained/)|
Cryptography|Bitcoin, Chance and Randomness|[Bitcoin, Chance and Randomness](https://medium.com/@hugonguyen/bitcoin-chance-and-randomness-ba49a6edf933)|
Cryptography|On Bitcoin Security in the Presence of Broken Crypto Primitives|[On Bitcoin Security in the Presence of Broken Crypto Primitive](http://diyhpl.us/~bryan/papers2/bitcoin/On%20Bitcoin%20security%20in%20the%20presence%20of%20broken%20crypto%20primitives%20-%202016.pdf)|
Cryptography|Signatures and zero-knowledge proofs|[State of Cryptography - beyond ECDSA and sha256](https://scalingbitcoin.org/transcript/stanford2017/state-of-cryptography)|
Cryptography|zero knowledge proofs|[Introduction to SNARKs](https://www.youtube.com/watch?v=jr95o_k_SwI&feature=youtu.be)|
Cryptography|Bulletproofs|[How Bulletproofs Could Make Bitcoin Privacy Less Costly](https://bitcoinmagazine.com/articles/how-bulletproofs-could-make-bitcoin-privacy-less-costly/), [Bulletproofs: Faster Rangeproofs and Much More](https://blockstream.com/2018/02/21/bulletproofs-faster-rangeproofs-and-much-more/),  [Building on Bulletproofs](https://medium.com/@cathieyun/building-on-bulletproofs-2faa58af0ba8)|
Cryptography|Commitment schemes; pedersen commitments|[Commitment schemes](https://storage.googleapis.com/dev.adjoint.io/crypto.html#commitment-schemes), [Non-Interactive and Information- Theoretic Secure Verifiable Secret Sharing](https://www.cs.cornell.edu/courses/cs754/2001fa/129.PDF)|
Cryptography|Schnorr| [Introduction to Schnorr Signatures (video)](https://youtu.be/XKatSGCZ-gE), [Simple Schnorr Multi-Signatures with Applications to Bitcoin](https://eprint.iacr.org/2018/068.pdf), [Liars, cheats, scammers and the Schnorr signature](https://joinmarket.me/blog/blog/liars-cheats-scammers-and-the-schnorr-signature/)|
Cryptography|Diffie-Hellman|[Diffie-Hellman Key Exchange: A Non-mathematician’s explanation](https://community.cisco.com/legacyfs/online/legacy/3/5/6/26653-dh.PDF)|
Cryptography|Ring Signatures|[Ring signatures](https://joinmarket.me/blog/blog/ring-signatures/)|
Cryptography|RSA|[How RSA Works With Examples](http://doctrina.org/How-RSA-Works-With-Examples.html) |
Transactions|Understanding a Raw Bitcoin Transaction|[Understanding a Raw Bitcoin Transaction](https://medium.com/@marchtodeath/understanding-a-raw-bitcoin-transaction-531193b7e147)|
Transactions|Understanding a Raw Bitcoin Transaction the hard way|[Bitcoins the hard way: Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html)|
Transactions|Working with Transactions |[Working with transactions (bitcoinj)](https://bitcoinj.github.io/working-with-transactions)|
Transactions|Transaction format|[IsMine function in Bitcoin Core](https://github.com/bitcoin/bitcoin/blob/624bee96597c1d59018e58131b8285c0b332700d/src/script/ismine.cpp#L43)|
Transactions|Script|[Bitcoin Developer Reference](https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf#page=16), [Advanced Bitcoin Scripting: Transactions & Multisig](https://www.youtube.com/watch?v=8FeAXjkmDcQ)|
Transactions|Signing transactions|[Why the signature is always 65 (1+32+32) bytes long?](https://bitcoin.stackexchange.com/questions/12554/why-the-signature-is-always-65-13232-bytes-long/12556#12556)|
Transactions|Standardness|[Bitcoin Developer Reference](https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf#page=16), [The Bitcoin Non-standard](https://medium.com/summa-technology/the-bitcoin-non-standard-6103330af98c), [Definition of Standardness](https://github.com/libbitcoin/libbitcoin-server/wiki/Standardness)|
Transactions|0-conf transactions|[Support for zero-confirmation transactions at Bitcoin ATM](https://coinatmradar.com/blog/support-zero-confirmation-transactions-at-bitcoin-atm/), [Solving the 0-conf problem using forfeits](https://gist.github.com/awemany/619a5722d129dec25abf5de211d971bd)|
Transactions|Partially Signed Bitcoin Transactions|[Partially Signed Bitcoin Transactions (video)](https://www.youtube.com/watch?v=H6xZSRDXUiU), [BIP 174](https://github.com/bitcoin/bips/blob/master/bip-0174.mediawiki), [Partially Signed Bitcoin Transactions](https://bitcointechweekly.com/front/bip-174-psbt-partially-signed-bitcoin-transactions/), [PSBT Howto for Bitcoin Core](https://github.com/bitcoin/bitcoin/blob/master/doc/psbt.md), [Partially Signed Bitcoin Transaction (PSBT) format](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-August/014843.html)|
Transactions|SIGHASH_NOINPUT|[BIP sighash_noinput](https://bitcoin-development.narkive.com/PhL7HxZZ/bip-sighash-noinput)|
Transactions|Compacted Transactions|[Compacted Transactions](https://people.xiph.org/~greg/compacted_txn.txt)|
Transactions|Mempool|[How the Mempool Works](https://blog.kaiko.com/an-in-depth-guide-into-how-the-mempool-works-c758b781c608), [Transaction Pools](https://github.com/bitcoinbook/bitcoinbook/blob/f8b883dcd4e3d1b9adf40fed59b7e898fbd9241f/ch08.asciidoc#transaction-pools), [Bitcoin Peer-to-Peer Network](https://youtu.be/eVerdR2hOMw?t=1918)|
Blocks|Merkle Trees|[Bitcoin Developer Reference](https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf#page=16), [Weaknesses in Bitcoin’s Merkle Root Construction](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/attachments/20190225/a27d8837/attachment-0001.pdf)|
Blocks|Data structures in validation|[Validation costs and incentives](https://diyhpl.us/wiki/transcripts/scalingbitcoin/validation-costs/)|
Blocks|Re-orgs|[Handling Re-orgs & Forks](https://www.youtube.com/watch?time_continue=839&v=wtTQ_1WyUoY)|
Blocks|Pruning|[Block file pruning](https://bitcoin.org/en/release/v0.11.0#block-file-pruning), [Add autoprune functionality PR #5863](https://github.com/bitcoin/bitcoin/pull/5863)|
SegWit|SegWit background and history|[Understanding Segregated Witness](https://segwit.org/understanding-segregated-witness-905cc712c692), [Segregated Witness](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc#segregated-witness), [Bitcoin Protocol Design: Segregated Witness Revisited](https://www.youtube.com/watch?v=AjBpIkfB-ac), [Segwit](https://www.youtube.com/watch?v=Txfy2mFe16A), [Segregated Witness Benefits](https://bitcoincore.org/en/2016/01/26/segwit-benefits/), [Segregated Witness Costs and Risks](https://bitcoincore.org/en/2016/10/28/segwit-costs/), [The Long Road to SegWit: How Bitcoin’s Biggest Protocol Upgrade Became Reality](https://bitcoinmagazine.com/articles/long-road-segwit-how-bitcoins-biggest-protocol-upgrade-became-reality/)|
SegWit|Advanced SegWit|[Advanced SegWit seminar video](https://youtu.be/JgNgnwF9hfY) |
SegWit|SegWit and scalabilty|[Segregated Witness and deploying it for Bitcoin (2015)](https://diyhpl.us/wiki/transcripts/scalingbitcoin/hong-kong/segregated-witness-and-its-impact-on-scalability/) |
SegWit|Tx malleability|[Transaction Malleability Explained](https://bitcointechtalk.com/transaction-malleability-explained-b7e240236fc7), [Transaction Malleability Explained, 2014](https://www.youtube.com/watch?v=jyDE-aFqJTs), [The Who, What, Why and How of the Ongoing Transaction Malleability Attack](https://bitcoinmagazine.com/articles/the-who-what-why-and-how-of-the-ongoing-transaction-malleability-attack-1444253640/), [Dealing with malleability](https://github.com/bitcoin/bips/blob/master/bip-0062.mediawiki), [Bitcoin Transaction Malleability and MtGox](https://arxiv.org/pdf/1403.6676.pdf)|
SegWit|Tx malleability|[Malleation code exericse repo](https://github.com/dongcarl/malleability-exercise)|
SegWit|SegWit and blocksize|[Understanding Segwit Block Size](https://medium.com/@jimmysong/understanding-segwit-block-size-fd901b87c9d4)|
SegWit|Bech32|[New address type for segwit addresses](https://diyhpl.us/wiki/transcripts/sf-bitcoin-meetup/2017-03-29-new-address-type-for-segwit-addresses/) |
SegWit|Wallet Development|[Segregated Witness Wallet Development Guide](https://bitcoincore.org/en/segwit_wallet_dev/)|
Wallet|Wallet Development in Bitcoin Core|[Wallet Development in Bitcoin Core seminar video](https://youtu.be/j0V8elTzYAA)|
Wallet|HD wallet|[Hierarchical Deterministic Wallets](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), [Multi-Account Hierarchy for Deterministic Wallets](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), [HD Wallets Explained: From High Level to Nuts and Bolts](https://medium.com/bitcraft/hd-wallets-explained-from-high-level-to-nuts-and-bolts-9a41545f5b0)|
Wallet|Native Descriptor Wallets|[Native Descriptor Wallets](https://gist.github.com/achow101/94d889715afd49181f8efdca1f9faa25)|
Wallet|Wallet BerkeleyDB key value store, data file, environment, logs, flushing|[Migration from Berkeley DB to LevelDB](https://bitcoin.stackexchange.com/questions/51435/migration-from-berkeley-db-to-leveldb), ([also see BIP 50](https://github.com/bitcoin/bips/blob/master/bip-0050.mediawiki))|
Wallet|Wallet key types: Regular, watch-only, hd|[Wallets and Accounts and Keys, Oh My!](http://bcoin.io/guides/wallets.html)|
Wallet|Wallet key management: Keypools, key metadata, address metadata|[Understanding keypool in Bitcoin Core](https://bitcointalk.org/index.php?topic=2940114.msg30228579#msg30228579), [Understanding the Gap Limit](https://blog.blockonomics.co/bitcoin-what-is-this-gap-limit-4f098e52d7e1)|
Wallet|Wallet rescan|[How to rescan / reindex wallet?](https://coinguides.org/rescan-reindex-wallet/)|
Wallet|Fees|[The Fee Market Explained](https://medium.com/@jimmysong/the-fee-market-explained-76b294947b42), [How wallets can handle transaction fees](https://medium.com/@bramcohen/how-wallets-can-handle-transaction-fees-ff5d020d14fb)|
Wallet|Fee estimation|[Fee estimation code exercise](https://youtu.be/PYA1f2xlIOM)|
Wallet|Replace by Fee|[Opt-in Full Replace-by-Fee Signaling](https://github.com/bitcoin/bips/blob/master/bip-0125.mediawiki), [Support for zero-confirmation transactions at Bitcoin ATM](https://coinatmradar.com/blog/support-zero-confirmation-transactions-at-bitcoin-atm/)|
Wallet|Coin selection| [Unspent Management and Coin Selection](https://www.youtube.com/watch?v=hrlNN3BSB6w), [Coin Selection](https://bitcoinedge.org/tutorial/dpp105-karl-johan-alm-bitcoin-wallets-coin-selection), [Coin Selection (Scaling 2016)](https://scalingbitcoin.org/transcript/milan2016/coin-selection), [An Evaluation of Coin Selection Strategies](http://murch.one/wp-content/uploads/2016/11/erhardt2016coinselection.pdf)|
Wallet|Hardware wallets with Bitcoin core|[Using your hardware wallet with Bitcoin Core](https://vimeo.com/316634495)|
Scripts & Contracts|Scripting & Transactions|[Scripts - general & simple video](https://youtu.be/np-SCwkqVy4)|
Scripts & Contracts|Scripting & Transactions|[Bitcoin Script: Past and Future video](https://youtu.be/H-wH6mY9pZo?t=2504)|
Scripts & Contracts|Scripting & Transactions - P2PKH, P2SH, P2WPKH, P2WSH, Bech32|[P2PKH, P2WPKH, P2SH, P2WSH](https://www.youtube.com/watch?time_continue=8&v=nrYOMjVmqi8), [Dissecting a P2PKH Bitcoin Transaction down to the last Byte](https://youtu.be/1n4g3eYX1UI),  [Bitcoin Multisig and P2SH Transactions](https://www.youtube.com/watch?v=K-ccC9YZ8UI)|
Scripts & Contracts|Script Descriptors|[Script descriptors](http://diyhpl.us/wiki/transcripts/bitcoin-core-dev-tech/2018-10-08-script-descriptors/), [Support for Output Descriptors in Bitcoin Core](https://github.com/bitcoin/bitcoin/blob/master/doc/descriptors.md)|
Scripts & Contracts|P2EP|[Improving Privacy Using Pay-to-EndPoint](https://blockstream.com/2018/08/08/improving-privacy-using-pay-to-endpoint/)|
Scripts & Contracts|Smart Contracts on a Dumb Chain; MimbleWimble|[Behind MimbleWimble](https://medium.com/scalar-capital/behind-mimblewimble-cd9da78a00e9)|
Scripts & Contracts|Smart Contracts on a Dumb Chain; scriptless scripts|[ElementsProject/scriptless-scripts](https://github.com/ElementsProject/scriptless-scripts/tree/master/md), [Scriptless Scripts](https://medium.com/scalar-capital/scriptless-scripts-25e18fd52ede?sk=72eb8b17650316ad92b41179006008a7), [Scriptless scripts, adaptor signatures and their applications](https://www.youtube.com/watch?time_continue=2&v=PDzGP621pEs)|
Scripts & Contracts|Payment Channels|[Understanding Payment Channels](https://blog.chainside.net/understanding-payment-channels-4ab018be79d4), [Bitcoin Protocol Design: Payment Channels Revisited](https://www.youtube.com/watch?v=4SdBa8ZOfqg), [Bitcoin script v2.0](https://diyhpl.us/wiki/transcripts/scalingbitcoin/stanford-2017/bitcoin-script-v2.0-and-strengthened-payment-channels/)|
Scripts & Contracts|MAST|[What is a Bitcoin Merklized Abstract Syntax Tree (MAST)?](https://bitcointechtalk.com/what-is-a-bitcoin-merklized-abstract-syntax-tree-mast-33fdf2da5e2f), [Merkleized abstract syntax trees (MAST)](http://diyhpl.us/wiki/transcripts/bitcoin-core-dev-tech/2017-09-07-merkleized-abstract-syntax-trees/), [MAST Discussion](https://diyhpl.us/wiki/transcripts/bitcoin-core-dev-tech/2018-03-06-merkleized-abstract-syntax-trees-mast/)|
Scripts & Contracts|ZK SNARKS|[SNARKS](https://diyhpl.us/wiki/transcripts/scalingbitcoin/snarks/), [Introduction to SNARKs](https://www.youtube.com/watch?v=jr95o_k_SwI&feature=youtu.be), [STARKs: Proofs with Polynomials](https://vitalik.ca/general/2017/11/09/starks_part_1.html)|
Scripts & Contracts|ZK STARKS|[Scalable, transparent, and post-quantum secure computational integrity](https://eprint.iacr.org/2018/046.pdf), [STARKs: Thank Goodness It's FRI-day](https://vitalik.ca/general/2017/11/22/starks_part_2.html), [STARKs: Into the Weeds](https://vitalik.ca/general/2018/07/21/starks_part_3.html), [ZK-STARKs — Create Verifiable Trust, even against Quantum Computers](https://medium.com/coinmonks/zk-starks-create-verifiable-trust-even-against-quantum-computers-dd9c6a2bb13d)|
Scripts & Contracts|Discreet Log Contracts|[Discreet Log Contracts](https://dci.mit.edu/research/smart-contracts-discrete-log-contracts), [Discreet Log Contracts: invisible smart contracts on the Bitcoin blockchain](https://medium.com/@gertjaap/discreet-log-contracts-invisible-smart-contracts-on-the-bitcoin-blockchain-cc8afbdbf0db)|
Scripts & Contracts|Miniscript| [Miniscript](http://diyhpl.us/wiki/transcripts/stanford-blockchain-conference/2019/miniscript/), [Policy to Miniscript compiler](http://bitcoin.sipa.be/miniscript/)|
Scripts & Contracts|State of script|[The State of Script (2018)](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/bitcoin-script/)|
Fungibility & Scalability| Overview | |
Fungibility & Scalability|On Scaling Decentralized Blockchains|[The fundamental tradeoff](https://gist.github.com/chris-belcher/a8155df5051bb3e3aa96), [On Scaling Decentralized Blockchains](http://diyhpl.us/~bryan/papers2/bitcoin/On%20scaling%20decentralized%20blockchains%20-%20A%20position%20paper.pdf)|
Fungibility & Scalability|Why fungibility is important|[Fungibility And Scalability](https://diyhpl.us/wiki/transcripts/scalingbitcoin/hong-kong/fungibility-and-scalability/), [Fungibility overview](https://diyhpl.us/wiki/transcripts/scalingbitcoin/milan/fungibility-overview/), [Fungibility as an Attack Vectors: ](https://medium.com/chainrift-research/bitcoins-attack-vectors-fungibility-ed58cb4cff73)|
Fungibility & Scalability|Privacy|[Different Approaches to Privacy on the Blockchain](https://blockstream.com/2017/09/08/different-approaches-to-privacy/), [Privacy](https://en.bitcoin.it/wiki/Category:Privacy), [Privacy](https://en.bitcoin.it/wiki/Privacy), [How much privacy is enough? Threats, scaling, and trade-offs in blockchain privacy protocols](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/how-much-privacy-is-enough/), [Privacy surrounding the Blockchain](https://medium.com/scalar-capital/privacy-surrounding-the-blockchain-7b92a6deea62)|
Fungibility & Scalability|Chain analysis|[Chainalysis Live Demo](https://www.youtube.com/watch?v=9OtPOQwLBjc), [Let's talk about ChainAnalysis](https://www.reddit.com/r/Bitcoin/comments/70oftr/lets_talk_about_chainanalysis/dn4vxug/?utm_source=share&utm_medium=web2x)|
Fungibility & Scalability|Wallet fingerprinting| [Wallet Fingerprinting (wiki)](https://en.bitcoin.it/wiki/Privacy#Wallet_fingerprinting) |
Fungibility & Scalability|Transaction origin analysis| [A Fistful of Bitcoins: Characterizing Payments Among Men with No Names](http://cseweb.ucsd.edu/~smeiklejohn/files/imc13.pdf)|
Fungibility & Scalability|Coinjoin|[Coinjoin wiki page](https://en.bitcoin.it/wiki/CoinJoin)|
Fungibility & Scalability|Confidential Transactions|[Bitcoins with Homomorphic Value](https://bitcointalk.org/index.php?topic=305791.0), [Confidential Transactions](https://elementsproject.org/features/confidential-transactions), [A Primer to Confidential Transactions](https://medium.com/@ecurrencyhodler/a-primer-to-confidential-transactions-e6ab3dd2bf1e)|
Fungibility & Scalability|Tumblebit|[TumbleBit: An Untrusted Bitcoin-Compatible Anonymous Payment Hub](http://diyhpl.us/~bryan/papers2/bitcoin/TumbleBit:%20An%20untrusted%20bitcoin-compatible%20anonymous%20payment%20hub%20-%202016.pdf), [Tumblebit](https://diyhpl.us/wiki/transcripts/scalingbitcoin/milan/tumblebit/)|
Fungibility & Scalability|Coin Jumble|[Coin Jumble](https://bitcointalk.org/index.php?topic=730321.msg8254585)|
Fungibility & Scalability|Schnorr| [Schnorr Signatures for Bitcoin - BPASE '18](https://blockstream.com/2018/02/15/schnorr-signatures-bpase/), [Flipping the scriptless script on Schnorr](https://joinmarket.me/blog/blog/flipping-the-scriptless-script-on-schnorr/), [Schnorr Signatures](https://medium.com/scalar-capital/schnorr-signatures-754038368b87)|
Fungibility & Scalability|Bellare-Neven|[Multi-Signatures in the Plain Public-Key Model and a General Forking Lemma](https://cseweb.ucsd.edu/~mihir/papers/multisignatures-ccs.pdf)|
Fungibility & Scalability|Threshold Schemes|[Threshold cryptosystem](https://en.wikipedia.org/wiki/Threshold_cryptosystem), [Threshold signatures and accountability](http://diyhpl.us/wiki/transcripts/sf-bitcoin-meetup/2019-02-04-threshold-signatures-and-accountability/)|
Fungibility & Scalability|Signature aggregation|[Signature aggregation for improved scalablity](https://bitcointalk.org/index.php?topic=1377298.0), [Schnorr signatures and signature aggregation](https://bitcoincore.org/en/2017/03/23/schnorr-signature-aggregation/), [BLS Multi-Signatures With Public-Key Aggregation](https://crypto.stanford.edu/~dabo/pubs/papers/BLSmultisig.html)|
Fungibility & Scalability|MuSig|[Key Aggregation for Schnorr Signatures](https://blockstream.com/2018/01/23/musig-key-aggregation-schnorr-signatures/), [MuSig: A New Multisignature Standard](https://blockstream.com/2019/02/18/en-musig-a-new-multisignature-standard/), [Simple Schnorr Multi-Signatures with Applications to Bitcoin](https://eprint.iacr.org/2018/068)|
Fungibility & Scalability|Taproot| [Taproot and Policy (video)](https://youtu.be/EdRm_mnoCWc), [Taproot and graftroot](http://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/edgedevplusplus/taproot-and-graftroot/), [Taproot: SegWit version 1 output spending rules](https://github.com/bitcoin/bips/blob/master/bip-0341.mediawiki)|
Fungibility & Scalability|Graftroot|[Graftroot: Private and efficient surrogate scripts under the taproot assumption](https://bitcoin-development.narkive.com/jqVWWk4l/graftroot-private-and-efficient-surrogate-scripts-under-the-taproot-assumption)|
The P2P Network|Overview of the p2p network|[Bitcoin Peer-to-Peer Network](https://youtu.be/eVerdR2hOMw)|
The P2P Network|Overview of the p2p network|[Adversarial Thinking in the Peer-to-Peer Network - first 41:29](https://youtu.be/H-wH6mY9pZo)|
The P2P Network|P2P Design| [Undocumented P2P Design of Bitcoin Core](https://residency.chaincode.com/presentations/bitcoin/P2P_Design_Bitcoin_Core.pdf)|
The P2P Network|Transaction propagation|[On Bitcoin and Red Balloons (incentives)](https://arxiv.org/pdf/1111.2626.pdf)|
The P2P Network|Headers-first sync'ing| [Headers-First Sync (wiki)](https://btcinformation.org/en/developer-guide#headers-first) |
The P2P Network|Advances in Block propagation|[Advances in block propagation](https://diyhpl.us/wiki/transcripts/gmaxwell-2017-11-27-advances-in-block-propagation/)|
The P2P Network|Compact blocks|[Compact Blocks FAQ](https://bitcoincore.org/en/2016/06/07/compact-blocks-faq/), [Compact Block Relay](https://github.com/bitcoin/bips/blob/master/bip-0152.mediawiki)|
The P2P Network|Relay networks, FIBRE|[Relay networks](https://diyhpl.us/wiki/transcripts/scalingbitcoin/relay-network/), [The Future of The Bitcoin Relay Network](https://bluematt.bitcoin.ninja/2016/07/07/relay-networks/), [What is FIBRE?](http://bitcoinfibre.org)|
The P2P Network|Deanonymization in the Bitcoin P2P Network|[Deanonymization in the Bitcoin P2P Network](https://papers.nips.cc/paper/6735-deanonymization-in-the-bitcoin-p2p-network.pdf)|
The P2P Network|Dandelion|[Dandelion: Redesigning the Bitcoin Network for Anonymity](https://arxiv.org/pdf/1701.04439.pdf), [Dandelion++: Lightweight Cryptocurrency Networking with Formal Anonymity Guarantees](https://arxiv.org/pdf/1805.11060.pdf), [What is the tradeoff between privacy and implementation complexity of Dandelion?](https://bitcoin.stackexchange.com/questions/81503/what-is-the-tradeoff-between-privacy-and-implementation-complexity-of-dandelion)|
The P2P Network|Peer discovery|[Network Discovery](https://github.com/bitcoinbook/bitcoinbook/blob/f8b883dcd4e3d1b9adf40fed59b7e898fbd9241f/ch08.asciidoc#network-discovery)|
The P2P Network|Topology Discovery|[Discovering Bitcoin’s Public Topology and Influential Nodes](https://www.cs.umd.edu/projects/coinscope/coinscope.pdf), [TxProbe: Discovering Bitcoin's Network Topology Using Orphan Transactions](https://arxiv.org/abs/1812.00942)|
The P2P Network|Peer connectivity||
The P2P Network|BGP Hijack|[Hijacking Bitcoin: Routing Attacks on Cryptocurrencies](https://btc-hijack.ethz.ch/)|
The P2P Network|Network partitioning & network level privacy attacks|[Network partitioning & network level privacy attacks seminar video](https://btc-hijack.ethz.ch/)|
The P2P Network|Researching P2P privacy attacks|[Researching P2P privacy attacks seminar video](https://youtu.be/qKNEUfnYue0)|
The P2P Network|Eclipse Attacks on Bitcoin’s Peer-to-Peer Network (2015)| [Eclipse Attacks on Bitcoin’s Peer-to-Peer Network](https://eprint.iacr.org/2015/263.pdf), [Eclipse Attacks on Bitcoin’s Peer-to-Peer Network (video)](https://www.usenix.org/node/190891)|
The P2P Network|Denial-of-Service concepts| [Denial of Service (DoS) attacks wiki](https://en.bitcoin.it/wiki/Weaknesses#Denial_of_Service_.28DoS.29_attacks), [Network Splits](https://bitcoin.stackexchange.com/questions/1738/what-would-happen-if-a-portion-of-the-bitcoin-network-was-separated-from-the-res), ["High horsepower" attacks](https://bitcoin.stackexchange.com/questions/8738/feasibility-of-a-high-horsepower-attack-based-on-difficulty-4x-adjustments)|
The P2P Network|Denial-of-Service Prevention|[Denial of Service (DoS) Prevention](https://github.com/bitcoin/bitcoin/pull/517), [DoS countermeasures may facilitate network fragmentation attacks](https://bitcointalk.org/index.php?topic=44954.0)|
The P2P Network|SPV nodes|[Future of SPV tech](https://diyhpl.us/wiki/transcripts/scalingbitcoin/future-of-spv-tech/)|
The P2P Network|MiniSketch|[Minisketch: Reducing Bitcoin Node Bandwidth Requirements](https://blockstream.com/2019/01/07/minisketch-reducing-node-bandwidth-requirements/), [Minisketch: an optimized library for BCH-based set reconciliation](https://github.com/sipa/minisketch)|
Chain Forks and Failures|BIP 66 Fork and spy mining|[Strict DER signatures](https://github.com/bitcoin/bips/blob/master/bip-0066.mediawiki), [What is SPV mining, and how did it (inadvertently) cause the fork after BIP66 was activated?](https://bitcoin.stackexchange.com/questions/38437/what-is-spv-mining-and-how-did-it-inadvertently-cause-the-fork-after-bip66-wa)|
Bitcoin Core Architecture|Architecture overview|[An overview of Bitcoin Core architecture (video)](https://www.youtube.com/watch?v=L_sI_tXmy2U)|
Bitcoin|Learning-Bitcoin-from-the-Command-Line|[Programming with Bitcoin Core and Lightning](https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line)|
Bitcoin Core Contribution|Contributing to Core|[Contributing to Bitcoin Core](https://github.com/bitcoin/bitcoin/blob/master/CONTRIBUTING.md), [Introduction to Bitcoin Development](https://rubin.io/talks/2017/02/01/intro-bitcoin-dev-jp/), [Contributing to Bitcoin Core, a personal account](https://bitcointechtalk.com/contributing-to-bitcoin-core-a-personal-account-35f3a594340b), [Onboarding to Bitcoin Core](https://medium.com/@amitiu/onboarding-to-bitcoin-core-7c1a83b20365)|
Bitcoin Core Contribution|Debugging Bitcoin Core|[Debugging Bitcoin Core (video)](https://youtu.be/6aPSCDAiqVI)
