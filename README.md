# [Awareness Bounty] The-State-of-NFT-Environmental-Impact-Reduction
## Executive Summary
"The State of NFT Environmental Impact Reduction” is a unique research paper that audits the energy efficiency of NFT projects across chains that currently support NFT minting, based on leading metrics. Based on our analysis, we will uncover common characteristics that lead to the reduction of the environmental impact of NFT minting and transactions.

## Foreword
The acceleration of the popularity of NFTs within the blockchain ecosystem has allowed artists and collectors to be  able to put themselves out into the open market and sell, trade, or collect NFTs. But as the initial excitement and hype reached its peak, artists and enthusiasts all over the world started to question the true impact NFTs could pose on to the environment, With most of the market share being taken up by Ethereum - currently a PoW (Proof of Work) blockchain - the concerns about carbon footprints and energy consumption of NFTs have come into the spotlight, which has led to many artists even cancelling their planned NFT art drops, in a bid to raise awareness to this massive issue. 

According to the research done by Memo Akten, 
> “***the average NFT*** [on Ethereum] _has a footprint of around 340 kWh, 211 KgCO2_. This ***single NFT***’s footprint is equivalent to a EU resident’s total electric power consumption _**for more than a month**_, with emissions equivalent to ***driving for 1000Km***, or ***flying for 2 hours***”.

This has left artists around the world in a dilemma between embracing this new revolutionary technology of NFTs and blockchain, against sacrificing the environment for their needs. Luckily, this does not have to be the case. Although Ethereum's base layer is currently unscalable and leaves behind a huge carbon-footprint with every transaction on it, there is a huge ecosystem of more advanced and energy-efficient blockchains and Layer 2 solutions that provide the same blockchain technology, proof of digital ownership, trust and openness. 

