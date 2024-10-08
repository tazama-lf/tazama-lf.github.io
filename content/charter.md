---
title: "Charter"
date: 2023-11-29
draft: false
---
<!-- Google tag (gtag.js) -->
<script src="https://www.googletagmanager.com/gtag/js?id=G-PZL0S57CC7" integrity="sha384-VHjxUTx/hhzdIOp4B+1uudBz9pmgepYfOpcEc3Qspl5M1gW6rnWMFCEOMXQ3z8JT" crossorigin="anonymous"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-PZL0S57CC7');
</script>

## Technical Charter

**Adopted November 29, 2023**

This Charter sets forth the responsibilities and procedures for technical contribution to, and oversight of, the Tazama open source project (the “Project”), which has been established as a project of LF Charities, Inc., a Delaware nonprofit corporation and Section 509(a)(3) supporting organization that is tax exempt under Section 501(c)(3) of the Internal Revenue Code of the United States (“LF Charities”). All contributors (including committers, maintainers, and other technical positions) and other participants in the Project (collectively, “Collaborators”) must comply with the terms of this Charter.

## 1. Mission and Scope of the Project

a. The mission of the Project is to develop and maintain an open source fraud detection mechanism for instant payment systems, in order to improve the safety of using those systems, particularly for the poorest and most vulnerable customers that those systems serve.

b. The scope of the Project includes collaborative development under the Project License (as defined herein) supporting the mission, including documentation, testing, integration and the creation of other artifacts that aid the development, deployment, operation or adoption of the open source project.

## 2. Technical Steering Committee

a. The Technical Steering Committee (the “TSC”) will be responsible for all technical oversight of the open source Project.

b. The TSC voting members are initially the Project’s Committers that are designated as voting TSC members. At the inception of the project, the Committers of the Project will be as set forth within the “CONTRIBUTING” file within the Project’s code repository. The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in the CONTRIBUTING file. Any meetings of the Technical Steering Committee are intended to be open to the public, and can be conducted electronically, via teleconference, or in person.

c. TSC projects generally will involve Contributors and Committers. The TSC may adopt or modify roles so long as the roles are documented in the CONTRIBUTING file. Unless otherwise documented:

i. Contributors include anyone in the technical community that contributes code, documentation, or other technical artifacts to the Project;

ii. Committers are Contributors who have earned the ability to modify (“commit”) source code, documentation or other technical artifacts in a project’s repository; and

iii. A Contributor may become a Committer by a majority approval of the existing Committers. A Committer may be removed by a majority approval of the other existing Committers.

d. Participation in the Project through becoming a Contributor and Committer is open to anyone so long as they abide by the terms of this Charter.

e. The TSC may (1) establish work flow procedures for the submission, approval, and closure/archiving of projects, (2) set requirements for the promotion of Contributors to Committer status, as applicable, and (3) amend, adjust, refine and/or eliminate the roles of Contributors, and Committers, and create new roles, and publicly document any TSC roles, as it sees fit.

f. The TSC may elect a TSC Chair, who will preside over meetings of the TSC and will serve until their resignation or replacement by the TSC.

g. Responsibilities: The TSC will be responsible for all aspects of oversight relating to the Project, which may include:

i. coordinating the technical direction of the Project and maintaining a list of technical requirements for features, functionality and performance of any release of code of the Project (collectively, the “Technical Requirements”);

ii. approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope);

iii. organizing sub-projects and removing sub-projects;

iv. creating sub-committees or working groups to focus on cross-project technical issues and requirements;

v. appointing representatives to work with other open source or open standards communities;

vi. establishing community norms, workflows, issuing releases, and security issue reporting policies;

vii. approving and implementing policies and processes for contributing (to be published in the CONTRIBUTING file) and coordinating with LF Charities to resolve matters or concerns that may arise as set forth in Section 7 of this Charter;

viii. discussions, seeking consensus, and where necessary, voting on technical matters relating to the code base that affect multiple projects; and

ix. coordinating any marketing, events, or communications regarding the Project.

## 3. End User Committee

a. “End User Organization” means any national bank, government financial agency, regulator, or law enforcement agency of any country, with particular attention to include those specifically designated by the United Nations as a “Least Developed Country”. Banks, fintechs, other financial organizations, or other nonprofit organizations in a regulatory or other specialty related to financial crime also qualify as End User Organizations.

b. The End User Committee (“EUC”) is composed of one individual appointed by each End User Organization and at the inception of the Project the initial members of the EUC will be those organizations listed on Project’s web site. Any End User Organization may appoint a different representative to the EUC upon notice to the Project.

c. The EUC will aim to meet quarterly unless a different meeting cadence is chosen by the EUC. The purpose of the EUC is to provide the project with feedback on use cases and features and other requirements of end users of the Technical Project. If at any point the TSC feels that the EUC has grown to a size where it would be advisable for purposes of efficiency to adopt an alternative structure (such as having representation from industry associations of End User Organizations versus particular End User Organizations appoint representatives to the EUC), the TSC can change the provisions of this Section 3 by simple vote.

## 4. Charitable Committee

a. The Charitable Committee is composed of representatives of charitable organizations, nonprofits, government agencies and/or private foundations who support through their work the Charitable Purposes as identified by LF Charities. LF Charities will maintain and publish requirements and criteria for participation on the Charitable Committee. The Chair of the TSC will also be a member of the Charitable Committee.

