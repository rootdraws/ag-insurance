# Nexus Mutual Whitepaper Analysis

## Executive Summary

**Bottom Line:** Nexus Mutual proposes a peer-to-peer discretionary mutual on Ethereum that eliminates traditional insurance intermediaries through smart contracts, reducing frictional costs by ~18% while restoring mutual ownership to policyholders.

**Key Strategic Elements:**
- **Economic Model:** Continuous token pricing tied to capital requirements (MCR%) creates natural funding incentives
- **Claims Process:** Crowd-sourced assessment with staked tokens prevents fraud while maintaining decentralization
- **Risk Management:** Solvency II-based capital modeling (99.5% confidence) with diversification benefits
- **Market Entry:** Smart contract cover addresses clear market need with objective claims assessment
- **Competitive Moats:** Risk assessor network, capital pool size, member token lock-in effects

**Critical Risks:**
- Game theory attacks on claims assessment despite incentive design
- Regulatory uncertainty around discretionary mutual structure
- Limited investment options reducing profitability vs traditional insurers
- Chicken-and-egg problem requiring both capital providers and cover buyers

---

# NEXUS MUTUAL
*A peer-to-peer discretionary mutual on the Ethereum blockchain.*

**HUGH KARP, REINIS MELBARDIS**

## ABSTRACT

The insurance industry has developed over time from a community-based model to an adversarial one where large institutions dominate. It is also inefficient in many areas leading to large frictional costs being borne by customers. Blockchain technology allows individuals to efficiently transact directly with each other and therefore enables the core insurance entity to be replaced. Nexus Mutual uses blockchain technology to bring the mutual ethos back to insurance by creating aligned incentives through smart contract code on the Ethereum blockchain.

## BACKGROUND

Before insurance companies existed, communities would group together themselves. They would pool resources to protect individual members from risks they all faced.¹ If an unfortunate event occurred the senior members of the community would decide whether to provide assistance or not. All funds raised were used to benefit the members of the community.

In developed nations we have largely moved away from this community approach primarily due to the underlying economics of insurance. Insurance economics are driven by diversification. The more individual risks that are pooled together the less capital is required to be confident all claims can be met.² Scale benefits are significant and community models don't have the means to access them easily.

Moving away from the community model brought other challenges, in particular the issue of agency. An insurer is looking after customers money and then promising it will pay when a claim arises. As a result, the insurer is becoming an agent of the customer and history has proven this model doesn't work without heavy oversight from government institutions and complex legal frameworks. These frameworks are necessary primarily due to the lack of trust between customers and the institution and boil down to two main points:³

1. **AGENCY** - Insurers decide on how customers money is handled. Including how it is invested, which insurance risks it will back and when it gets paid out to shareholders. They also have an implied option where there is potentially unlimited upside but if the insurance company goes bust it is customers that suffer. Interests are not directly aligned.

2. **TRANSPARENCY** - A customer finds it extremely difficult to assess how safe a particular insurer is. There is a clear information asymmetry issue.

In developed nations both of these issues are dealt with primarily via law and prudential regulation – a complex combination of standards defining minimum capital levels, governance processes, reviews and regular financial reporting. Regulation in this way is largely effective, barring a handful of high profile exceptions⁴, but brings additional costs and reduced flexibility.

Even with this burden the institutional model has provided significant benefits to customers via reduced premiums and deeper pockets. The underlying diversification benefits have more than outweighed the regulatory burden. But there is still substantial unnecessary cost in the system. Roughly 35%⁵ of insurance premiums are lost due to frictional costs in the system. Only 65% of premiums are returned to customers via claims, the rest is lost in distribution, operational expenses (including regulatory), capital costs and profit.

Blockchain technology and smart contracts can strip out not only the administrative inefficiencies but a large portion of the governance and regulatory related costs. They can do this by providing trust in a different, much more cost-effective way. Trust is moved from institutions and regulations to transparent code. Of the 35% of frictional costs we believe blockchain technology can cut out approximately 18%⁶ due to administrative savings and reduced governance and regulatory costs, effectively halving the frictional costs in the system.

