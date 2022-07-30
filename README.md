# Whitepaper

Created: July 30, 2022 12:13 PM
Last Edited Time: July 30, 2022 12:18 PM
Status: In Review

# The Boring Paper

**Abstract** - In this paper, we identify the Boring Obfuscation Protocol. Boring is a decentralized virtual private network and bandwidth market built on the Solana Network, providing an economic incentive for node providers with transparent programs for privacy to network users.

**Introduction -** Boring is a protocol for participants in virtual private networks to conduct transactions between node providers and bandwidth users. The protocol allows node providers to connect their endpoints via the Solana Program Library and attach metadata that identifies the attributes of their node, such as, for instance, geolocation. Bandwidth users will be able to locate and connect to these provided nodes, ultimately transacting with the provider via the protocol. The BOP token facilitates several aspects of this market. First, it allows Node providers to prioritize incoming traffic proportionate to their stake. It also promotes several defense mechanisms against attack vectors such as Sybil Attacks. Beyond that, it is the mechanism by which users and providers transact in their exchange of bandwidth for currency.

Initially, the Boring protocol will only support BOP tokens, but as the client interface is developed and appropriate pricing oracles are available, the ability for VPN users to fund their payment wallets will extend to other currencies on Solana. Finally, as cross-chain bridges become stronger infrastructure, Boring will allow payments to be made outside of Solana from other networks.

**Existing System Gaps -** Existing centralized VPN services have several significant flaws, namely lack of transparency. These services are structured to keep users locked into the service in monthly or yearly contracts. Beyond that, they are subject to breach as users' payment information is often kept on file in insecure centralized data storage. Boring corrects this with blockchain payments that can be processed per second and weighed by the amount of data utilized. The closest competitor is also a decentralized solution, Orchid Protocol, built on the Ethereum blockchain and plagued by the network issues it inherits from it. Also, the payments of a single public blockchain with no direction to mixing services can, at some point, lead to censorship of particular public addresses. Boring Protocol removes this issue by adding private payments using services such as Lava Cash. Allowing other network currencies to fund a payment wallet will further minimize the inconvenience.

**The Boring Ecosystem**

**Providers** - Virtual private networks depend on numerous endpoints or nodes connected to a central governing node that directs incoming traffic to them based on specific criteria. As Boring is built on Solana, the Solana chain inherits a portion of the role of the central node. Metadata will be presented with node connections that identify the end point's attributes and direct traffic to them based upon these factors. Beyond that, the chain will recognize the weight of the attached nodes' BOP token stake and proportionately direct traffic that meets the earlier criteria. Providers can set the price of the data they supply to the endpoint user.

**Clients -** Clients connect to virtual private networks to obfuscate personal private data that would generally be shared with endpoints such as websites and advertisers these websites serve. With Boring a client funds a BOP wallet with tokens and selects specific criteria for their connection, such as geolocation or connection latency. The Client also generates a budget based on the funding in their wallet and the amount of time they need to access the VPN service. As the user connects, these criteria are processed, and an endpoint that matches such is provided to them. As the connection persists, automatic payments are processed to compensate the provider for the endpoint the client is utilizing.

**Protocol -** As the protocol facilitates the means to solve the double coincidence of wants and attracts both providers and users via marketing strategy etc., such aspects must remain intact and viable. The protocol processes a fee for every connection payment in nano payments to do so.

**The Token -** The native digital cryptographically-secured token of the Boring protocol (BOP) is a transferable representation of attributed utility functions specified in the protocol/code of the Boring protocol. It is designed to be used solely as an interoperable utility token on the network/protocol.

BOP is a non-refundable functional utility token that will be used as the medium of exchange between participants on the Boring protocol in a decentralized manner. Introducing BOP aims to provide a convenient and secure mode of payment and settlement between participants who interact within the ecosystem on the Boring protocol. It is not, and not intended to be, a medium of exchange accepted by the public (or a section of the public) as payment for goods or services or the discharge of debt; nor is it designed or intended to be used by any person as payment for any goods or services whatsoever that are not exclusively provided by the issuer. The BOP token does not in any way represent any shareholding, participation, right, title, or interest in the Company, the Distributor, their respective affiliates, or any other company, enterprise, or undertaking. A BOP token will not entitle token holders to any promise of fees, dividends, revenue, profits, or investment returns and is not intended to constitute securities in Singapore or any relevant jurisdiction. BOP tokens may only be utilized on the Boring protocol, and ownership of BOP tokens carries no rights, express or implied, other than the right to use BOP as a means to enable usage of and interaction within the Boring protocol.

