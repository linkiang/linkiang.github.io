# 4. Technology related

From a technical point of view, the casting protocol is a new nft application solution that creates a standardized rarity abstraction layer that can be easily integrated with other applications or Dapps. Many people think that NFT can surpass Fungible Token and DeFi. For other types of Dopp, such as GameFi, NFT has a wider practical application significance. However, the existing NFTs are mainly used for collectibles transactions. As collectibles, the rarity of collectibles that lack friendly features in many GameRs is completely determined by the market, and the market is small, which leads to huge price fluctuations. This will not allow NFT to run well outside the scope of the collection. We believe that NFT should have a wider range of uses, such as representing a wider range of items on the chain. In most cases, the demand for this will appear in games and meta-universes. Rarity and data want to create a service that can serve The meta-universe prop system must satisfy both scarcity and versatility: the main value manifestation. From an economic point of view, only by ensuring scarcity can we ensure that the value system of the entire prop system does not appear chaotic. Only by using the same set of rarity functions can the data of the rarity during the creation of the item be ensured: an item needs to be able to enhance at least one value, that is, the item itself must have a data use, only if it has a data use, it has different data Dimension can be truly used as a standardized tool by developers of the interaction layer. If there is no data dimension, then it will not have versatility. It is very simple. NFT without reserved data entry and exit can only be used as a display. The difference is similar. For the pistol model and the real pistol, the pistol model only needs to tell you that this is a pistol, but the real pistol must have a load capacity,A series of dimensions such as range, muzzle speed, etc.

In the casting protocol, these data are based on the standard data of ERC721. Any contract developer can easily read the data in it, display it or use it in its own interactive layer, so that the owner can be extremely convenient Phase shifting This is the reason we proposed the casting protocol, which is a new standard NFT protocol for GameFi, which has complete rarity during casting and provides more complete data in the NFT. And these NFs with certain scarcity and dataability can become the basis of the block system in other Dapp/App

## How does the casting protocol protocol work?
### 1.0 token generation
The bottom layer has the function of coin minting. The minting protocol is used to mint NFT. It will have a set of randomly generated attributes. The scarcity of these attributes is generated during the minting and is independent of each other. The randomness of the scarcity of each attribute follows a distribution model, and there will be a function to query any.

The scarcity of the attributes of the casting agreement. The overall scarcity can be calculated from the sum of the scarcity of all attributes or the sum of the weighted scarcity. The rare system standard is applicable to all casted NFTs on this layer, and they are all deterministic.
### 2.0 token application examples
Any Dapp/App can use the casting protocol, which presets the rarity in the entire or each individual attribute, and targets different application logic in its own application module. For example, map an NF to a weapon or armor based on the rarity of different attributes. Another example is the use of casting associations in games.
### 3.0 key realization of rarity
First define a probability density function (Probability Density Function referred to as PDF), and then define a sampling method of the output degree function. We also need to define the Cumulative Distribution Function (CDF) for this PDF. We can use a normal distribution as the PDF, such as the standard normal distribution StandSND). In order to generate SND random samples from uniform randomness, we can use inverse CDF (quantile function) or box muller for transformation.

## The casting agreement agreement has completed the goal
### 1.0 portable bottom layer
Create this open, standardized, and portable bottom layer, or part of the bottom layer.

### 2.0 Rarity Model
The casting protocol uses the Rarity contract to create a mathematics-based rarity model, and ensures that this rarity is not excessively affected by other factors, so as to ensure that the item value system does not appear chaotic.
### 3.0 Generate props NFT
The casting protocol uses Itcm contracts to generate NFTs representing the generated items. Through different Item contracts, a large number of portable and standardized items can be produced that are in line with the scarcity model.

### 4.0 Contract generation with Dapp
Through the mutual cooperation of these two contracts, the casting protocol meets the goals of openness, standardization, and portability at the same time, and becomes a truly practical Gamefi, or meta-universe infrastructure.