Additionally, through the use of membership tokens, blockchain technology can bring back the original goals of the mutual where all contributions are entirely for the benefit of members. Aligned incentives will foster a community spirit rather the existing adversarial and unbalanced relationship between individual and large institution.

Blockchain technology allows a peer-to-peer insurance mutual to be recreated in a cost effective and scalable way. It allows the cooperative ethos to be regained while preserving the benefits of diversification.

## SOLUTION OVERVIEW

The following components are necessary for a peer-to-peer risk sharing mutual:

1. **MEMBERSHIP TRACKING** – A way to track individual members, including their proportional ownership.
2. **CLAIMS ASSESSMENT METHODOLOGY** – A way for claims to be approved or declined.
3. **CAPITAL MODEL** – To define how much capital is required to back the risks at any point in time.
4. **FUNDING** – Ability to attract capital to back the risks and reward that capital appropriately for the risks taken. Initially and on an ongoing basis.
5. **INVESTMENT RETURNS** – Insurers hold customers money until a claim event occurs. During this time they tend to invest these funds, usually quite conservatively, to earn additional return.
6. **PRODUCT** – A viable product to sell, including underwriting rules and other acceptance criteria.
7. **PRICING** – A method for determining the fair risk charge for the risk cover and a way for it to adjust over time.
8. **DISTRIBUTION** – Tools and incentives to attract new members to the mutual.
9. **IDENTITY** – An identity module will be required as part of the sign-up process to conform with legal and regulatory requirements.
10. **GOVERNANCE** – A way to upgrade, enhance and fine-tune the code in line with the wishes of the membership base, as well as the ability to interact with the non-blockchain world.
11. **TRANSPARENCY** – Real time reporting of capital position and risk exposures.
12. **LEGAL FRAMEWORK** – A safe legal and regulatory environment to operate within.

## MEMBERSHIP

A simple ERC-20 compatible token will be created to serve as the key internal incentive mechanism to bind the mutual together.

A continuous token model will be used so that tokens can be purchased at any time but at a variable price. This contrasts to more common ICO type approaches where there is a fixed purchase period with set price change points, followed by a speculation-driven market on exchanges.

The token price will vary based on 1) funding level of the Capital Pool and 2) the minimum amount of capital required to support existing covers (which provides a link to business growth):

```
TP = A + (MCR_ETH / C) × MCR%^4
```

Where:
- **TP** = Token Price in Ether
- **MCR_ETH** = The minimum amount of capital required to support existing covers, Minimum Capital Requirement, in Ether. The MCR is calibrated to a 99.5% solvency level.
- **MCR%** = Ratio of Capital Pool funds to the Minimum Capital Requirement.
- **A and C** = Fixed constants, to be calibrated based on the prevailing Ether price before launch.

### Token Creation Methods

Tokens can only be created in the following ways:

1. **INITIAL TOKENS** – Some tokens will be set aside for founders and early contributors when the contract is deployed.
2. **PURCHASED VIA THE TOKEN PRICE MODEL** – Anyone, at any point, can purchase tokens via the token price model. When funding is required (ie low MCR%) the price will be lower to encourage funds to be placed. Conversely the token price increases when funds are more plentiful.
3. **CLAIMS ASSESSMENT REWARDS** – Additional member tokens are allocated as an incentive to perform claims assessment. This will be limited to a fixed percentage of the cost of cover.
4. **RISK ASSESSMENT REWARDS** – Additional member tokens are allocated as an incentive for participating in risk assessment.
5. **GOVERNANCE** – Additional member tokens are allocated as an incentive for participating in governance.

### Token Usage

Membership tokens can be used in the following ways:

