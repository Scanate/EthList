# EthList: The Comprehensive Ethereum Reading List
### Found a great resource? Add it by submitting a Pull Request!

| [Introduction](#introduction) | [Getting Started](#getting-started) | [Ecosystem](#ecosystem) | [Thought Pieces](#thought-pieces) | [Trading](#trading) | [Programming](#programming) | [Legal](#legal)
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |

Contributors: Phil Kurtland, Jake Brukhman, Robert Hackett, Maksim Balashevich, Jorge Izquierdo, Michal Brazewicz, Justin Poirier, Luis Cuende

## Introduction

### What is Ethereum?

Ethereum is a cutting edge blockchain-based distributed computing platform, featuring smart contract functionality. It provides a decentralized virtual machine, the Ethereum Virtual Machine (EVM), that can execute peer-to-peer contracts using a crypto-fuel called _Ether_.

- [Visual demonstration of a blockchain](https://anders.com/blockchain/)
- [Ethereum the world computer](https://www.youtube.com/watch?v=j23HnORQXvs) (video)
- [Vitalik Buterin's Ethereum introduction at Devcon 1](https://www.youtube.com/watch?v=gjwr-7PgpN8) (video)
- [Joseph Lubin's interview on building decentralized applications](https://www.youtube.com/watch?v=MgLmY9oedTM) (video)
- [BBC explains Ethereum](https://www.youtube.com/watch?v=0X33lgMbvdI) (video)
- [Techcrunch on Ethereum](https://www.youtube.com/watch?v=WfULutvxvzY) (video)
- [ELI5: What is Ethereum?](https://www.reddit.com/r/ethereum/comments/60hhjm/eli5_what_is_ethereum/)
- [Introduction to Ethereum: The Internet’s Government](https://media.consensys.net/introduction-to-ethereum-the-internets-government-35bdd25f572a#.5me0m455w)
- [A beginner’s guide to Ethereum](https://blog.coinbase.com/a-beginners-guide-to-ethereum-46dd486ceecf)
- [What is Ethereum?](https://cointelegraph.com/ethereum-for-beginners/what-is-ethereum)
- [Just enough Bitcoin for Ethereum](https://media.consensys.net/time-sure-does-fly-ed4518792679#.xclr74isu)
- [Ethereum: Bitcoin Plus Everything](https://medium.com/@ConsenSys/ethereum-bitcoin-plus-everything-a506dc780106#.v7s0ganew)
- [An Introduction to Ethereum and Smart Contracts: a Programmable Blockchain](https://auth0.com/blog/an-introduction-to-ethereum-and-smart-contracts-part-2/)
- General [White Paper](https://github.com/ethereum/wiki/wiki/White-Paper), Technical [Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf) (pdf)
- [Thinking outside the Blocks](https://www.bcg.com/blockchain/thinking-outside-the-blocks.html?linkId=32278919)
- [Understanding Ethereum Report](https://forum.daohub.org/uploads/default/original/2X/b/b583e2bb2e6998bfec40d488b1709deb53abdc4a.pdf) (PDF)
- [Very deep-dive on Ethereum Reading List](https://medium.com/@ConsenSys/very-deep-dive-on-ethereum-reading-list-f5b1122e5990)

#### History Articles:
 
- [Can This 22-year-old Coder Out-Bitcoin Bitcoin?](http://fortune.com/ethereum-blockchain-vitalik-buterin/)
- [The Uncanny Mind That Built Ethereum](https://backchannel.com/the-uncanny-mind-that-built-ethereum-9b448dc9d14f#.27vnan8wp)

### I want more in-depth details!

#### The annual Ethereum Developer Conference (Devcon):

- [Devcon 0 (Berlin, 2014) talks and videos](https://www.youtube.com/watch?v=_BvvUlKDqp0&amp;list=PLJqWcTqh_zKEjpSej3ddtDOKPRGl_7MhS)
- [Devcon 1 (London, 2015) talks and videos](https://www.youtube.com/watch?v=BUARih8_f68&list=PLJqWcTqh_zKHQUFX4IaVjWjfT2tbS4NVk)
- [Devcon 2 (Shanghai, 2016) talks and videos](https://www.youtube.com/watch?v=1wayaZ1-iBE&list=PLaM7G4Llrb7xqzgOwbvNv63_KM7VH84Rd)
- [**Devcon 3** (Cancún, 2017) website and registration](http://ethereumfoundation.org/devcon3/)

#### List of protocol updates and hard-forks:

- Olympic pre-release (Testnet, Chain #0 - May 9, 2015)
  - [Blog post](https://blog.ethereum.org/2015/05/09/olympic-frontier-pre-release/)
- **Frontier** public release (Ethereum Genesis, Chain #1 - July 30, 2015)
  - [Blog post](https://blog.ethereum.org/2015/07/30/ethereum-launches/)
- **Homestead** (Block #1,150,000 - March 14, 2016)
  - [Blog post](https://blog.ethereum.org/2016/02/29/homestead-release/), [EIP-2](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2.mediawiki), [EIP-7](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-7.md), [EIP-8](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-8.md)
- DAO Fork (Block #1,920,000 - July 20, 2016)
  - [Blog post](https://blog.ethereum.org/2016/07/20/hard-fork-completed/), opposition at r/EthereumClassic
- DoS Fork (Block #2,463,000 - October 18, 2016)
  - [Blog post](https://blog.ethereum.org/2016/10/18/faq-upcoming-ethereum-hard-fork/), [EIP-150](https://github.com/ethereum/EIPs/issues/150), [EIP-158](https://github.com/ethereum/EIPs/issues/158)
- Spurious Dragon (Block #2,675,000 - November 22, 2016)
  - [Blog post](https://blog.ethereum.org/2016/11/18/hard-fork-no-4-spurious-dragon/), [EIP-155](https://github.com/ethereum/EIPs/issues/155), [EIP-160](https://github.com/ethereum/EIPs/issues/160), [EIP-161](https://github.com/ethereum/EIPs/issues/161), [EIP-170](https://github.com/ethereum/EIPs/issues/170)
- **Metropolis** will be [scheduled end of June, 2017](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2012.md#5-metropolis-update) (_to be announced_)
  - _work in progress_: [EIP-86](https://github.com/ethereum/EIPs/pull/208), [EIP-96](https://github.com/ethereum/EIPs/pull/210), [EIP-98](https://github.com/ethereum/EIPs/issues/98), [EIP-100](https://github.com/ethereum/EIPs/issues/100), [EIP-140](https://github.com/ethereum/EIPs/pull/206), [EIP-196](https://github.com/ethereum/EIPs/pull/213), [EIP-197](https://github.com/ethereum/EIPs/pull/212), [EIP-198](https://github.com/ethereum/EIPs/pull/198)
- **Serenity** _to be announced_ (2018)
  - [Why does Ethereum plan to move to Proof of Stake](http://ethereum.stackexchange.com/questions/9)?

#### List of public testnets:

- Olympic, pre-release public test network with ID #0 (replaced by Morden)
- Morden, Fontier-based public test network with ID #2 ([replaced by Ropsten](https://blog.ethereum.org/2016/11/20/from-morden-to-ropsten/))
- **Ropsten**, Homestead-based public test network with ID #3 ([recently revived](https://www.reddit.com/r/ethereum/comments/61bawv/ropsten_revived_thanks_to_generous_miners/))
- ConsenSys, Proof-of-Work [public test network](https://github.com/ConsenSys/ConsenSys.github.io/wiki/ConsenSys-public-testnet)
- **Kovan**, Proof-of-Authority [public test network](https://github.com/kovan-testnet/proposal)
- Rinkeby, Proof-of-Authority, _to be announced_ ([EIP-225](https://github.com/ethereum/EIPs/issues/225))

#### Misc Collections:

- [Learn about the Blockchain](https://www.reddit.com/r/Entrepreneur/comments/3l7gj2/i_want_to_learn_everything_about_the_blockchain/)
- [Reading Guide on Ethereum](https://medium.com/@paulgambill/reading-guide-on-ethereum-27d006c82792#.vtek62s0k)
- [Ethereum Reading List for Prospective Dapp Developers](https://dappdaily.com/ethereum-reading-list-for-prospective-dapp-developers-15d515383b23)
- [r/ethereum’s Guide](https://www.reddit.com/r/ethereum/comments/61y5ix/welcome_to_rethereum_the_reddit_front_page_of_the/)
- [The Ethereum Wiki](https://theethereum.wiki/w/index.php/Main_Page)
- [Ethereum Stack Exchange](https://ethereum.stackexchange.com)

## Getting Started

- [Easy Guide to Using Ethereum
](https://medium.com/ethertime/the-easy-guide-to-using-ethereum-d482b6c3d3a4
)

#### Security:
- [The Crypto-Trader’s Guide to Online Security
](https://medium.com/santiment/the-crypto-traders-guide-to-online-security-8eeffa6839ed
)
- [My guide to securing your digital life
](https://medium.com/@pipermerriam/my-guide-to-solid-digital-security-fb76cb19c536#.hmz8imwe6
)
- [It’s Time to Get Real: Stop Relying on Third Parties to Protect You & Your Funds. You are responsible for your security.
](https://www.reddit.com/r/ethereum/comments/556frk/its_time_to_get_real_stop_relying_on_third/
)
- [Cold Storage for Dummies
](https://www.reddit.com/r/ethereum/comments/55k8w2/cold_storage_for_dummies_does_a_simple_guide_exist/
)

## Ecosystem

- [State of the Dapps
](http://dapps.ethercasts.com/
)
- [Ethereum Business Directory
](http://ethereumall.com/business-directory/page/9/?wpbdp_view=all_listings
)

#### Other conferences, workshops, meetups, or tutorials:

- [European Ethereum Development Conference](https://www.youtube.com/channel/UC5NL-IbFyN72qme66EqX5-A/videos) (EDCON)
- [London Ethereum](https://www.youtube.com/watch?v=Uya2rd5pN0o&list=PLaM7G4Llrb7xTHkSwbDfDP9MeZ_6WKI6Z) (meetup)
- [Berlin Ethereum](https://www.youtube.com/watch?v=KWeNSvori4I&list=PLaM7G4Llrb7wPiT2G75tj2JQr8qg6P5hi) (meetup)
- [Ethereum Core Developer Meetings](https://www.youtube.com/watch?v=ex51Gb3SVqo&list=PLaM7G4Llrb7zfMXCZVEXEABT8OSnd4-7w) (call)
- [Building Ethereum DApps using Solidity](https://www.youtube.com/watch?v=9_coM_g7Dbg&list=PLH4m2oS2ratdoHFEkGvwvd7TkeTv4sa7Z) (tutorial)

#### Newsletters
- [Week in Ethereum
](http://www.weekinethereum.com/
)
- [Dapp Daily
](https://dappdaily.com/
)
- [Consensys Media
](https://media.consensys.net/
)
- [The Etherian
](https://theetherian.wordpress.com
)
- [The Control
](https://thecontrol.co/
)
- [HEAT Crypto Roundup
](http://heatledger.ghost.io/
)

#### News
- [CoinTelegraph
](https://cointelegraph.com/
)
- [CoinDesk (owned by Digital Currency Group, which has a stake in a competing cryptocurrency) http://www.coindesk.com/

](http://www.coindesk.com/
)

#### Ethereum Block Explorers
- [https://etherscan.io/
](Etherscan)
- [https://ethplorer.io
](Ethplorer)


#### ICOs (Initial Coin Offerings):
- [Ultimate ICO Calendar
](www.scanate.co/ico
)
- [Smith and Crown
](https://www.smithandcrown.com/icos/
)
- [TokenMarket
](https://tokenmarket.net/
)
- [TokenInvestor
](https://tokeninvestor.com/
)

## Thought Pieces

Possibilities of Decentralized Technology
https://www.reddit.com/r/ethtrader/comments/4dvfcm/serious_question_can_anyone_actually_think_of/d1uskh1/

Risks of Ethereum
https://www.reddit.com/r/ethtrader/wiki/risks

Community Values
https://www.reddit.com/r/ethereum/comments/57hqyg/thoughts_on_our_values_as_a_community/

Growth of the space
https://blog.coinbase.com/the-coinbase-secret-master-plan-f4d644443301#.xdoe2er8i

The Internet of Agreements: Building the Hyperconnected Future on Blockchains
http://internetofagreements.com/files/WorldGovernmentSummit-Dubai2017.pdf

#### Decentralized Apps/Protocols
Crypto Tokens and the Coming Age of Protocol Innovation
http://continuations.com/post/148098927445/crypto-tokens-and-the-coming-age-of-protocol

The Golden Age Of Open Protocols
http://avc.com/2016/07/the-golden-age-of-open-protocols/

Decentralized organizations can solve the world’s worst problems
https://blog.aragon.one/decentralized-organizations-can-solve-the-worlds-worst-problems-840db6255d12

Blockchain Tokens and the dawn of the Decentralized Business Model
https://blog.coinbase.com/app-coins-and-the-dawn-of-the-decentralized-business-model-8b8c951e734f#.qxh3d0hh2

The Business Case for Dapps – Decentralization as a Strategy
http://mattgoldenberg.net/2016/01/02/the-business-case-for-dapps-decentralization-as-a-strategy/

‘Decentralised’ is the new black, or a short history of dapps
http://www.coinfox.info/news/reviews/5805-decentralised-is-the-new-black-or-a-short-history-of-dapps

Cryptoeconomics Is Hard
https://blog.coinfund.io/cryptoeconomics-is-hard-ad401b2428b9

#### Crowdsales
Introducing the Blockchain Token Securities Law Framework
https://blog.coinbase.com/2016-12-07-blockchain-token-securities-law-a66ef03c383f#.7xhadylu3

Blockchain investments and the new problem asset for conventional VCs
https://blog.coinfund.io/blockchain-investments-and-the-new-problem-asset-for-conventional-vcs-b65bfc7ca75

How to Raise Money on a Blockchain with a Token
https://blog.gdax.com/how-to-raise-money-on-a-blockchain-with-a-token-510562c9cdfa#.z69j53rkx

Exploring Continuous Token Models: Towards a Million Networks of Value
https://media.consensys.net/exploring-continuous-token-models-towards-a-million-networks-of-value-fff153175776

Trick or Treat? Investment in Blockchain Cryptoassets
https://medium.com/@flexthought/trick-or-treat-investment-in-blockchain-cryptoassets-b1ad47ef58c#.49xq4x4hh

AGAINST TOKENS (AND TOKEN CROWDSALES)
https://prestonbyrne.com/2016/08/12/against-crowdsales/

How Cryptocurrencies and Blockchain-based Startups Are Turning The Traditional Venture Capital Model on Its Head
http://startupmanagement.org/2016/10/06/how-cryptocurrencies-and-blockchain-based-startups-are-turning-the-traditional-venture-capital-model-on-its-head/

How to Evaluate an Initial Cryptocurrency Offering (ICO)
http://startupmanagement.org/2016/11/24/how-to-evaluate-an-initial-cryptocurrency-offering-ico/

ICO 2.0 — what is the ideal ICO?
https://medium.com/iconominet/why-icos-fail-1f9530a6d135#.6uw69odix

Blockchain investment vehicles: the future of global retail investment
https://blog.coinfund.io/blockchain-investment-vehicles-3ca285797060

## Trading
Learn Forex Trading at the School of Pipsology (Very applicable to crypto trading)
http://www.babypips.com/school

Paradigm Shift: Technical Analysis in the Altcoins & Bitcoin Market, & Introduction to Market Cycle, Structure & Manipulation
https://alunacrypto.blogspot.ca/2014/05/technical-analysis-altcoins-bitcoin-trading-market-structure-cycle-manipulation.html

CryptoCurrency Market Capitalizations
https://coinmarketcap.com/

#### Exchanges

##### Bitcoin
https://www.bitfinex.com/

https://www.bitmex.com/

##### Altcoins
https://poloniex.com/

https://bittrex.com/

https://liqui.io/

##### Decentralized Exchanges (Mostly Eth assets)
https://oasisdex.com/

https://etherdelta.github.io/

https://cryptoderivatives.market/

## Programming

- [Build your own crypto-currency with Ethereum](https://www.ethereum.org/token)
- [Raise funds from friends without a third party](https://www.ethereum.org/crowdsale)
- [Build a democracy on the blockchain](https://www.ethereum.org/dao)
- [Build **your first DApp** in ten steps](https://github.com/paritytech/parity/wiki/Tutorial-Part-I)
- [Monitor the network status](https://ethstats.net/) ([mirror](http://stats.parity.io/)) and [the gas price market](http://ethgasstation.info/)
- [Read the documentation](http://ethdocs.org/en/latest/) (for Homestead)
- [Check out some **DApps**, that run on Ethereum](http://dapps.ethercasts.com/)
- [Learn **Solidity**, an Ethereum smart contract language](https://solidity.readthedocs.io/)
- [Browse the Ethereum Ecosystem Business Directory](http://ethereumall.com/)
- [Ask questions at **Ethereum Stack Exchange**](http://ethereum.stackexchange.com/)
- [Live chat with Ethereum developer teams and community](https://gitter.im/orgs/ethereum/rooms)
- [Check out Ethereum **Meetups** in your area](https://www.meetup.com/topics/ethereum/)
- [A 101 Noob Intro to Programming Smart Contracts on Ethereum](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4#.ieo0yl4jr)
- [Where can I learn how to develop DApps using the solidity programming language?](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4#.ieo0yl4jr
)
- [Learning to Code in Ethereum](https://www.reddit.com/r/ethereum/comments/4z4y81/any_advice_on_learning_to_code_in_ethereum/)

## Legal
- [BitLegal Map
](http://map.bitlegal.io/
)
- [Introducing the Blockchain Token Securities Law Framework
](https://blog.coinbase.com/2016-12-07-blockchain-token-securities-law-a66ef03c383f#.7xhadylu3
)
- [IRS Virtual Currency Guidance : Virtual Currency Is Treated as Property for U.S. Federal Tax Purposes; General Rules for Property Transactions Apply
](https://www.irs.gov/uac/newsroom/irs-virtual-currency-guidance
)
- [Legality of Bitcoin by Country
](https://en.wikipedia.org/wiki/Legality_of_bitcoin_by_country
)

![Ethereum](https://upload.wikimedia.org/wikipedia/commons/b/b7/ETHEREUM-YOUTUBE-PROFILE-PIC.png)