BOP also provides the economic incentives to encourage users to contribute to and participate in the ecosystem on the Boring protocol, thereby creating a win-win system where every participant is fairly compensated for its efforts. BOP is an integral and indispensable part of the Boring protocol; without BOP, there would be no incentive for users to expend resources to participate in activities or provide services to benefit the entire Boring ecosystem. Additional BOP tokens will be awarded to users based only on their actual usage, activity, and contribution to the Boring protocol. Users or holders of BOP tokens who did not actively participate will not receive any BOP incentives.

The Boring Protocol itself is simply a blockchain protocol that, by design, does not own or run any computing/storage servers, so third-party computing resources are required for processing transactions on the Boring protocol. Providers of these services/resources would require payment for the consumption of these resources to maintain network integrity, and BOP will be used as the native currency to quantify and settle the costs of these transactions. Following the same logic as dVPN users and node providers, purchasers of bandwidth would be required to fund the contract with BOP before it is entitled to use the service and be connected to the network. As the users consume data, their balance within the contract will be deducted to pay node providers. As node providers process traffic, they will receive BOP rewards within the contract and withdraw BOP as a withdrawal period expires. The withdrawal delay period is structured to prevent bad actor nodes.

Node providers will stake the BOP token to indicate their commitment to the network, and regional traffic will be distributed across the nodes in proportion to their stake (greater stakes will entitle the node to perform more work). Staked BOP will also be subject to a withdrawal delay, creating a defense mechanism against bad actors. The stake works as a governance mechanism in directing user traffic with the defense mechanism.

BOP tokens are designed to be utilized, which is the BOP distribution goal. The project to develop the Boring protocol would fail if all BOP token holders simply held onto their BOP and did nothing with it. In particular, we would like to highlight that BOP:

(a) does not have any tangible or physical manifestation, and does not have any intrinsic value (nor does any person make any representation or give any commitment as to its value);

(b) is non-refundable and cannot be exchanged for cash (or its equivalent value in any other digital asset) or any payment obligation by the Company, the Distributor, or any of their respective affiliates;

(c) does not represent or confer on the token holder any right of any form concerning the Company, the Distributor (or any of their respective affiliates), or its revenues or assets, including without limitation any right to receive future dividends, income, shares, ownership right or stake, share or security, any voting, distribution, redemption, liquidation, proprietary (including all forms of intellectual property or license rights), right to receive accounts, financial statements or other financial data, the right to requisition or participate in shareholder meetings, the right to nominate a director, or other financial or legal rights or equivalent rights, or intellectual property rights or any other form of participation in or relating to the Boring protocol, the Company, the Distributor or their service providers;

(d) is not intended to represent any rights under a contract for differences or any other agreement the purpose or pretended purpose of which is to secure a profit or avoid a loss;

(e) is not intended to be a representation of money (including electronic money), security, commodity, bond, debt instrument, unit in a collective investment scheme or any other kind of financial instrument or investment(f) is not a loan to the Company, the Distributor, or their respective affiliates. It is not intended to represent a debt owed by the Company, the Distributor, or any of their respective affiliates, and there is no expectation of profit; and

(g) does not provide the token holder with any ownership or other interest in the Company, the Distributor, or any of their respective affiliates. Notwithstanding the BOP distribution, users have no economic or legal right over or beneficial interest in the assets of the Company, the Distributor, or any of their affiliates after the token distribution. To the extent a secondary market or exchange for trading BOP does develop, it would be run and operated wholly independently of the Company, the Distributor, the distribution of BOP, and the Boring protocol. Neither the Company nor the Distributor will create such secondary markets, nor will either entity act as an exchange for BOP tokens.