1. **PURCHASING COVER** – Member tokens can be used ("burned") to purchase cover. In this case the token value is determined by the continuous token model. 90% of the tokens used are burned, with the remaining 10% locked for the cover period plus 35 days, as they are required to submit a claim.
2. **CLAIMS ASSESSMENT STAKE** – To participate in claims assessment and earn the resulting income, member tokens must be staked.
3. **RISK ASSESSMENT STAKE** – To participate in assessing risks and earning commissions a stake is required.
4. **REDEMPTION** - If the Capital Pool has sufficient funds redemptions of member tokens in exchange for Ether is permitted.

### Restrictions

The following restrictions will apply:
1. Capital Pool needs to be above the MCR (MCR% > 100%).
2. Redemptions are capped per transaction.
3. The Capital Pool must have enough liquidity in Ether.
4. Sell price will be 2.5% below the prevalent buy price.

Only members of the mutual will be able to own tokens. As such, tokens cannot be transferred to any Ethereum address that has not been designated as a member.

## CLAIMS ASSESSMENT

There are two main approaches to claims assessment using blockchain technology. Firstly, using an oracle which is either a trusted off-chain information provider (eg to trigger parametric insurance events) or secondly, crowd-sourcing information and assessing claims using voting mechanics (eg a prediction market).

Under a discretionary mutual model there is a legal requirement that a group or sub-group of members decide on how funds are distributed. This immediately focusses efforts on the crowd-source approach but there are other arguments that limit the usefulness of parametric trigger-based cover:

1. **BASIS RISK⁷** - This can lead to poor customer outcomes especially when customers have suffered a loss but the trigger has not technically been met.
2. **ORACLE FAILURE** - Back-up claims process mechanisms will be required if the oracle were to fail.
3. **LIMITED PRODUCT SET** – Product development requires a reliable data oracle to exist. The data must also be sufficiently granular to construct a meaningful consumer product.

### Incentive Structure

A solution to this issue is to require claims assessors to have a significant stake in the success of the overall pool and a high disincentive to act dishonestly. This can be achieved by requiring a stake be posted in the form of membership tokens. The stake is deposited for a specified period of time and provided claims are assessed honestly it is returned. If the Advisory Board deems a claims assessor to be acting dishonestly it has the power to burn the staked member tokens.

In addition, the following other incentive structures will be put in place:

- Voting with the consensus outcome entitles claims assessors to a share of the fee pool. Fees will be paid as additional member tokens and valued at a fixed percentage of the cost of cover.
- Voting against the consensus outcome results in locking of the bond for a longer period.
- Voting power must add up to greater than 5x the cover amount, where voting power is determined by the number of staked member tokens used to vote.
- No consensus results in a reduced fee pool for claims assessors and the claim is then escalated to all members for a vote.
- Member tokens contributing to claims assessment voting become "inactive" and cannot contribute to another claims assessment for 12 hours.
- Calibrations of the incentive mechanisms need to be refined in testing.

## CAPITAL MODEL

The capital model determines the minimum capital the fund needs to hold. The funding rules in the next section then reference the Minimum Capital Requirement (MCR) and determine actions such as the token price and redemption restrictions.

The capital model will borrow heavily from EIOPA's Solvency II⁸ methodology which is calibrated to withstand events in a year with a 99.5% probability, or, in other words, a 1-in-200 year event.

### Diversification Benefits

An alternative approach is to 100% collateralise the insurance contracts, essentially holding the full sum assured value at all times. This comes at the cost of severely reduced capital efficiency. As a simple example, assume we have 10,000 (n) identical policies each with a chance of claim of 1% (p) for a sum assured of $100 (v):

```
Mean = μ = p × n = 100
Std Dev = σ = √(n × p × (1 - p)) = 9.9499
MCR = v × (μ + 2.58 × σ) = $12,567
Total Exposure = n × v = $1,000,000
```

In this example, we expect 1% of the total exposure to be paid out in claims, but with 10,000 contracts we only need 1.26% of the total exposure to be confident the fund will be solvent in 199 out of 200 scenarios.