b. The role of the Charitable Committee is to: (a) provide the Project with advice and insight with respect to the Charitable Purposes: (b) share information on the work of the Project with the global communities served by the organizations represented on the Charitable Committee; (c) approve changes to the Technical Requirements; and (d) approve amendments to this Charter to the extent that any such amendment modifies or replaces any Charitable Purpose.

## 5. Voting

a. While the Project aims to operate as a consensus-based community, if any TSC or EUC decision requires a vote to move the Project forward, the voting members of the TSC or EUC, as applicable, will vote on a one vote per voting member basis.

b. Quorum for meetings requires at least fifty percent of all voting members of the TSC or EUC, as applicable, to be present. The TSC or EUC may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.

c. Except as provided in Section 7.c. and 8.a, decisions by vote at a meeting require a majority vote of those in attendance, provided quorum is met. Decisions made by electronic vote without a meeting require a majority vote of all voting members of the TSC or EUC, as applicable.

d. In the event a vote cannot be resolved, any voting member of the TSC or EUC, as applicable, may refer the matter to LF Charities for assistance in reaching a resolution.

## 6. Compliance with Policies

a. Contributors will comply with the policies of LF Charities as may be adopted and amended by LF Charities, including, without limitation the policies listed at <https://lf-charities.org/policies/>.

b. The TSC may adopt a code of conduct (“CoC”) for the Project, which is subject to approval by LF Charities. In the event that a Project-specific CoC has not been approved, the LF Charities Code of Conduct listed at <https://lf-charities.org/policies/> will apply for all Collaborators in the Project.

c. When amending or adopting any policy applicable to the Project, LF Charities will publish such policy, as to be amended or adopted, on its web site at least 30 days prior to such policy taking effect; provided, however, that in the case of any amendment of the Trademark Policy or Terms of Use of LF Charities, any such amendment is effective upon publication on LF Project’s web site.

d. All Collaborators must allow open participation from any individual or organization meeting the requirements for contributing under this Charter and any policies adopted for all Collaborators by the TSC, regardless of competitive interests. Put another way, the Project community must not seek to exclude any participant based on any criteria, requirement, or reason other than those that are reasonable and applied on a non-discriminatory basis to all Collaborators in the Project community.

e. The Project will operate in a transparent, open, collaborative, and ethical manner at all times. The output of all Project discussions, proposals, timelines, decisions, and status should be made open and easily visible to all. Any potential violations of this requirement should be reported immediately to LF Charities.

## 7. Community Assets

a. LF Charities will hold title to all trade or service marks used by the Project (“Project Trademarks”), whether based on common law or registered rights. Project Trademarks will be transferred and assigned to LF Charities to hold on behalf of the Project. Any use of any Project Trademarks by Collaborators in the Project will be in accordance with the license from LF Charities and inure to the benefit of LF Charities.

b. The Project will, as permitted and in accordance with such license from LF Charities, develop and own all Project GitHub and social media accounts, and domain name registrations created by the Project community.

c. Under no circumstances will LF Charities be expected or required to undertake any action on behalf of the Project that is inconsistent with the tax-exempt status or charitable purpose, as applicable, of LF Charities.

## 8. General Rules and Operations

a. The Project will:

i. engage in the work of the Project in a professional manner consistent with maintaining a cohesive community, while also maintaining the goodwill and esteem of LF Charities and other partner organizations in the open source community; and

ii. respect the rights of all trademark owners, including any branding and trademark usage guidelines.

## 9. Intellectual Property Policy

a. Collaborators acknowledge that the copyright in all new contributions will be retained by the copyright holder as independent works of authorship and that no contributor or copyright holder will be required to assign copyrights to the Project.

b. Except as described in Section 7.c., all contributions to the Project are subject to the following:

i. All new inbound code contributions to the Project must be made using Apache License, Version 2.0 (the “Project License”).

ii. All new inbound code contributions must also be accompanied by a Developer Certificate of Origin ([http://developercertificate.org](http://developercertificate.org)) sign-off in the source code system that is submitted through a TSC-approved contribution process which will bind the authorized contributor and, if not self-employed, their employer to the applicable license;

iii. All outbound code will be made available under the Project License.

iv. Documentation will be received and made available by the Project under the Creative Commons Attribution 4.0 International License (available at [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/)).

v. The Project may seek to integrate and contribute back to other open source projects (“Upstream Projects”). In such cases, the Project will conform to all license requirements of the Upstream Projects, including dependencies, leveraged by the Project. Upstream Project code contributions not stored within the Project’s main code repository will comply with the contribution process and license terms for the applicable Upstream Project.

c. The TSC may approve the use of an alternative license or licenses for inbound or outbound contributions on an exception basis. To request an exception, please describe the contribution, the alternative open source license(s), and the justification for using an alternative open source license for the Project. License exceptions must be approved by a two-thirds vote of the entire TSC.

d. Contributed files should contain license information, such as SPDX short form identifiers, indicating the open source license or licenses pertaining to the file.

## 10. Amendments

a. This charter may be amended by a two-thirds vote of the entire TSC and is subject to approval by LF Charities, provided that any amendment that modifies, supplements or removes any Charitable Purpose requires the approval of the Charitable Committee.
