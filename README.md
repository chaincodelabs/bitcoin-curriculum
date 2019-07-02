# Bitcoin Curriculum

| Subject                       | Topic  | Sources |
|-------------------------------|--------|---------|
Introduction|White Paper|https://bitcoin.org/bitcoin.pdf|
Introduction|If I'd Known What We Were Starting (2017)|https://www.linkedin.com/pulse/id-known-what-we-were-starting-ray-dillinger/|
Introduction|Bitcoin's Academic Pedigree (2017)|https://queue.acm.org/detail.cfm?id=3136559|
Introduction|What is blockchain anyway?|https://www.youtube.com/watch?v=on5ySFK0aoY|
Introduction|The Economic Limits of Bitcoin and the Blockchain|https://faculty.chicagobooth.edu/eric.budish/research/Economic-Limits-Bitcoin-Blockchain.pdf|
Introduction|Proof of work|https://bitcointechtalk.com/the-anatomy-of-proof-of-work-98c85b6f6667 https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf|
Introduction|Difficulty adjustment|https://bitcoin.stackexchange.com/questions/855/what-keeps-the-average-block-time-at-10-minutes/857#857|
Introduction|byzantine generals problem|http://diyhpl.us/~bryan/papers2/bitcoin/The%20Byzantine%20generals%20problem%20-%20Lamport%20-%201982.pdf|
Introduction|Running a full node|https://www.reddit.com/r/BitcoinBeginners/comments/3eq3y7/full_node_question/ctk4lnd/|
History & Philosophy of Bitcoin|What is consensus? (Consensus Algorithms, Blockchain Technology and Bitcoin UCL (2016))| https://www.youtube.com/watch?v=fw3WkySh_Ho&t=10s|
Soft Forks & protocol overview|On Unstoppability of Softforks|https://zmnscpxj.github.io/bitcoin/unpreventable-softforks.html|
Soft Forks & protocol overview|Upgrading the protocol||
Soft Forks & protocol overview|Example soft forks|https://en.bitcoin.it/wiki/Softfork|
Soft Forks & protocol overview|Forking signaling and Activation|https://medium.com/@elombrozo/forks-signaling-and-activation-d60b6abda49a|
Soft Forks & protocol overview|Fork categorization (soft, hard, evil, etc.)|http://www.truthcoin.info/blog/protocol-upgrade-terminology/ https://petertodd.org/2016/forced-soft-forks|
Soft Forks & protocol overview|Flag day upgrades|https://medium.com/@bergealex4/uasf-user-driven-protocol-development-da4e886832d|
Soft Forks & protocol overview|IsSuperMajority signaling|https://github.com/bitcoin/bips/blob/master/bip-0065.mediawiki|
Soft Forks & protocol overview|BIP9 signaling|https://rusty.ozlabs.org/?p=576 https://github.com/bitcoin/bips/blob/master/bip-0009.mediawiki|
Soft Forks & protocol overview|BIP148 and BIP149|https://github.com/bitcoin/bips/blob/master/bip-0148.mediawiki https://github.com/bitcoin/bips/blob/master/bip-0149.mediawiki https://medium.com/@jimmysong/uasf-bip148-scenarios-and-game-theory-9530336d953e https://segwit.org/user-activated-soft-forks-the-bip-148-alternative-28e87ffdb76f|
Soft Forks & protocol overview|BIP91|https://github.com/bitcoin/bips/blob/master/bip-0091.mediawiki|
Security Models|Overview|https://diyhpl.us/wiki/transcripts/scalingbitcoin/overview-of-security-concerns/ https://vimeo.com/316625785#t=750s https://www.coindesk.com/bitcoins-security-model-deep-dive https://en.bitcoin.it/wiki/Weaknesses https://pdfs.semanticscholar.org/ac1a/918fc933b767d34574ec2cc6a33b4223dc1a.pdf|
Security Models|Checkpoints, assumevalid, minimumchainwork|https://bluematt.bitcoin.ninja/2017/02/28/bitcoin-trustlessness/ https://twitter.com/hrdng/status/869206705548271616|
Security Models|Defining SPV and lightclients|https://gist.github.com/ariard/1034cd7624805d53334e80d4712fb8ee|
Security Models|BIP 37 (bloom filters)|https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki https://eprint.iacr.org/2014/763.pdf|
Security Models|Neutrino |https://github.com/bitcoin/bips/blob/master/bip-0157.mediawiki https://blog.lightning.engineering/posts/2018/10/17/neutrino.html https://github.com/bitcoin/bitcoin/pull/14121 https://vimeo.com/316626387|
Security Models|Committed bloom filters|https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2016-May/012636.html|
Security Models|Fraud proofs|https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/fraud-proofs/ https://gist.github.com/justusranvier/451616fa4697b5f25f60 https://download.wpsoftware.net/bitcoin/wizards/2015-04-18.html https://people.xiph.org/~greg/bitcoin-wizards-fraud-proof.log.txt https://www.mail-archive.com/bitcoin-dev@lists.linuxfoundation.org/msg07913.html|
Security Models|Committed UTXO hashes|https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-October/011638.html|
Security Models|Assume UTXO|https://gist.github.com/jamesob/4698f209fd5fb2984bc46ea931fa3e09|
Mining|Poisson distribution/Progress-free-ness|https://towardsdatascience.com/the-poisson-distribution-and-poisson-process-explained-4e2cb17d459|
Mining|Block arrivals in the Bitcoin blockchain|https://arxiv.org/pdf/1801.07447.pdf|
Mining|Fee Sniping|https://www.reddit.com/r/Bitcoin/comments/47upgx/nsequence_and_optin_replacebyfee_difference/d0g612x/?context=5|
Mining|Selfish Mining|https://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf https://scalingbitcoin.org/transcript/montreal2015/how-to-mine-bitcoin-profitably https://bitcoinmagazine.com/articles/why-bitcoin-mining-pools-aren-t-incentivized-to-broadcast-blocks-quickly-1475249510/ http://diyhpl.us/~bryan/papers2/bitcoin/Optimal%20selfish%20mining%20strategies%20in%20bitcoin.pdf https://bitcoinmagazine.com/articles/if-there-is-an-answer-to-selfish-mining-braiding-could-be-it-1482876153/|
Mining|Default next-block selection||
Mining|51% attacks|https://medium.com/chainrift-research/bitcoins-attack-vectors-51-attacks-a96deac43774|
Mining|BetterHash|https://github.com/TheBlueMatt/bips/blob/betterhash/bip-XXXX.mediawiki|
Mining|No Reward Mining Overview|http://randomwalker.info/publications/mining_CCS.pdf|
Mining|Pool overview|http://diyhpl.us/~bryan/papers2/bitcoin/Analysis%20of%20Bitcoin%20pooled%20mining%20reward%20systems%20-%20Rosenfeld%20-%202011.pdf|
Mining|Pool Hopping -> PPLNS|https://bitcointalk.org/index.php?topic=39832|
Mining|PPS As a Real-World Business Solution|https://en.bitcoin.it/wiki/Pooled_mining#The_Pay-per-Share_approach|
Mining|Trustless Pools|https://en.bitcoin.it/wiki/P2Pool|
Mining|Payment Channel Payouts|https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-August/014893.html|
Mining|ASICBoost|https://arxiv.org/pdf/1604.00575.pdf http://www.mit.edu/~jlrubin//public/pdfs/Asicboost.pdf https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-April/013996.html|
Mining|BCH Mining/Difficulty Adjustment|https://medium.com/@Mengerian/bringing-stability-to-bitcoin-cash-difficulty-adjustments-eae8def0efa4 https://medium.com/@jimmysong/bitcoin-cash-difficulty-adjustments-2ec589099a8e https://www.bitcoinabc.org/2017-11-01-DAA/|
Mining|Network partitioning attacks and network level privacy attacks||
Mining|Sybil attacks|http://diyhpl.us/~bryan/papers2/bitcoin/The%20sybil%20attack.pdf http://diyhpl.us/~bryan/papers2/bitcoin/On%20Bitcoin%20and%20red%20balloons.pdf|
Mining|Tumblebit|https://open.bu.edu/bitstream/handle/2144/29224/575.pdf?sequence=2&isAllowed=y|
Attacks|Dust attacks|https://medium.com/chainrift-research/bitcoins-attack-vectors-dust-attacks-9040edee2986|
Consensus approaches|On consensus|https://medium.com/scalar-capital/on-consensus-e47920cd8914|
Consensus approaches|GHOST|https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/ghostdag/ https://eprint.iacr.org/2013/881.pdf https://github.com/ethereum/wiki/wiki/White-Paper#modified-ghost-implementation|
Consensus approaches|Braiding|https://diyhpl.us/wiki/transcripts/scalingbitcoin/hong-kong/braiding-the-blockchain/|
Consensus approaches|BFT|https://medium.com/loom-network/understanding-blockchain-fundamentals-part-1-byzantine-fault-tolerance-245f46fe8419|
Consensus approaches|Bitcoin-NG/PoW+BFT|https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf|
Consensus approaches|PoS|https://medium.com/loom-network/understanding-blockchain-fundamentals-part-2-proof-of-work-proof-of-stake-b6ae907c7edb https://medium.com/@hugonguyen/proof-of-stake-the-wrong-engineering-mindset-15e641ab65a2|
Consensus approaches|Sidechains|https://blockstream.com/sidechains.pdf https://diyhpl.us/wiki/transcripts/scalingbitcoin/milan/sidechains/ http://diyhpl.us/~bryan/papers2/bitcoin/Proof-of-Work%20sidechains%20-%202018.pdf|
Consensus Changes & Hard Forks|Fork categorization|https://blog.bitmex.com/bitcoins-consensus-forks/|
Consensus Changes & Hard Forks|Extension blocks|https://bitcointalk.org/index.php?topic=283746.0 https://bitcoinmagazine.com/articles/how-extension-blocks-are-backward-compatible-and-how-theyre-not/|
Consensus Changes & Hard Forks|Hard forks: Potential dangers|https://medium.com/@jimmysong/network-partitioning-321b7f159868|
Consensus Changes & Hard Forks|Replay protection|https://bitcointechtalk.com/replay-attacks-explained-e3d6d2ea0ab2 https://bitcointechtalk.com/how-to-protect-against-replay-attacks-7a00bd2fe52f https://github.com/btc1/bitcoin/commit/a3c41256984bf11d95a560ae89c0fcbadfbe73dc|
Consensus Changes & Hard Forks|Wipeout protection||
Consensus Changes & Hard Forks|Light nodes|https://en.bitcoin.it/wiki/Lightweight_node|
Consensus Changes & Hard Forks|Current research (spoonnet, etc)|https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-February/013542.html|
Cryptography|The 3 Seminal Events In Cryptography|http://doctrina.org/The-3-Seminal-Events-In-Cryptography.html|
Cryptography|An Overview of Public Key Cryptography|https://ee.stanford.edu/~hellman/publications/31.pdf|
Cryptography|Finite fields, Elliptic Curves, ECDSA, Schnorr|https://www.youtube.com/watch?v=DcGm_4-ig1o|
Cryptography|Bitcoin, Chance and Randomness|https://medium.com/@hugonguyen/bitcoin-chance-and-randomness-ba49a6edf933|
Cryptography|libsecp|https://scalingbitcoin.org/transcript/stanford2017/state-of-cryptography https://www.youtube.com/watch?v=DcGm_4-ig1o|
Cryptography|State of cryptography for blockchains beyond ECDSA and sha256|https://diyhpl.us/wiki/transcripts/scalingbitcoin/stanford-2017/state-of-cryptography/|
Cryptography|On Bitcoin Security in the Presence of Broken Crypto Primitives|http://diyhpl.us/~bryan/papers2/bitcoin/On%20Bitcoin%20security%20in%20the%20presence%20of%20broken%20crypto%20primitives%20-%202016.pdf|
Cryptography|zero knowledge proofs|https://www.youtube.com/watch?v=jr95o_k_SwI&feature=youtu.be|
Cryptography|Bulletproofs|https://bitcoinmagazine.com/articles/how-bulletproofs-could-make-bitcoin-privacy-less-costly/ https://blockstream.com/2018/02/21/bulletproofs-faster-rangeproofs-and-much-more/ https://joinmarket.me/blog/blog/bulletpoints-on-bulletproofs/ https://joinmarket.me/blog/blog/from-zero-knowledge-proofs-to-bulletproofs-paper/ https://medium.com/@cathieyun/building-on-bulletproofs-2faa58af0ba8|
Cryptography|Commitment schemes; pedersen commitments|https://www.adjoint.io/docs/cryptography.html#commitment-schemes https://www.cs.cornell.edu/courses/cs754/2001fa/129.PDF|
Cryptography|Schnorr|https://eprint.iacr.org/2018/068.pdf https://joinmarket.me/blog/blog/liars-cheats-scammers-and-the-schnorr-signature/|
Cryptography|Diffie-Hellman|http://academic.regis.edu/cias/ia/palmgren_-_diffie-hellman_key_exchange.pdf|
Cryptography|Ring Signatures|https://joinmarket.me/blog/blog/ring-signatures/
Cryptography|RSA|http://doctrina.org/How-RSA-Works-With-Examples.html
Cryptography|MORE.... accumulators, etc||
Transactions|Understanding a Raw Bitcoin Transaction|https://medium.com/@marchtodeath/understanding-a-raw-bitcoin-transaction-531193b7e147|
Transactions|Understanding a Raw Bitcoin Transaction the hard way|http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html|
Transactions|Working with Transactions |https://bitcoinj.github.io/working-with-transactions|
Transactions|Transaction format|https://github.com/bitcoin/bitcoin/blob/624bee96597c1d59018e58131b8285c0b332700d/src/script/ismine.cpp#L43|
Transactions|Script|https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf#page=16&zoom=100|0|140 https://www.youtube.com/watch?v=8FeAXjkmDcQ|
Transactions|Signing transactions|https://bitcoin.stackexchange.com/questions/12554/why-the-signature-is-always-65-13232-bytes-long/12556#12556|
Transactions|Data structures and serialization||
Transactions|Softforks using the script language||
Transactions|Standardness|https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf#page=16&zoom=100|0|140 https://medium.com/summa-technology/the-bitcoin-non-standard-6103330af98c https://github.com/libbitcoin/libbitcoin-server/wiki/Standardness|
Transactions|Standard transaction types||
Transactions|0-conf transactions|https://coinatmradar.com/blog/support-zero-confirmation-transactions-at-bitcoin-atm/ https://gist.github.com/awemany/619a5722d129dec25abf5de211d971bd|
Transactions|PSBT|https://www.youtube.com/watch?v=H6xZSRDXUiU https://github.com/bitcoin/bips/blob/master/bip-0174.mediawiki https://bitcointechweekly.com/front/bip-174-psbt-partially-signed-bitcoin-transactions/ https://github.com/bitcoin/bitcoin/blob/master/doc/psbt.md https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-August/014843.html|
Transactions|SIGHASH_NOINPUT|https://bitcoin-development.narkive.com/PhL7HxZZ/bip-sighash-noinput|
Transactions|Compacted Transactions|https://people.xiph.org/~greg/compacted_txn.txt|
Transactions|Mempool|https://github.com/bitcoinbook/bitcoinbook/blob/f8b883dcd4e3d1b9adf40fed59b7e898fbd9241f/ch08.asciidoc#transaction-pools https://youtu.be/eVerdR2hOMw?t=1918|
Blocks|Blocks overview||
Blocks|Merkle Trees|https://lopp.net/pdf/Bitcoin_Developer_Reference.pdf#page=16&zoom=100|0|140 https://lists.linuxfoundation.org/pipermail/bitcoin-dev/attachments/20190225/a27d8837/attachment-0001.pdf|
Blocks|Data structures in validation|https://diyhpl.us/wiki/transcripts/scalingbitcoin/validation-costs/|
Blocks|On disk data structures||
Blocks|Re-orgs|https://www.youtube.com/watch?time_continue=839&v=wtTQ_1WyUoY|
Blocks|Pruning|https://bitcoin.org/en/release/v0.11.0#block-file-pruning https://github.com/bitcoin/bitcoin/pull/5863|
Segwit|Segwit|https://segwit.org/understanding-segregated-witness-905cc712c692 (5 min| primer) https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc#segregated-witness (25 min) https://www.youtube.com/watch?v=AjBpIkfB-ac (7 min video| technical) https://www.youtube.com/watch?v=Txfy2mFe16A (27 min video| technical) https://bitcoincore.org/en/2016/01/26/segwit-benefits/ (12 min| technical) https://bitcoincore.org/en/2016/10/28/segwit-costs/ (20 min) https://bitcoinmagazine.com/articles/long-road-segwit-how-bitcoins-biggest-protocol-upgrade-became-reality/ (20 min| SegWit history)|
Segwit|Segwit and scalabilty|https://diyhpl.us/wiki/transcripts/scalingbitcoin/hong-kong/segregated-witness-and-its-impact-on-scalability/ (30 min video| 2015| conceptual)|
Segwit|Tx malleability|https://bitcointechtalk.com/transaction-malleability-explained-b7e240236fc7 (5 min| tx malleability primer) https://www.youtube.com/watch?v=jyDE-aFqJTs (first 21 min of video| malleability| 2014) https://bitcoinmagazine.com/articles/the-who-what-why-and-how-of-the-ongoing-transaction-malleability-attack-1444253640/ (9 min| 2015 tx malleability attack) https://github.com/bitcoin/bips/blob/master/bip-0062.mediawiki (8 min| withdrawl BIP| 2014) https://arxiv.org/pdf/1403.6676.pdf (25 min| Mt. Gox and tx Malleability| optional)|
Segwit|Segwit and blocksize|https://medium.com/@jimmysong/understanding-segwit-block-size-fd901b87c9d4 (10 min| block size primer)|
Segwit|Bech32|https://diyhpl.us/wiki/transcripts/sf-bitcoin-meetup/2017-03-29-new-address-type-for-segwit-addresses/ (35 min video| bech32)|
Segwit|Wallet Development|https://bitcoincore.org/en/segwit_wallet_dev/ (10 min| technical)|
Wallet|HD wallet|https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki https://medium.com/bitcraft/hd-wallets-explained-from-high-level-to-nuts-and-bolts-9a41545f5b0|
Wallet|Wallet BerkeleyDB key value store, data file, environment, logs, flushing|https://bitcoin.stackexchange.com/questions/51435/migration-from-berkeley-db-to-leveldb|
Wallet|Wallet key types: Regular, watch-only, hd|http://bcoin.io/guides/wallets.html|
Wallet|Wallet key management: Keypools, key metadata, address metadata|https://bitcointalk.org/index.php?topic=2940114.msg30228579#msg30228579|
Wallet|Wallet transaction tracking, mempool and block notifications||
Wallet|Wallet rescan|https://coinguides.org/rescan-reindex-wallet/|
Wallet|Wallet transaction creation: ATMP||
Wallet|Wallet transaction metadata, getbalance, time received, confirmations, IsTrusted||
Wallet|Wallet upgrade||
Wallet|Segwit wallet development|https://bitcoincore.org/en/segwit_wallet_dev/|
Wallet|Fees, fee estimation|https://medium.com/@jimmysong/the-fee-market-explained-76b294947b42 https://medium.com/@bramcohen/how-wallets-can-handle-transaction-fees-ff5d020d14fb|
Wallet|RBF|https://github.com/bitcoin/bips/blob/master/bip-0125.mediawiki https://coinatmradar.com/blog/support-zero-confirmation-transactions-at-bitcoin-atm/|
Wallet|Coin selection|https://bitcoinedge.org/tutorial/dpp105-karl-johan-alm-bitcoin-wallets-coin-selection https://scalingbitcoin.org/transcript/milan2016/coin-selection http://murch.one/wp-content/uploads/2016/11/erhardt2016coinselection.pdf|
Wallet|Hardware wallets with Bitcoin core|https://vimeo.com/316634495|
Scripts & Contracts|Scripting (General and simple)|https://www.youtube.com/watch?time_continue=2&v=np-SCwkqVy4|
Scripts & Contracts|Scripting & Transactions - P2PKH, P2SH, P2WPKH, P2WSH, Bech32|https://www.youtube.com/watch?time_continue=8&v=nrYOMjVmqi8 https://www.youtube.com/watch?v=K-ccC9YZ8UI|
Scripts & Contracts|Script Descriptors|http://diyhpl.us/wiki/transcripts/bitcoin-core-dev-tech/2018-10-08-script-descriptors/ https://github.com/bitcoin/bitcoin/blob/master/doc/descriptors.md|
Scripts & Contracts|P2EP|https://blockstream.com/2018/08/08/improving-privacy-using-pay-to-endpoint/|
Scripts & Contracts|Smart Contracts on a Dumb Chain; Mimblewimble|https://medium.com/scalar-capital/behind-mimblewimble-cd9da78a00e9|
Scripts & Contracts|Smart Contracts on a Dumb Chain; scriptless scripts|https://medium.com/scalar-capital/scriptless-scripts-25e18fd52ede?sk=72eb8b17650316ad92b41179006008a7 https://www.youtube.com/watch?time_continue=2&v=PDzGP621pEs|
Scripts & Contracts|Payment Channels|https://blog.chainside.net/understanding-payment-channels-4ab018be79d4 https://www.youtube.com/watch?v=4SdBa8ZOfqg https://diyhpl.us/wiki/transcripts/scalingbitcoin/stanford-2017/bitcoin-script-v2.0-and-strengthened-payment-channels/|
Scripts & Contracts|Malleability|See SegWit Section|
Scripts & Contracts|MAST|https://bitcointechtalk.com/what-is-a-bitcoin-merklized-abstract-syntax-tree-mast-33fdf2da5e2f http://diyhpl.us/wiki/transcripts/bitcoin-core-dev-tech/2017-09-07-merkleized-abstract-syntax-trees/ https://diyhpl.us/wiki/transcripts/bitcoin-core-dev-tech/2018-03-06-merkleized-abstract-syntax-trees-mast/|
Scripts & Contracts|Signature aggregation||
Scripts & Contracts|ZK SNARKS|https://diyhpl.us/wiki/transcripts/scalingbitcoin/snarks/ https://www.youtube.com/watch?v=jr95o_k_SwI&feature=youtu.be https://vitalik.ca/general/2017/11/09/starks_part_1.html|
Scripts & Contracts|ZK STARKS|https://eprint.iacr.org/2018/046.pdf https://vitalik.ca/general/2017/11/22/starks_part_2.html https://vitalik.ca/general/2018/07/21/starks_part_3.html https://medium.com/coinmonks/zk-starks-create-verifiable-trust-even-against-quantum-computers-dd9c6a2bb13d|
Scripts & Contracts|Discreet Log Contracts|https://dci.mit.edu/research/smart-contracts-discrete-log-contracts https://medium.com/@gertjaap/discreet-log-contracts-invisible-smart-contracts-on-the-bitcoin-blockchain-cc8afbdbf0db|
Scripts & Contracts|Miniscript|https://www.youtube.com/watch?v=XM1lzN4Zfks  http://diyhpl.us/wiki/transcripts/stanford-blockchain-conference/2019/miniscript/ http://bitcoin.sipa.be/miniscript/miniscript.html|
Scripts & Contracts|State of script|https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/bitcoin-script/|
Fungibility & Scalability|The current state of Bitcoin fungibility (2019)|https://vimeo.com/316635787|
Fungibility & Scalability|On Scaling Decentralized Blockchains|https://gist.github.com/chris-belcher/a8155df5051bb3e3aa96 http://diyhpl.us/~bryan/papers2/bitcoin/On%20scaling%20decentralized%20blockchains%20-%20A%20position%20paper.pdf|
Fungibility & Scalability|Why fungibility is important|https://diyhpl.us/wiki/transcripts/scalingbitcoin/hong-kong/fungibility-and-scalability/ https://diyhpl.us/wiki/transcripts/scalingbitcoin/milan/fungibility-overview/|
Fungibility & Scalability|Fungibility as an attack vector|https://medium.com/chainrift-research/bitcoins-attack-vectors-fungibility-ed58cb4cff73|
Fungibility & Scalability|Privacy|https://blockstream.com/2017/09/08/different-approaches-to-privacy/ https://en.bitcoin.it/wiki/Category:Privacy https://en.bitcoin.it/wiki/Privacy https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/how-much-privacy-is-enough/ https://medium.com/scalar-capital/privacy-surrounding-the-blockchain-7b92a6deea62|
Fungibility & Scalability|Chain analysis|https://www.youtube.com/watch?v=9OtPOQwLBjc https://www.reddit.com/r/Bitcoin/comments/70oftr/lets_talk_about_chainanalysis/dn4vxug/?utm_source=share&utm_medium=web2x https://www.elliptic.co/data-visualizations/bitcoin-transaction-visualization-big-bang|
Fungibility & Scalability|P2P fingerprinting||
Fungibility & Scalability|tx origin analysis| http://cseweb.ucsd.edu/~smeiklejohn/files/imc13.pdf|
Fungibility & Scalability|Coinjoin|https://en.bitcoin.it/wiki/CoinJoin|
Fungibility & Scalability|Confidential Transactions|https://people.xiph.org/~greg/confidential_values.txt|https://bitcointalk.org/index.php?topic=305791.0 https://elementsproject.org/features/confidential-transactions https://medium.com/@ecurrencyhodler/a-primer-to-confidential-transactions-e6ab3dd2bf1e https://joinmarket.me/blog/blog/finessing-commitments/
Fungibility & Scalability|Tumblebit|http://diyhpl.us/~bryan/papers2/bitcoin/TumbleBit:%20An%20untrusted%20bitcoin-compatible%20anonymous%20payment%20hub%20-%202016.pdf https://diyhpl.us/wiki/transcripts/scalingbitcoin/milan/tumblebit/ https://joinmarket.me/blog/blog/tumblebit-for-the-tumble-curious/|
Fungibility & Scalability|Coin Jumble|https://bitcointalk.org/index.php?topic=730321.msg8254585|
Fungibility & Scalability|Mixnets|?? https://www.coindesk.com/this-binance-backed-crypto-startup-wants-to-anonymize-everything|
Fungibility & Scalability|Schnorr|https://youtu.be/TVGiIl3_3Ys?t=407 https://blockstream.com/2018/02/15/schnorr-signatures-bpase/ https://joinmarket.me/blog/blog/flipping-the-scriptless-script-on-schnorr/ https://medium.com/scalar-capital/schnorr-signatures-754038368b87|
Fungibility & Scalability|Bellare-Neven|https://cseweb.ucsd.edu/~mihir/papers/multisignatures-ccs.pdf|
Fungibility & Scalability|Threshold Schemes|https://en.wikipedia.org/wiki/Threshold_cryptosystem http://diyhpl.us/wiki/transcripts/sf-bitcoin-meetup/2019-02-04-threshold-signatures-and-accountability/|
Fungibility & Scalability|Signature aggregation|https://bitcointalk.org/index.php?topic=1377298.0 https://bitcoincore.org/en/2017/03/23/schnorr-signature-aggregation/ https://crypto.stanford.edu/~dabo/pubs/papers/BLSmultisig.html|
Fungibility & Scalability|MuSig|https://blockstream.com/2018/01/23/musig-key-aggregation-schnorr-signatures/ https://blockstream.com/2019/02/18/en-musig-a-new-multisignature-standard/ https://eprint.iacr.org/2018/068|
Fungibility & Scalability|Taproot|http://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/edgedevplusplus/taproot-and-graftroot/ https://github.com/sipa/bips/blob/bip-schnorr/bip-taproot.mediawiki|
Fungibility & Scalability|Graftroot|https://bitcoin-development.narkive.com/jqVWWk4l/graftroot-private-and-efficient-surrogate-scripts-under-the-taproot-assumption|
The P2P Network|Overview of the p2p network|https://youtu.be/eVerdR2hOMw|
The P2P Network|Re-Introduction to net/net_processing||
The P2P Network|Threading Model||
The P2P Network|CConnman, CNode -> CNodeState Migration, CNode Future||
The P2P Network|Network magic and handshake (version, service bits, feefilter, sendcmpct, etc.), service bits||
The P2P Network|Transaction propagation|https://arxiv.org/pdf/1111.2626.pdf (incentives)|
The P2P Network|Headers-first sync'ing||
The P2P Network|Advances in Block propagation|https://diyhpl.us/wiki/transcripts/gmaxwell-2017-11-27-advances-in-block-propagation/|
The P2P Network|Compact blocks|https://bitcoincore.org/en/2016/06/07/compact-blocks-faq/ https://youtu.be/EHIuuKCm53o?t=1273 https://github.com/bitcoin/bips/blob/master/bip-0152.mediawiki|
The P2P Network|Relay networks; FIBRE|https://diyhpl.us/wiki/transcripts/scalingbitcoin/relay-network/ https://bluematt.bitcoin.ninja/2016/07/07/relay-networks/ http://bitcoinfibre.org|
The P2P Network|Deanonymization in the Bitcoin P2P Network|https://papers.nips.cc/paper/6735-deanonymization-in-the-bitcoin-p2p-network.pdf|
The P2P Network|Dandelion|https://arxiv.org/pdf/1701.04439.pdf https://arxiv.org/pdf/1805.11060.pdf https://bitcoin.stackexchange.com/questions/81503/what-is-the-tradeoff-between-privacy-and-implementation-complexity-of-dandelion|
The P2P Network|Peer discovery|https://github.com/bitcoinbook/bitcoinbook/blob/f8b883dcd4e3d1b9adf40fed59b7e898fbd9241f/ch08.asciidoc#network-discovery|
The P2P Network|Topology Discovery|https://www.cs.umd.edu/projects/coinscope/coinscope.pdf https://arxiv.org/abs/1812.00942|
The P2P Network|Peer connectivity||
The P2P Network|BGP Hijack|https://btc-hijack.ethz.ch/|
The P2P Network|Eclipse Attacks on Bitcoin’s Peer-to-Peer Network (2015)|https://eprint.iacr.org/2015/263.pdf https://www.usenix.org/node/190891 (video)|
The P2P Network|DoS concepts (net splits, etc)|https://en.bitcoin.it/wiki/Weaknesses#Denial_of_Service_.28DoS.29_attacks https://bitcoin.stackexchange.com/questions/1738/what-would-happen-if-a-portion-of-the-bitcoin-network-was-separated-from-the-res https://bitcoin.stackexchange.com/questions/8738/feasibility-of-a-high-horsepower-attack-based-on-difficulty-4x-adjustments|
The P2P Network|Denial-of-Service Prevention|https://github.com/bitcoin/bitcoin/pull/517 https://bitcointalk.org/index.php?topic=44954.0|
The P2P Network|SPV nodes|https://diyhpl.us/wiki/transcripts/scalingbitcoin/future-of-spv-tech/|
The P2P Network|MiniSketch|https://blockstream.com/2019/01/07/minisketch-reducing-node-bandwidth-requirements/ https://github.com/sipa/minisketch|
Chain Forks and Failures|OP_EVAL, OP_CHV and Taproot||
Chain Forks and Failures|A history of consensus changes in Bitcoin||
Chain Forks and Failures|BIP 66 Fork and spy mining|https://github.com/bitcoin/bips/blob/master/bip-0066.mediawiki https://bitcoin.stackexchange.com/questions/38437/what-is-spv-mining-and-how-did-it-inadvertently-cause-the-fork-after-bip66-wa|
Bitcoin Core Architecture|Architecture overview|https://www.youtube.com/watch?v=L_sI_tXmy2U|
Bitcoin|Learning-Bitcoin-from-the-Command-Line|https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line|
Bitcoin Core Contribution|Contributing to Core|https://github.com/bitcoin/bitcoin/blob/master/CONTRIBUTING.md https://rubin.io/talks/2017/02/01/intro-bitcoin-dev-jp/ https://bitcointechtalk.com/contributing-to-bitcoin-core-a-personal-account-35f3a594340b|