### Modular Structure

The capital model is structured in multiple modules, where each module represents a product and currency pair. In addition, there is a currency module (fx) to account for currency risk. The modules are then combined at a total level to get the MCR.

For module one:
```
MCR_M1 = √(∑[i,j] Corr(i,j) × Exp(i) × Exp(j))
```

Where:
- **Corr(i,j)** is the correlation matrix of the individual pricing risk cells
- **Exp(i)** = Total probability-weighted exposure (or cover amount) in pricing risk cell i

The correlation matrix may be very simple if independence between cells can be assumed.

## FUNDING

The funding levels are all effectively governed by the continuous token model described in the membership section. The total Capital Pool value is V, which is calculated as the sum of all the asset values converted into Ether.

When the fund is first launched no covers can be purchased until an MCR% of 100% is achieved (which will be once the Capital Pool is equal to the Minimum Capital Requirement). Once that happens the fund goes live and the token model interacts with the capital model to increase or decrease the token price as required.

## INVESTMENT RETURNS

Investment returns are an often under-appreciated aspect to insurance as it allows the insurance entity to earn returns on the reserves it holds. This is a key component to insurers' profitability and therefore must be replicated in some fashion if Nexus Mutual is able to compete with existing insurance entities longer term.

As Nexus Mutual will hold all funds on-chain, it will restrict itself to assets of ETH and ERC20 tokens only. The investment process will be entirely automated using the Uniswap protocol to initiate trades.

Current most appropriate candidates for generating a return on ETH:
- Locking up ETH to generate interest in the proposed Proof of Stake system
- Investing in financial instruments based on collateralised lending
- Acting as a guarantor in state channel and payment channel networks

## PRODUCT

Initially the mutual will be launched with only one product, Smart Contract Cover with a fixed cover amount. The product will cover "unintended code usage" where someone, not necessarily the cover purchaser, has suffered a financial loss on the smart contract.

This product is seen to have a very good market fit for the early adopters of the platform. The initial product has been chosen for several reasons:

- Claims assessment can be done entirely remotely using publicly available data from block explorers
- A fixed cover amount means claims assessment is a simple "yes" or "no"
- The product pricing can be largely automated
- It is not necessary to confirm the member has an insurable interest
- The product is new to market with no alternatives existing
- The likely short-term nature of the covers is a good fit given the (lack of) on-chain investment options available

## PRICING & CAPACITY LIMITS

Given the lack of historic data on smart contract hacks, related information on code security will be used to assist pricing. Additionally, it is expected that most new contracts will start off with a very high (or even uninsurable) cost which is then reduced over time as the code is more battle-tested.

We are introducing the concept of **decentralised risk assessment**, which involves knowledgeable experts (think smart contract security auditors) staking value in the form of member tokens against specific risks to reduce the price of cover.

Important risk mitigation involves **capacity limits**. Exposure to any single smart contract (or related and very similar contracts) will be limited to a fixed percentage of the pool value.

## DISTRIBUTION

Distribution will initially focus on the relatively small group of cryptocurrency enthusiasts, entirely within the cryptocurrency sphere. There is ample opportunity in the short to medium term:

- **WELL-FUNDED PROJECTS** looking to deploy code could purchase cover in case something goes wrong
- **INDIVIDUALS** looking to interact with smart contracts may want extra confidence before exposing funds
- **PROJECTS LAUNCHING AN ICO** looking to provide confidence to prospective funders
- **MULTI-SIG WALLET CONTRACTS** could be insured

The longer-term vision is not for products to be mass marketed to consumers directly, but rather as a B2B2C platform that distribution partners can integrate with via blockchain's inherent open API architecture.

## IDENTITY

It will be necessary to identify all members of the mutual. This is because each member becomes a guarantor of the company and is required by company law in the UK to be identified.

There will be a simple identity process where KYC is conducted that links an Ethereum address to the customer, noting that all identifying information is not held on-chain.