## **Motherbored**

Boring will deploy a hardware device complete with firmware for participants to “plug and play” to support the network. These nodes will serve as routing points for the network to process traffic. In exchange, BOP token incentives will be distributed to encourage the deployment of such hardware devices/nodes.

## **Conclusion**

The issues presented by existing systems are solved with the implementation of the Boring Protocol. Other mechanisms to thwart attack vectors will be introduced as they are identified. The Boring Protocol provides the means to generate income in token rewards from an endpoint such as a computer or mobile device even when it is not used and therefore would only be a cost to the average consumer. It is a relatively untapped resource, and it will drive an entirely new market for bandwidth usage and privacy in one actionable program.

---

**Risks -**The Boring protocol is currently in the initial development stages, and there are a variety of unforeseeable risks. You acknowledge and agree that numerous risks are associated with acquiring BOP, holding BOP, and using BOP for participation in the Boring protocol. In the worst scenario, this could lead to the loss of all or part of BOP held.

**IF YOU DECIDE TO ACQUIRE BOP OR PARTICIPATE IN THE BORING PROTOCOL, YOU EXPRESSLY ACKNOWLEDGE, ACCEPT AND ASSUME THE FOLLOWING RISKS:**

****\1. Uncertain Regulations and Enforcement Actions The regulatory status of the Boring protocol, BOP, and distributed ledger technology is unclear or unsettled in many jurisdictions. The regulation of digital assets has become a primary target of regulations in all major countries in the world. It is impossible to predict how, when, or whether regulatory agencies may apply existing regulations or create new regulations with respect to such technology and its applications, including BOP or the Boring protocol. Regulatory actions could negatively impact BOP or the Boring protocol in various ways. The Company, the Distributor (or their respective affiliates) may cease operations in a jurisdiction in the event that regulatory actions, or changes to law or regulation, make it illegal to operate in such jurisdiction or commercially undesirable to obtain the necessary regulatory approval(s) to operate in such jurisdiction.

\2. Inadequate disclosure of information As of the date hereof, the Boring protocol is still under development. Its design concepts, consensus mechanisms, algorithms, codes, and other technical details and parameters may be constantly and frequently updated and changed. Although this lite paper contains the most current information relating to the Boring protocol, it is not absolutely complete. It may still be adjusted and updated by the Boring protocol team from time to time. The Boring protocol team has no ability or obligation to keep BOP holders informed of every detail (including development progress and expected milestones) regarding the project to develop the Boring protocol. Hence insufficient information disclosure is inevitable and reasonable.

\3. Failure to develop There is the risk that the development of the Boring protocol will not be executed or implemented as planned. It may be for a variety of reasons, including without limitation the event of a decline in the prices of any digital asset, virtual currency, or BOP, unforeseen technical difficulties, and shortage of development funds for activities.

\4. Security weaknesses Hackers or other malicious groups or organizations may attempt to interfere with BOP or the Boring protocol in a variety of ways, including, but not limited to, malware attacks, denial of service attacks, consensus-based attacks, Sybil attacks, smurfing, and spoofing. Furthermore, there is a risk that a third party or a member of the Company, the Distributor, or their respective affiliates may intentionally or unintentionally introduce weaknesses into the core infrastructure of BOP or the Boring protocol, which could negatively affect BOP or the Boring protocol. The future of cryptography and security innovations are highly unpredictable, and advances in cryptography, or technical advances (including without limitation development of quantum computing), could present unknown risks to BOP or the Boring protocol by rendering ineffective the cryptographic consensus mechanism that underpins that blockchain protocol.

\5. Other risks The potential risks briefly mentioned above are not exhaustive. There are other risks (as more particularly set out in the Terms and Conditions) associated with your participation in the Boring protocol, as well as the acquisition of, holding, and use of BOP, including those that the Company or the Distributor cannot anticipate. Such risks may further materialize as unanticipated variations or combinations of the aforementioned risks. You should conduct full due diligence on the Company, the Distributor, their respective affiliates, and the Boring protocol team, as well as understand the overall framework, mission.
