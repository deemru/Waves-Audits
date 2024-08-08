# Waves-Audits

- [Waves-Audits](#waves-audits)
  - [Who Am I?](#who-am-i)
    - [Key Contributions in the Waves Ecosystem](#key-contributions-in-the-waves-ecosystem)
  - [How Do I Work?](#how-do-i-work)
  - [How To Apply?](#how-to-apply)
    - [Payment](#payment)
  - [My Work](#my-work)
    - [Security Audits](#security-audits)
    - [Brief Audits](#brief-audits)

## Who Am I?

I am [Dmitrii Pichulin](https://github.com/deemru), an Information Security Specialist. I specialize in performing in-depth audits of smart contracts on the Waves blockchain. With years of experience in multiple disciplines, I provide nuanced insights that are often missed.

Explore my professional journey and contributions through my LinkedIn and GitHub profiles:

- [LinkedIn / deemru](https://www.linkedin.com/in/deemru/)
- [GitHub / deemru](https://github.com/deemru)

### Key Contributions in the Waves Ecosystem

- [w8io](https://github.com/deemru/w8io) - full-featured explorer for the Waves blockchain ([mainnet](https://w8.io), [testnet](https://testnet.w8.io)).
- [WavesKit](https://github.com/deemru/WavesKit) - all-in-one framework for the Waves blockchain ([article](https://habr.com/ru/articles/446112/)).
- [Waves-PHP](https://github.com/wavesplatform/waves-php) - another Waves blockchain framework tailored to common enterprise architecture.
- [Verifiable Elliptic Curve Random Oracle (VECRO)](https://github.com/deemru/VECRO) for the Waves blockchain ([article](https://habr.com/ru/articles/449342/)).
- Ethical Hacking & Bug Bounties - over 15 successful bug bounty reports for Waves since 2018.
- Security Audits - identified and resolved vulnerabilities across a diverse range of contracts and projects (partly [documented below](#my-work)).

## How Do I Work?

I offer two primary types of audits - security audits and brief audits. Their full meaning can be represented as comprehensive and brief security audits of Waves blockchain smart contracts respectively. A brief audit usually offers the same level of in-depth analysis as a comprehensive one but usually just for a single smart contract in isolation from the whole system, it is less verbose and without the final conclusions as a document.

The steps below outline the most efficient methodology for conducting a security audit, fine-tuned through years of practice:

- Repository Integration - Grant me access to the code repository for your smart contracts or system in question. This will enable a thorough examination of the codebase.
- Threat-Level Assessment - I will generate tickets specifying tasks and corresponding threat levels. Each ticket will pinpoint vulnerabilities and code quality issues, classifying them by their [level of severity](https://github.com/deemru/pepebridge-audit#severity-levels).
- Discussion and Rectification Phase - This stage involves a detailed discussion of the identified issues, recommended fixes, and any other concerns. Teams should aim to resolve the identified issues during this phase.
- Review and Re-Audit - After implementing the fixes, I will conduct a second audit to verify that the changes adequately address the identified issues and do not introduce new vulnerabilities.
- Polishing - These steps can be repeated as much as it is needed until the both parties considered it complete by resolving all the issues or achieving a certain level of security.
- Final Conclusion - The audit concludes with a comprehensive report summarizing the findings, implemented fixes, and any remaining concerns or recommendations.

## How To Apply?

- Initial Information - Compile the basic information about your project including its functionality and vision.
- Create Issue - Create an issue in [deemru/Waves-Audits](https://github.com/deemru/Waves-Audits) repository or reach out to me on Telegram under the username [@deemru](https://t.me/deemru) with the initial information.
- Repository Access - Be prepared to grant my GitHub account [@deemru](https://github.com/deemru) access to your code repository, with permissions to create issues.
- Smart Contracts - Your repository should already contain a skeletal structure of smart contracts that align with your project's basic description.
- Initial Evaluation - Once all required information is available, allow up to two business days for a preliminary estimate of the audit duration.
- Brief Audits - In the case of brief audits, there is a possibility of receiving the audit report on the same day.
- Audit Process - See [How Do I Work?](#how-do-i-work) steps.

### Payment

As the WavesDAO role grows I plan to take audit project tokens and direct them to WavesDAO treasury so they can be used to distribute salaries across the DAO.

## My Work

Below you will find an extensive list of projects I've audited, which serve as a testament to my expertise. These audits are a valuable resource whether you're looking to evaluate my skills, understand the basics of smart contracts security, or deepen your own proficiency in the field.

Please note that some repositories are private, so 404 errors for these links are expected.

So let my work tell the story.

### Security Audits

- PepeTeam Bridge - [Audit](https://github.com/deemru/pepebridge-audit) | [Twitter](https://twitter.com/cryptopepeteam/status/1648334370892128259) | [FAQ](https://pepe-team.tawk.help/article/pepeteam-bridges) | [DefiLlama](https://defillama.com/protocol/pepeteam-bridge)
- Vires.Finance - [Audit](https://github.com/deemru/viresfinance-audit) | [Medium](https://medium.com/@viresfinance/vires-finance-security-audit-complete-6480f32e6195) | [DefiLlama](https://defillama.com/protocol/vires-finance)
- Allbridge - [Audit](https://github.com/deemru/allbridge-waves-audit)
- Swop.fi - [Audit](https://github.com/deemru/swopfi-audit) | [Medium](https://medium.com/swop-fi/swop-fi-smart-contracts-audited-b12249b0ec7b) | [Twitter](https://twitter.com/Swopfi/status/1399652141850103811) | [DefiLlama](https://defillama.com/protocol/swop)

### Brief Audits

- PepeTeam WE Bridge - [#1](https://github.com/crypto-pepe/bridge-west-contracts/issues/1) | [#2](https://github.com/crypto-pepe/bridge-west-contracts/issues/2) | [#3](https://github.com/crypto-pepe/bridge-west-contracts/issues/3) | [#4](https://github.com/crypto-pepe/bridge-west-contracts/issues/4) | [#5](https://github.com/crypto-pepe/bridge-west-contracts/issues/5)
- StakeBooster - [#1](https://github.com/StakeBooster/SB-SC/issues/1) | [#2](https://github.com/StakeBooster/SB-gWX/issues/2) | [gauge](https://gist.github.com/deemru/813fcbc4d88950f5889327e539c637ea#file-gauge-ride) | [twap](https://gist.github.com/deemru/3e92367b1b2115064dfb84ebb56166a7#file-twap-ride)
- PowerDAO - [#3](https://github.com/pwrdao/dapp/issues/3)
- Waves Enterprise EAST - [#3](https://github.com/waves-enterprise/east-contract-waves/issues/3) | [#1](https://github.com/waves-enterprise/east-contract-waves/issues/1)
- Axly - [#1](https://github.com/vladislavpetushkov/axly-smartcontract/issues/1)
- PepeTeam Swap - [#1](https://github.com/crypto-pepe/swap-contracts/issues/1)
- WavesLands - [#4](https://github.com/waveslands/ride/issues/4) | [#3](https://github.com/waveslands/ride/issues/3) | [#2](https://github.com/waveslands/ride/issues/2) | [#182](https://github.com/wdstat/waveslands/issues/182)
- Tsunami Exchange - [#35](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/35) | [#34](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/34) | [#32](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/32) | [#23](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/23) | [#20](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/20) | [#19](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/19) | [#18](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/18) | [#15](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/15) | [#11](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/11) | [#7](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/7) | [#5](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/5) | [#4](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/4) | [#3](https://github.com/Tsunami-Exchange/tsunami-contracts/issues/3)
- PepeTeam Bridge - [#3](https://github.com/crypto-pepe/cip-waves-contracts/issues/3) | [#2](https://github.com/crypto-pepe/cip-waves-contracts/issues/2) | [#1](https://github.com/crypto-pepe/cip-waves-contracts/issues/1) | [#1](https://github.com/crypto-pepe/bridige-waves-contracts/issues/1)
- PepeTeam sWAVES - [#4](https://github.com/crypto-pepe/invest-contracts/issues/4) | [#3](https://github.com/crypto-pepe/invest-contracts/issues/3) | [#2](https://github.com/crypto-pepe/invest-contracts/issues/2) | [#1](https://github.com/crypto-pepe/invest-contracts/issues/1)
- Vires.Finance - [#69](https://github.com/viresfinance/dapp/pull/69) | [#68](https://github.com/viresfinance/dapp/pull/68) | [#52](https://github.com/viresfinance/dapp/pull/52) | [#50](https://github.com/viresfinance/dapp/pull/50) | [#49](https://github.com/viresfinance/dapp/pull/49)
- Puzzle Lend - [#1](https://github.com/vlzhr/puzzlelend-contracts/issues/1)
- Puzzle Swap - [#1](https://github.com/vlzhr/puzzleswap-contracts/issues/1)
