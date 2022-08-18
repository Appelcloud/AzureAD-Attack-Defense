# Azure AD - Attack and Defense Playbook

This publication is a collection of various common attack scenarios on Azure Active Directory and how they can be mitigated or detected.
All of the included scenarios, insights and comments are based on experiences from the contributors during their attack simulations, hands-on or real-world scenarios.

It should be considered a living document, which has to be updated as practices progress and changes in attack and defense techniques.
We invite identity or security experts from the community to work together on this publication and contribute updates, feedbacks, comments or further additions.

## Background
The initial idea for creating the ‘Azure AD Attack & Defense Playbook’ came from Thomas Naunheim. Our first Teams call was somewhere in Autumn 2020 where Thomas presented the idea and it was sold immediately. The first chapter was about the ‘Password Spray’ attack where we focused heavily on the AAD Identity Protection detection mechanism to detect ‘password spray’ type of attacks.

For the next chapters (Consent Grant & Azure DevOps) we had lucky to have Joosua Santasalo part of the project as an author and reviewer.

## Attack Scenarios

Typically, one chapter has taken approximately 1-2 months of calendar time so it has been quite an effort to put all four (4) chapters & appendix together. During the last 1,5 years we have published the following chapters:

### Scenarios:
- [Password Spray](PasswordSpray.md)
- [Consent Grant](ConsentGrant.md)
- [Service Principals in Azure DevOps Pipelines](ServicePrincipals-ADO.md)
- [Overview of Identity Security Monitoring in Microsoft Cloud](IdentitySecurityMonitoring.md)
- [Azure AD Connect Sync Service Account ](AADCSyncServiceAccount.md)
- [Replay of Primary Refresh (PRT) and other issued tokens](ReplayOfPrimaryRefreshToken.md)

In all chapters, we follow the same guideline. You can expect to find:

- Description of the common attack scenarios
- Detection of the attacks
- Mitigation for the attack and instructions how to enhance your environment security posture based on document scope

The following sections in this introduction contain a short description of each chapter you can find from the playbook.

### Contributors
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
        <td align="left"><a href="https://securecloud.blog/"><img src="https://pbs.twimg.com/profile_images/1314289282459275264/qINvzl6o_400x400.jpg" width="100px;" alt=""/><br /><sub><b>Joosua Santasalo</b></sub></a><br /><a href="https://twitter.com/SantasaloJoosua" title="Twitter">💬</a> <a href="https://securecloud.blog/" title="Blog">📖</a></td>
    <td align="left"><a href="https://samilamppu.com"><img src="https://pbs.twimg.com/profile_images/1361737408077828096/Jmjo2Evh_400x400.jpg" width="100px;" alt=""/><br /><sub><b>Sami Lamppu</b></sub></a><br /><a href="https://twitter.com/samilamppu" title="Twitter">💬</a> <a href="https://samilamppu.com" title="Blog">📖</a></td>
    <td align="left"><a href="https://www.cloud-architekt.net"><img src="https://www.cloud-architekt.net/assets/images/about.jpg" width="100px;" alt=""/><br /><sub><b>Thomas Naunheim</b></sub></a><br /><a href="https://twitter.com/thomas_live" title="Twitter">💬</a> <a href="https://www.cloud-architekt.net" title="Blog">📖</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->


## How to become part of the project and contribute?
- **Update or new content (Pull Request):** As already mentioned, we like to have a living document which is driven by the Azure AD community! Share your results and insights as part of this project! Send a pull request to add your content to this project.

- **Issues/Outdated content:** Protection features or tools changes continually. Update the out-dated content (as part of pull request) or create an issue to point out

- **Reviewer:** We also look for experts who want to review or discuss the existing or new content before publishing!

- **Feedback:** Feel free to suggest attack/defense scenarios that could be interesting for the community. We will add them to the backlog and idea collection!