NFTs are also not all bad. According to Robbie Ferguson, CoFounder of [ImmutableX](https://dailyhodl.com/2021/03/29/immutable-x-is-making-nfts-carbon-neutral-on-ethereum/#:~:text=On%20Immutable%20X%2C%20we%27ve,475%2C000%20times%20less%20energy%20consumption), 
> “On a macro level, accelerating the trading and collecting of digital NFTs offsets the need for environmentally wasteful throwaway physical goods. By reducing the physical reproduction of certain physical goods, e.g. fast fashion, music, plastic games, and moving to more digital collection options like NFTs, reduces the bigger secondary sources of environmental pollution. Namely, mineral mining for plastics, production, supply chain, and transport pollution, with transport having the largest impact on energy consumption at 8,265 TWh in the US in 2019.”

Unfortunately, most artists and collectors are not aware of the many options for minting NFTs and their associated ecological impact. **This body of research** outlines a wide variety of current projects/solutions and explains how they reduce energy consumption of NFTs. The hope is that by having a consolidated resource with clear information on the advantages of supporting these options, we can immediately reduce the impact of NFTs on the environment without waiting for longer-term solutions such as Ethereum’s Sharded PoS - Ethereum 2.0.

## Research Methodology
Our research analyzed the two key systems that impact the minting of NFTs; the NFT platform, and the blockchain on which the NFT is minted. 

1. Relating to ***Blockchains***, we observed...
   - What consensus algorithm do they use?
   - What are the NFT standards do they use (if they have one)?
   - What is the environmental impact and/or environmental friendly actions the chain is undertaking as a community?
2. Relating to ***Tools & Marketplaces***, we observed...
   - What does the project do?
   - When it was launched?
   - What is the consensus mechanism(s) are used by the underlying blockchain(s)?
   - What NFT standards are supported by the platform itself?
   - What is the environmental impact and/or environmental friendly actions the project is undertaking as a community?

The research was conducted by scouring the internet for different chains and platforms that support NFTs, and listing them in a spreadsheet, after which they are analysed based on the above mentioned criterias. Information was solicited from various sources including articles, blogs (both official and unofficial), Discord and Reddit communities of respective chains and platforms, and directly talking to representatives of the chains or platforms. 

## Summary of Findings
This forthcoming section will discuss the outcomes of our research and summarize our findings. **The full research report can be found here: [The State of NFT Environmental Impact Reduction: Excel Report.](https://docs.google.com/spreadsheets/d/1nEIFuu9oUVxtsQHgUZck-YhMD9xKXzl5AyD-Jj2j3lM/edit?usp=sharing)**

Our research resulted in the aggregation and analysis of a total of **26** different blockchains (including. Sidechains, and Layer-2 solutions), and **80** different platforms (including tools, marketplaces, and games). 
In this report, we asked ourselves **“What characteristics make a protocol or project more or less eco friendly for NFT usage?”**. In our research, we observed characteristics across three sections: design, practices, and business operations. 

### Design Impacts on Eco-Friendliness
- ***Proof of Stake (PoS) Consensus Mechanism:*** Whether a platform/project uses Proof of Stake or Proof of Work is the biggest factor when it comes to energy efficiency and eco-friendliness. In stark contrast to Proof of Work consensus mechanisms, Proof of Stake (including Delegated Proof of Stake, Nominated Proof of Stake and others) have a significantly lower energy consumption. For example: Ethereum 1.0’s Proof of Work shifting to 2.0’s Proof of Stake is estimated to cut energy usage by a whopping 99% ([Institute of Electrical and Electronics Engineers, 2020](https://spectrum.ieee.org/computing/networks/ethereum-plans-to-cut-its-absurd-energy-consumption-by-99-percent)). An additional example: Ethereum 1.0’s Proof of Work is estimated to release 20.15 Mt CO2 per year, while popular Proof of Stake protocol [NEAR](https://near.org/blog/the-near-blockchain-is-climate-neutral/) releases 174 tons of CO2 per year (which is then carbon-offset by NEAR Foundation). It could be noticed that almost all blockchains since Ethereum, support a consensus mechanism other than Proof of Work. In essence, moving to a chain without PoW already reduces your carbon footprint.
- ***Proof of Authority (and similar) consensus mechanism:*** Gaming platforms that formed first on Ethereum have tried to migrate from Ethereum to another L1 chain or an L2 chain. We could see that blockchain games like Axie Infinity, Enjin, Dapper Labs Crypto Kitties; all tried to build their own chain either as an L2 or another L1 exclusive to the game and its ecosystem, or more optimised for blockchain games. This has led in some cases to prefer efficiency rather than decentralisation as most game-based L2s tend to be Proof of Authority or similar consensus models with a handful of nodes for faster transactions. This in effect leads to lesser energy consumption but at the cost of decentralisation. 
- ***Layer-2s, Side-Chains and EVM compatible chains:*** One of the most popular ways for staying exposed to Ethereum’s immense popularity, usage, and developers has been the creation of NFT applications on Layer-2 scaling solutions like xDai, Polygon, and other EVM compatible chains like Binance Smart Chain. Thus the NFT standards on such chains are the same as that of ERC-721. Although most of these L2s do not allow the porting of NFTs from Ethereum and vice versa, some of the chains such as parachains on top of Polkadot have bridges that allow the transfer of ERC-721 to Polkadot. 

### Practices Impact on Eco-Friendliness
- ***Delayed Minting:*** [Minters like Opensea](https://opensea.io/blog/announcements/introducing-the-collection-manager/) that offer “delayed minting” or “free minting” that results in an NFT not being minted on-chain until point of sale in-directly reduce the carbon footprint of the NFT being minted. Waiting until point of sale to mint results in one or more fewer transactions taking place over the lifetime of the NFT. “Delayed minting” programs may seem like they have only a small impact on the eco-friendliness of a platform, but in aggregate, saving even one transaction’s worth of energy per NFT minted makes a big difference. 
- [***Batching NFT Transactions:***](https://medium.com/horizongames/going-beyond-erc20-and-erc721-9acebd4ff6ef) Platforms that offer the option to “batch” the minting of multiple NFTs are more energy efficient than individually minting NFTs one at a time. 

### Business Operations Impact on Eco-Friendliness
- ***Carbon Offsetting Programs:*** Chains like NEAR Protocol, Algorand, and minters and marketplaces like ArtBlocks, Bazaar Market use carbon offsetting to reduce their environmental impact. Carbon offsetting is often done through donating to companies that plant trees commensurate with the amount of carbon expended by the project. The aforementioned chains and projects have used carbon offsetting to partially, or fully offset their carbon footprints.  Many blockchains (such as Polygon, Efinity) have even pledged to be carbon-neutral/negative in a few years and have laid out roadmaps for the same. Some claim to already be carbon neutral.
- ***Building upon Energy-efficient chains:*** With the recent uproar on the energy consumption of NFTs on Ethereum, a new wave of NFT marketplaces have been launched or are under development. Most of these new platforms openly acknowledge that they intentionally chose to build on energy-efficient chains like Tezos and Cardano in order to help save the planet.These platforms have only been recently launched and only have been around for a month or two. This means that developers and artists are not only realizing that there are other energy efficient chains, they are also building the infrastructure such that artists and collectors no longer have to rely on energy intensive PoW chains anymore. The CleanNFTs business motive has led to many artists openly promoting and experimenting with new platforms as well.

## Conclusion
Every day, platforms are innovating and developing new ways to offset or reduce their carbon footprints. We are excited to see more projects evolving in the direction of eco-friendliness over the coming years and decades. The NFT ecosystem of many chains are still only developing, with multitudes of NFT projects to be launched, it remains to be seen how successful this new technology will evolve to be in the near future. By far, Ethereum still has one of the most mature NFT ecosystems, along with chains like Tezos, WAX, BSC, and Flow. Will these energy-efficient alternatives prove to be a killer application for Ethereum and their current PoW mechanism? Or will the network effects of the chain prove fatal to others, it remains to be witnessed, as the ecosystem evolves.

#### Questions?
If you have questions regarding our research or methodology, feel free to connect with us on Linkedin and drop us a message: [Robin Roy Thomas](https://www.linkedin.com/in/robin-roy-thomas/), [Kirsten Pomales Langenbrunner](https://www.linkedin.com/in/kirstenpomales/). 

##### Extra Resources
- Calculate your Ethereum Carbon Footprint: https://carbon.fyi/
- A repository of everything NFT: https://github.com/Lucas-Kohorst/awesome-nft#awesome-defi-
- A list of NFT marketplaces: https://www.cryptowisser.com/nft-marketplaces/
- Repository of Eco-Friendly and Non-Ecofriendly NFT Platforms: https://github.com/memo/eco-nft
- The Ecological Cost of #CryptoArt Part 1: https://memoakten.medium.com/the-unreasonable-ecological-cost-of-cryptoart-2221d3eb2053
- The Ecological Cost of #CryptoArt Part 2: https://memoakten.medium.com/analytics-the-unreasonable-ecological-cost-of-cryptoart-72f9066b90d 

