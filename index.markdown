---
layout: default
---

# UC Berkeley Decentralized Finance Spring 2021

For information about future offering of the DeFi course, please join the [berkeley-blockchain@googlegroups.com](https://groups.google.com/forum/#!forum/berkeley-blockchain) mailing list.

## Instructors

<table style="table-layout: fixed; font-size: 88%;">
  <thead>
    <tr>
      <th style="width: 25%;"><img style="object-fit:cover" width=132 height=200 src="https://vcresearch.berkeley.edu/sites/default/files/styles/faculty_photo_full/public/2018-01/christine_parlour.jpg?itok=MubDXnwu" alt="Christine Parlour"></th>
      <th style="width: 25%;"><img background-size=cover width=132 height=200 src="https://people.eecs.berkeley.edu/~dawnsong/dawn-berkeley.jpg" alt="Dawn Song"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Christine Parlour</td>
      <td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
    </tr>
    <tr>
      <td>Lecturer, <a href="http://haas.berkeley.edu/">Haas Business School</a></td>
      <td>Professor, <a href="https://eecs.berkeley.edu/">EECS</a></td>
    </tr>
  </tbody>
</table>

## Volunteer Teaching Assistant

Tianchen Liu

## Class Time

6-8pm PT Thu, starting April 1, Spring B.

## Enrollment and Participation

To get more information about the course or get instructor approval for taking the course, please fill in [this form](https://docs.google.com/forms/d/e/1FAIpQLScoLJB9CR5ZXcx6EgyYvgJkodQqslCEKpUh9GuhxOvrsuIytA/viewform).

## Course Description

The purpose of this class is to bring together students and experts in Computer Science and Finance to discuss the emerging area of Decentralized Finance (or DeFi). By utilizing blockchain and smart contract technologies, DeFi aims to provide a new platform for programmable, automated finance services that remove the reliance on central trust and intermediaries. With its rapid growth, the total value locked in decentralized finance — a measure of the total value of assets committed to the DeFi ecosystem —has reached over $40 billion.

Our goal is to provide a framework to understand this new area of financial services.  For each finance function, we will consider

- the current intermediated structure
- the DeFi version (actual or proposed) that fulfills the function

Is either one of these optimal?  We will evaluate both through the lens of CS and finance. Is the application computable (efficiency, decidable), programmable (automatic)?  Is the application welfare-enhancing and stable (not a source of systemic risk).  How do the new and old systems interact? 

We will cover a broad spectrum of topics including:

1. An introduction: The role of the financial system and the CS basics behind decentralized systems

2. Decentralization of reputation and information including oracles, identities, proofs of properties

3. Economics and challenges behind different types of decentralized financial services and instruments, including stable coins, decentralized exchanges (e.g, automated market makers), synthetics and derivatives, lending, insurance, portfolio management, prediction markets

4. Requirements and technologies for decentralized regulation including auditable privacy, measurement and tracking of systemic risk and its computability

5. Technologies and challenges for a more responsible data economy including data ownership, data monetization and valuation, controlled use and misuse of data

6. Security issues and countermeasures in DeFi

## Participants

This course is primarily designed for PhD students and PhD students may take it for credit or audit.  Master’s and undergraduate students with permission may take it for credit or audit.

## Grading

Students who wish to audit must attend ALL sessions. Students who take it for credit will be required to also produce a short writeup on an aspect of the course that focuses on an open research question in this area. The writeup is due on May 14.

## Course schedule (subject to change)

Date | Topic 
-----|------
04/01 | [(Recording)](https://youtu.be/KKoE275LYZY) Introduction to traditional financial systems [(Dawn's Slides)](https://drive.google.com/file/d/1l2HvMqFm_bo9dAoSVDhc84WKY-s9BHO7/view?usp=sharing) [(Christine's Slides)](https://drive.google.com/file/d/1zh-4cxx5c1xmzWVRfvkqLgxvCPj2eiIg/view?usp=sharing)
04/08 | **Part I**: Introduction to blockchain and smart contracts supporting DeFi applications <br/> Dawn: short intro on blockchain & smart contracts [(Slides)](https://drive.google.com/file/d/1YWz2ZCm7JWC3YmYiC6Fo3c_WgXfLkCVn/view?usp=sharing) <br/> Lewis Gudgeon: [DeFi SoK](https://arxiv.org/abs/2101.08778) <br/> **Part II**: Stable coins <br/> Rene Reinsberg: Introduction on Stable Coins [(Slides)](https://drive.google.com/file/d/1vVaeBMBIODJdbF3Zb_JDiU8hfAG589So/view?usp=sharing) <br/> Ariah Klages-Mundt: [In search of stability](https://arxiv.org/abs/2006.12388) [(Slides)](https://drive.google.com/file/d/1M2dj65Mh6jWpvdWOGNZsWaIH-vn6fy_F/view?usp=sharing) <br/> Ye Li: Managing Stablecoins: [Optimal Strategies, Regulation, and Transaction Data as Productive Capital](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3757083) [(Slides)](https://drive.google.com/file/d/1Ixq6rtNis3RxVDnjM52GL5klGnTNNgrH/view?usp=sharing) <br/> Christine: Stablecoins vs. traditional payments [(Slides)](https://drive.google.com/file/d/1FGPbycbWavRnwVG0S79jmnHXbP9m5y4k/view?usp=sharing) [(Paper)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3711777)  
04/15 | - Dan Robinson (Paradigm): Overview of DEX <br/> [A short history of uniswap](https://uniswap.org/blog/uniswap-history/) <br/> [The rise of AMMs](https://medium.com/dragonfly-research/what-explains-the-rise-of-amms-7d008af1c399) <br/> - Guillermo A Angeris (Stanford): Overview & analysis of AMM [(Slides)](https://drive.google.com/file/d/1XICw-rKaWoZgWQWl5r2Ihkn0wUnQzNty/view?usp=sharing) <br/> [An analysis of Uniswap markets](https://arxiv.org/abs/1911.03380) <br/> [Improved price oracles: constant function market makers](https://arxiv.org/abs/2003.10001)  <br/> - Jun Aoyagi (UC Berkeley): Liquidity implications of constant product market makers [(Slides)](https://drive.google.com/file/d/1vjYKso-fF5HlmfOnqoa5JyUAeXjHOssA/view?usp=sharing) <br/> [Angeris et al (2019)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3602203) <br/> [Glostem and Milgrom (1985)](https://www.sciencedirect.com/science/article/pii/0304405X85900443) <br/> - Alfred Lehar (Univ. of Calgary): Empirical analysis of Uniswap [(Slides)](https://drive.google.com/file/d/1ZteucrBVxcllvQuurj8LTu1_aeY_EdHt/view?usp=sharing)
04/22 | [(Recording)](https://youtu.be/4htz9yb-W9M) New ways to organize existing financial products <br/> **Part I**: Regulation in DeFi  <br/> - William Magnuson: Regulation in FinTech [(Slides)](https://drive.google.com/file/d/132yzT1lr9x50H2KNSQrp_4_s5kSE_0S3/view?usp=sharing) <br/> [General Overview](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3148036) <br/> [On Systemic Risk](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3027525)  <br/> **Part II**: Lending <br/> - Daniel Perez: The ins and outs of Protocol for Loanable Funds [(Slides)](https://daniel.perez.sh/talks/2021/plfs) <br/> [DeFi Protocols for Loanable Funds: Interest Rates, Liquidity and Market Efficiency](https://arxiv.org/abs/2006.13922) <br/> [Liquidations: DeFi on a Knife-edge](https://arxiv.org/abs/2009.13235) 
04/29 | Do Kwon (Terra): Overview of synthetics and derivatives [(Slides)](https://drive.google.com/file/d/1gEKcG0lWDkY-hpdkylSHtYm_63iDjalZ/view?usp=sharing) <br/>Christine: portfolio management in traditional finance <br/> Campbell Harvey (Duke Univ.): DeFi - Opportunities and Risks [(Slides)](https://drive.google.com/file/d/1bhqPCwRku_KkB3rUxITf6-9YEC17DkUa/view?usp=sharing)
05/06 | [(Recording)](https://youtu.be/0IWrsWk7oLY) Benedikt Bunz (Stanford): auditable privacy; ZKP etc. applications in DeFi [(Slides)](https://drive.google.com/file/d/1ioOEUMAG79ly0Z3xwc_fmKsykpnkhgtH/view?usp=sharing) <br/> Fabian Vogelsteller (Lukso): decentralized identity standards, future of decentralized identity [(Slides)](https://drive.google.com/file/d/1BMpdbJdUnxjCZ1haS8VpoUsQMI6v9tJT/view?usp=sharing) [ERC 725](https://github.com/ERC725Alliance/ERC725/blob/master/docs/ERC-725.md) [LSPs](https://github.com/lukso-network/LIPs/tree/master/LSPs) <br/> Deepak Maram (Cornell): decentralized identity system & CanDID [(Slides)](https://drive.google.com/file/d/1eKM4JpQawGjHR5Iy-PGgzaDnzr2wX-3k/view?usp=sharing)
05/13 | Information markets: oracles, prediction markets, data market, data valuation, data tokenization <br/> - Fan Zhang [Duke University]: Overview of Oracles [(Slides)](https://drive.google.com/file/d/1t3uwN88MCpmBPRPdKCoVVvXtXF3VFKMe/view?usp=sharing) <br/> [DECO Paper](https://arxiv.org/abs/1909.00938) <br/> [DECO Blog](https://hackingdistributed.com/2019/09/03/DECO/) <br/> - Shota Ichihashi [Bank of Canada]: The Economics of Data [(Slides)](https://drive.google.com/file/d/1MIP5h_ZGpzbWP8ZEtvZd2Ii0z85mMQtR/view?usp=sharing) <br/> [The Economics Of Social Data: An Introduction](https://cowles.yale.edu/sites/default/files/files/pub/d21/d2171-r.pdf) <br/> [Blog about paper above](https://voxeu.org/article/economics-social-data) <br/> Dawn: Data Valuation using Shapley Value [(Slides)](https://drive.google.com/file/d/1aGvBqOggEOAP9idOZW5a86j6cPjXctte/view?usp=sharing)
05/20 Bonus | [(Recording)](https://youtu.be/9UkjSVbBONs) Security issues and countermeasures in DeFi <br/> - Sam Sun (Paradigm): overview of different types of security issues and real-world exploits in DeFi [(Slides)]( https://drive.google.com/file/d/1XO5_9hj6Cs0kAp3wgyz1qHLv9nzUJe8J/view) <br/> [Intro to Solidity](https://medium.com/block-street/coding-a-smart-world-introduction-to-solidity-ethereum-studio-36198a3db998) <br/> [Solidity Documentation](https://docs.soliditylang.org/en/develop/introduction-to-smart-contracts.html) <br/> - Arthur Gervais (Imperial College London): flashloan analysis, BEV empirical study, security countermeasures. [(Slides)](https://drive.google.com/file/d/14HIgT9RaRNUfxjvIt4bOyNxk5j35lM32/view?usp=sharing) <br/> [High-Frequency Trading on Decentralized On-Chain Exchanges](https://arxiv.org/pdf/2009.14021.pdf) <br/> [Attacking the DeFi Ecosystem with Flash Loans for Fun and Profit](https://arxiv.org/pdf/2003.03810.pdf)