# Plaid Bug Bounty
Plaid is a world-leading data network and payments platform to help you cut costs, 
onboard and convert more customers.<br/>
see details about its bug bounty program in hackerone [here](https://hackerone.com/plaid/)

## SCOPE

| Target Name                                      | Type        |
|--------------------------------------------------|-------------|
| [plaid-ruby](https://github.com/plaid/plaid-ruby) | Source code |
| [plaid-link-ios](https://github.com/plaid/plaid-link-ios) | Source code |
| production.plaid.com                             | Domain      |
| my.plaid.com                                     | Domain      |
| secure.plaid.com                                 | Domain      |
| cdn.plaid.com                                    | Domain      |
| [plaid-link-android](https://github.com/plaid/plaid-link-android) | Source code |
| [react-native-plaid-link-sdk](https://github.com/plaid/react-native-plaid-link-sdk) | Source code |
| [plaid-link-examples](https://github.com/plaid/plaid-link-examples) | Source code |
| [react-plaid-link](https://github.com/plaid/react-plaid-link) | Source code |
| dashboard.plaid.com                              | Domain      |
| demo.plaid.com                                   | Domain      |
| plaid.com                                        | Domain      |

**note**: <br/>
Any domain/property of Plaid not listed in the Scope, including data repos such as GitHub, PasteBin, etc. may be accepted at Plaid's discretion but is not guaranteed.


## methodology

| Step Number | Methodology Step                          | Description                                                                                     |
|-------------|------------------------------------------|-------------------------------------------------------------------------------------------------|
| 1           | Familiarize Yourself with the Scope     | Review the listed targets and prioritize critical areas.                                       |
| 2           | Gather Information                       | Explore repositories and read API documentation to understand functionalities.                 |
| 3           | Set Up Your Testing Environment          | Create a local environment and configure essential testing tools.                              |
| 4           | Conduct Reconnaissance                  | Perform subdomain enumeration and API endpoint mapping.                                        |
| 5           | Source Code Analysis                     | Analyze the source code for vulnerabilities, focusing on authentication, authorization, and data handling. |
| 6           | Perform Security Testing                 | Use automated scanning and manual testing to identify vulnerabilities.                         |
| 7           | Document Your Findings                   | Create detailed reports for each vulnerability, including evidence and remediation suggestions. |
| 8           | Responsible Disclosure                   | Follow submission guidelines and maintain professionalism in communications.                   |
| 9           | Continuous Learning and Improvement      | Review feedback and stay informed about new vulnerabilities and tools.                         |
| 10          | Iterate and Refine Your Approach        | Analyze results and adjust your methodology based on what works and what doesn’t.             |
