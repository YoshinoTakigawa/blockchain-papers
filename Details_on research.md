# Research Details

We would categorize challenges into three classes: technical challenges, risks, and understanding the impact.

Lets first consider technical challenges.

Limited scalability and latency- as pointed out by Kasireddy[1] and Yli-Huumo [6] blockchain systems have limited scalability and high latency. A transaction takes about 8 minutes, and it supports only about 2-3 transactions per second (Chepurnoy [3]).
Limited privacy - as pointed out by Kasireddy[1] and Yli-Huumo [6], although blockchain provides pseudo anonymizations, by analyzing the transaction graph and related other information, it is often possible to link users to transactions. Once one transaction is linked to a user, all transactions become known. Since blockchain transactions data are public or shared across a larger group (in the case of permissioned-blockchain), this means blockchain is riskier than using a credit card in terms of privacy. This could reduce adoption.
Storage constraints - As pointed out by Kasireddy[1] and Yli-Huumo [6], each node must store the full history of the blockchain. This affects transaction times and limits lightweight nodes, such as IoT devices, from joining the network. As time passes, history becomes larger, and the problem will be aggravated.
Unsustainable consensus mechanisms - As pointed out by Kasireddy[1], Yli-Huumo [6], Bitcoin list of problems [4], and Ethereum Problems [5], current consensus method is cumbersome and consumes a significant amount of energy. For example, as pointed out by [7], bitcoin energy consumption, if considered as a country, would be 39th in the world and higher than Australia.
Among other challenges are Quantum computing threat and Inadequate tooling pointed out by Kasireddy[1], and Sybil attack ( If an attacker attempts to fill the network with clients that they control). Furthermore, Ethereum Problems [5] and Bitcoin list of problems [4] discusses further issues.

There are many working on these problems. Kasireddy[2] a comprehensive overview of some of the approaches used to handle these problems. Further Blockchain papers [8] provides a curated list of relevant publications.

Let’s consider challenges related to risk. As we will discuss in the next section, risks stem from the irrevocability of operations and complicated mechanisms made possible by smart contracts. Following are some challenges.

Lack of methods to verify and limit risks - As pointed out by Kasireddy[2], lack of such tools is a major inhibitor to the blockchain. Among approaches that have been considered are formal contract verification, testing and simulation environments, a mechanism to undo operations or to limit the associated risks ( by specifying upper limits)
Lack of governance and standards - There are no clear regulatory processes for public blockchains. Finding a technical solution or a finding a process to solve the problem is a pressing need.
Thirdly, the impact of blockchain extends beyond computer science. We need to understand the economics side effects of the blockchain. Economics, Marketplaces and Trust sections in Blockchain papers [8] lists some of the current work in this area.

1. Kasireddy, Fundamental challenges with public blockchains, https://medium.com/@preethikasir...

2. Kasireddy, Blockchains don’t scale. Not today, at least. But there’s hope., https://hackernoon.com/blockchains-dont-scale-not-today-at-least-but-there-s-hope-2cb43946551a

3. Alex Chepurnoy, Some Open Problems in Blockchains, https://www.slideshare.net/AlexChepurnoy/some-open-problems-in-blockchains

4, Bitcoin list of problems, Weaknesses - Bitcoin Wiki, https://en.bitcoin.it/wiki/Weaknesses

5, ethereum/wiki, https://github.com/ethereum/wiki/wiki/Problems

6. Yli-Huumo,Where Is Current Research on Blockchain Technology?—A Systematic Review, https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5047482/

7. Bitcoin Energy Consumption Index - Digiconomist, https://digiconomist.net/bitcoin-energy-consumption

8. Blockchain Papers, decrypto-org/blockchain-papers, 

9. Ethereum Hard Fork Explained - Cryptovest, https://cryptovest.com/education/ethereum-hard-fork-explained/
