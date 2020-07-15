# Project-Deluge
Identifying technical vulnerabilities

---
### Announcement: [here](https://github.com/KuChainNetwork/Project-Deluge/blob/master/announcement/announcement003.md);


---
![kuChainDeluge](https://github.com/KuChainNetwork/Project-Deluge/blob/master/imgs/KuChainBetanetCoverOther.jpg?raw=true)

### KuChain Betanet Bug Bounty Program Rule 

This bounty brief describes the rules of KuChain Betanet Bug Bounty Program, as well as the eligibility of vulnerabilities and the rewards.



:point_right: Program duration: ***UTC+8 2020.07.01 10:00am - 2020.08.07 10:00am***. 

Vulnerabilities submitted before UTC+8 2020.07.01 10:00am and after UTC+8 2020.08.07 10:00am will be considered invalid. 

Please upload your vulnerability report in KuChain GitHub repository - [***Project Deluge(Issues)***](https://github.com/KuChainNetwork/Project-Deluge/issues).



---

#### Rewards/Ratings:

:point_right: According to the vulnerability severity, each effective bug report will be paid ***$ 200 – $ 10,000***. Vulnerabilities with extreme impact may receive a reward of up to :warning: ***$ 10,000*** :warning: .  

We are eager to work with the community to make sure that everyone's finding is rewarded fairly - based on the vulnerability's impact on business and overall severity.



***Rewards will be paid out in KCS.***



When your submission is verified as a valid and rewarded vulnerability, please provide us with an ***ERC-20 address*** to receive your reward.  You may register a ***KuCoin*** account [here](https://www.kucoin.com/).



*Prices will change with the cryptocurrency markets and the dollar amount listed below could change.

*Please note that only vulnerabilities with a working proof of concept that shows how it can be exploited will be considered eligible for monetary rewards.*



---

#### Vulnerability Severity

| **Impact** | Likelihood | Severity |
| ---------- | ---------- | -------- |
| High       | High       | Critical |
| High       | Medium     | Severe   |
| High       | Low        | Moderate |
| Medium     | High       | Severe   |
| Medium     | Medium     | Moderate |
| Medium     | Low        | Low      |
| Low        | High       | Moderate |
| Low        | Medium     | Low      |

*Likelihood*: Likelihood represents the possibility that a particular vulnerability is discovered and exploited.

*Impact*: Impact measures the loss caused by an attack using this vulnerability.

*Severity*: Severity indicates the magnitude of the vulnerability.

Likelihood and impact are divided into three levels: high, medium and low.

Severity is decided by likelihood and impact with four levels: critical, severe, moderate and low.



---

#### Reward Range

| **Technical severity** | Reward range      |
| ---------------------- | ----------------- |
| P1 - Critical          | $ 3,500 or above  |
| P2 - Severe            | $ 1,200 - $ 3,500 |
| P3 - Moderate          | $ 600 - $ 1,200   |
| P4 - Low               | $ 200 - $ 600     |



---

#### KuChain Resources

:information_source:KuChain API Documentation : [here](https://github.com/KuChainNetwork/docs)

:information_source:KuChain Betanet Faucet :  [here](https://beta.kuchain.network)

:information_source:KuChain Block Explorer:  [here](https://explorer.kuchain.network)

:information_source:Draft White Paper (to be released by phases) ：[here](https://github.com/KuChainNetwork/docs/blob/master/whitepaper/en/kratos.md)


---
#### Vulnerability Classifications  

#### In Scope:

:information_source: https://github.com/KuChainNetwork/kratos



##### P1 (Critical):

**Vulnerabilities that could undermine the fund safety of any user or business runner, including:**

1. Vulnerabilities that could undermine the safety of any user or validator's fund/fee.
2. Vulnerabilities that could severely undermine trading or token economy.
3. Remote Code Execution on any Chain node, such as Validator nodes, Witness nodes, or Seed nodes.

4. Vulnerabilities related to key generation, encryption, decryption, signing and verification.
5. Vulnerabilities that could disrupt the Chain governance.
6. Transaction origin spoofing or transaction malleability.



##### P2 (Severe):

**Vulnerabilities with similar impact as P1 vulnerabilities, but are dependent on specific prerequisites, including:**

1. Denial of service of any Chain validator node.

2. Vulnerabilities that could undermine or disrupt trading or token economy.

3. Vulnerabilities that could disrupt the Validator consensus result and performance.

4. Vulnerabilities that could cause the node to be unable to respond with transactions and balances.

   

##### P3 (Moderate):

**Denial of service of critical functions, including:**

1. Denial of service of nodes.



##### P4 (Low):

**Denial of service of non-critical functions, including:**

1. Vulnerabilities that could affect the stability or availability of Chain / Explorer.



---

#### Ineligible Issues (Will be closed as out of scope)  

- **Issues that have no security impact. Including but not limited to:**

1. Web garbled.
2. Failure to load a web page.
3. Some functions cannot be used.



- **Vulnerabilities that are not exploitable. Including but not limited to:**

1. Reports from automated tools or scans which are meaningless (e.g. the lower version of Web Server).
2. Self-XSS.
3. JSON Hijacking without sensitive information.
4. CSRF with negligible security impact (e.g. adding to favorites, modifying ordinary personal data which is unrelated to important business).
5. Exposure of internal IP address or domains.
6. 401 basic certified fishing.
7. Program path trust issues.
8. Logcat information disclosure without sensitive information.



- **Speculation without any evidence.  Including but not limited to:**

1. Theoretical vulnerabilities.
2. Use of known vulnerable libraries without actual proof of concept.



- **Phishing (E.g. HTTP Basic Authentication Phishing).**
- **Internally known issues, duplicate issues, or issues which have already been made public.**



:point_right: Participants maliciously attack or instigate others to maliciously attack KuChain as part of the Bug Bounty Program will be disqualified. Participants found to jeopardize the security of any private data and asset of KuChain users and/or to steal such information will be pursued according to the relevant legal responsibility.



---

#### Review Process

Given that vulnerabilities in P1 level may affect the progress of Bug Bounty Program itself, we will not publicize P1 level vulnerabilities until their repairation.

 While vulnerabilities in P2 to P4 level without substantial detriment to the event, we will inform you in the comment area under each bug submission as soon as we confirm its effectiveness. 

 Below is the detail review process of your bug report.



1. Submit your vulnerability report on [GitHub](https://github.com/KuChainNetwork/Project-Deluge/issues); 
2. Preliminary examination. For vulnerability report deemed to be invalid, its particular bulletin board will be closed after fair and transparent reasoning of the disqualification cause being given by KuChain team in the comment area (e.g. out of scope, incorrect report format, duplicates). Valid and identifiable vulnerability reports will be qualified for the next round of review; while for valid but not identifiable ones, KuChain team will reach out to the submitters via email to make sure we get the chance to fix every single vulnerability.
3. Vulnerability confirmed in Step 2 will be graded by KuChain jury. We will inform the submitter with the vulnerability level in the comment area under the corresponding bug report right after the vulnerability level is determined.
4. A week after the end of Bug Bounty Program, an official announcement on GitHub will be publicized, citing all valid and rewarded bug reports, including their submitters, vulnerability level and the corresponding rewards. Such information will also be communicated to the submitters by email.
5. In the event of any objection concerning the jury’s decision, a one-week appeal period is set after the announcement where each bug submitter has one appeal opportunity. 
6. Rewards will be paid out in KCS to an ERC-20 address of qualified submitters one week after the appeal period.



---

#### :warning: Attention:warning:

- KuChain may be reset and dropped due to some vulnerabilities' repairation during the program. Vulnerabilities found in these cases will be considered invalid. 
- Vulnerabilities which have already known by Cosmos-SDK will be considered invalid.



---

:warning: *The final interpretation right belongs to KuChain technical team and KuChain jury.*