## GOVERNANCE

An Advisory Board will be set-up to facilitate decisions requiring interaction with the non-blockchain world as well as govern some of the more extreme scenarios. Importantly, the Advisory Board has no custodial rights over the fund pool and cannot release funds to any particular person.

The Advisory Board will operate under two core principles:
1. **SUSTAINABILITY** – Protect existing members by ensuring the overall fund is sustainable
2. **GROWTH** - Enable sustainable premium and member growth

Advisory Board members will have the following broad authorities:
1. Facilitate and implement the wishes of the membership base
2. Punish bad actors within the Claims Assessment process
3. Meet all the legal and regulatory requirements of Nexus Mutual Ltd
4. Implement emergency pause functionality if required
5. White-list and vote on proposals where required

## TRANSPARENCY

A key requirement for operating a well-run mutual entity is providing members, potential members and other interested parties with accurate information regarding the financial health of the mutual. A website interface will be developed which reports on key metrics in real-time:

- Capitalisation ratio (MCR%)
- Exposure by pricing cell, and groupings
- History of capital metrics and token price
- Number of total member tokens outstanding split by locked vs transferrable
- Details on claims assessment results, with summary statistics

## LEGAL FRAMEWORK

Nexus Mutual has been set-up as a company limited by guarantee in the UK and will operate under a discretionary mutual structure. Members of the mutual will have a legal right to proportional ownership of the mutual and will also be responsible for providing the guarantee.

The guarantee will be set at £1 per member. This means if the mutual was ever to run out of money, each member is liable for a further £1 only.

A discretionary mutual is not a provider of insurance, it is a legal structure that enables members to trade with each other under the banner of one legal personality. Therefore, it is not required to conform with all the insurance regulatory and legal requirements.

## COMPETITIVE STRATEGY

A key challenge in open source business is retaining a competitive advantage when anybody can copy your entire code base. The following barriers and frictional costs are designed to keep Nexus Mutual relevant:

- **RISK ASSESSOR NETWORK** – Establishing a meaningful network of risk assessors and providing them adequate incentives to participate
- **SIZE OF CAPITAL POOL** – The faster scale can be achieved the larger the Capital Pool can grow and the greater the diversification benefits
- **CONTINUAL DEVELOPMENT** – A continued focus on improvement of the product
- **MEMBER TOKENS** – All customers are members and have a vested interest in the success of the mutual through token ownership

## APPENDIX A – COST REDUCTION ENABLED BY BLOCKCHAIN TECHNOLOGY

Focussing on the P&C column (Property and Casualty), the costs account for roughly 25% of premium, representing most of the ~35% of premium that gets lost in frictional costs. The most notable cost excluded is commission.

**MARKETING AND SALES SUPPORT** – These costs will largely remain as is for mainstream products.

**OPERATIONS AND IT** – The major area where large cost savings can be realised. We estimate these costs are reduced by 90%, as policy issuance and servicing are entirely automated.

**SUPPORT FUNCTIONS** – Large cost savings will materialise primarily because the number of people employed will be dramatically reduced. We assume 90% of these costs can be avoided.

Therefore, combining the above estimates, we expect to reduce the non-commission frictional costs by approximately 72% compared to a traditional insurance company. Converting it back to a percentage of premium income, this equates to a further 18% of premiums accruing in the mutual for the benefit of the members.

---

¹ https://en.wikipedia.org/wiki/Mutual_insurance  
² https://en.wikipedia.org/wiki/Law_of_large_numbers  
³ http://fsi.gov.au/publications/  
⁴ https://en.wikipedia.org/wiki/List_of_corporate_collapses_and_scandals  
⁵ McKinsey & Guy Carpenter reports on insurance operating costs  
⁶ See Appendix A  
⁷ Understanding basis risk in insurance contracts  
⁸ https://eiopa.europa.eu/regulation-supervision/insurance/solvency-ii