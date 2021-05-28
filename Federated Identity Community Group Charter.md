
\[DRAFT\] Federated Identity Community Group Charter
=========================================================================

This Charter is work in progress. To submit feedback,
please use [the GitHub Repository](https://github.com/hlflanagan/fedidcg) issues where the charter is being developed.

-   This Charter: <span class="remove">{TBD: URI}</span>
-   Previous Charter: n/a
-   Start Date: June 2021 (est.)


Goals
-----

The purpose of the Federated Identity Community Group is to provide a forum focused on incubating web features that will both support federated identity and prevent untransparent, uncontrollable tracking of users across the web.


Scope of Work
-------------

Federated login and tracking tools use the same primitives and are indistinguishable from non-transparent, uncontrollable tracking from the browser’s perspective. Current proposed mitigations for tracking will impact federated identity. This group will discuss potential architectures, APIs, and possible changes that could be proposed to external protocols such as OAuth2.0, OIDC, and SAML. 

{TBD: Describe topics that are in scope. For specifications that the CLA
patent section applies to, it is helpful to describe the scope in a way
that it is clear what types of technologies will be defined in
specifications, as opposed to adoption by reference or underlying
technology not defined in the proposed spec. Key use cases are often
helpful in describing scope. If no specifications will be defined in the
group that the CLA patent section applies to, the charter should clearly
state that. A clear scope is particularly important where patent
licensing obligations may apply.}

### Out of Scope

The identity space is much larger than federation. While there are several topics related to identity that may be of interest, they are out of scope for this specific group. If a general Identity Community Group is formed, the Federated Identity Community Group should become a sub-group within that larger effort.

Specific topics out of scope:

* Decentralized identifiers
* Ad-tech tools or APIs

Deliverables
------------

### Proposals 

A Proposal is an idea brought to the Community Group for consideration and potential adoption as a Work Item.

Each Proposal has one or more Champions, beginning with the Community Group Participant who proposed it. Champions are self-organized. Proposals should explicitly list their Champions, and Champions should keep this list updated as the set of Champions for the Proposal changes.

Any Community Group Participant may make a Proposal by filing an issue in the privacycg/proposals repository on GitHub, stating the problem they would like to address and how they propose to address it.

The Community Group may discuss the Proposal on GitHub and during teleconferences or face-to-face meetings.

Champions are responsible for the technical content of their Proposal. They are expected to solicit input from Community Group Participants, and they may consider and respond to comments, suggestions, and objections on their Proposal from Participants and the public.

Champions may ask the Chairs to create a dedicated repository for their Proposal. The Chairs will generally honor such requests, though they may choose not to (if, for example, they believe the Proposal to be out of scope).

Proposals begin as or evolve into explainers which describe a user-facing problem which needs to be solved and how the authors propose to solve it. Explainers are Community Group Reports as defined in the Community and Business Group Process, but they are not Specifications as defined in that document.

Proposals may be withdrawn by their Champions, or may be closed by the Chairs (if, for example, the Chairs deem the Proposal to be out of scope, or if its number of Champions drops to zero). If such a Proposal has a dedicated repository, the Chairs and Champions should take steps to ensure the data is not lost, perhaps by archiving the repository or by transferring it to a different organization or user. 

### Work Items
This Community Group may produce Work Items—a special kind of Community Group Report whose purpose is to enable interoperability between independent implementations of the features it defines. Work Items are Specifications as defined in the Community and Business Group Process. Each Work Item has one or more Editors, who are appointed by the Chairs.

The current set of Work Items of the Community Group are:

| Name |	Editors |	Expected Destinations |
| ---- | -------- | ----------------------|
|      |          |                       |


This list will be kept updated by the Chairs to reflect the current set of Work Items of the Community Group.

The Community Group may adopt a Proposal as a Work Item if it is the consensus of its Champions and the Chairs that such a Work Item would be likely to enable and lead to independent, interoperable implementations. The Chairs and Champions may solicit commitments from organizations to provide adequate implementation experience of the Proposal's features, and may take such commitments or other such expressions of implementer interest into account when making their decision.

Each Work Item should be accompanied by an explainer describing its proposed changes to the web platform. Editors should keep the Work Item's explainer up-to-date with the Work Item as it evolves.

Because Work Items begin life as Proposals, they typically start out with an explainer already written, and Proposal Champions are typically appointed Editors.

When a Work Item's Editors deem the Work Item ready for migration, they will notify the Chairs. The CG may produce a Final Community Group Report at this time. The Editors and Chairs will identify the best destination standards body or bodies, and will then work with those bodies to successfully migrate the Work Item.

When migrated to the standards track, Work Items might become standalone specifications, they might be integrated into one or more existing specifications, or they might result in a combination of these options.

The Chairs may remove Work Items. The Chairs must notify the group of the removal of Work Items, and this notice must include rationale. Some possible reasons for removing a Work Item are:

* because the Work Item has been migrated elsewhere
* because it is no longer the consensus of its Champions and the Chairs that the Work Item is likely to enable and lead to independent, interoperable implementations.
* because the Work Item no longer has an Editor and a replacement cannot be found 

The Chairs should take steps to ensure the repositories of removed Work Items are not lost, perhaps by archiving the repository or by transferring it to a different organization or user. 

Coordination
------------------------

This group will collaborate with appropriate groups at W3C, OIDF, IETF, and elsewhere, and will migrate Work Items to them when they’re ready for the standards track. Groups most likely to be close partners are listed below, but this group is expected to coordinate with other groups as relevant.

# W3C Groups 

* [Privacy Community Group](https://www.w3.org/community/privacycg/)

* [Web Application Security Working Group (WebAppSec)](https://www.w3.org/2011/webappsec/)
  * WebAppSec is expected to be a destination for transitioning Work Items to the standards track. 
    
* [Web Platform Incubator Community Group (WICG)](https://www.w3.org/community/wicg/)


Community and Business Group Process
------------------------------------

The group operates under the [Community and Business Group
Process](https://www.w3.org/community/about/agreements/). Terms in this
Charter that conflict with those of the Community and Business Group
Process are void.

As with other Community Groups, W3C seeks organizational licensing
commitments under the [W3C Community Contributor License Agreement
(CLA)](http://www.w3.org/community/about/agreements/cla/). When people
request to participate without representing their organization's legal
interests, W3C will in general approve those requests for this group
with the following understanding: W3C will seek and expect an
organizational commitment under the CLA starting with the individual's
first request to make a contribution to a group
[Deliverable](#deliverables). The section on [Contribution
Mechanics](#contrib) describes how W3C expects to monitor these
contribution requests.

The [W3C Code of Ethics and Professional
Conduct](https://www.w3.org/Consortium/cepc/) applies to participation
in this group.

Work Limited to Charter Scope
-----------------------------

The group will not publish Specifications on topics other than those
listed under [Specifications](#specifications) above. See below for [how
to modify the charter](#charter-change).

Contribution Mechanics
----------------------

Substantive Contributions to Specifications can only be made by
Community Group Participants who have agreed to the [W3C Community
Contributor License Agreement
(CLA)](http://www.w3.org/community/about/agreements/cla/).

Specifications created in the Community Group must use the [W3C Software
and Document
License](http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document).
All other documents produced by the group should use that License where
possible.

{TBD: if CG doesn't use GitHub replace the remaining paragraphs in this
section with: "All Contributions are made on the groups public mail list
or public contrib list"}

Community Group participants agree to make all contributions in the
GitHub repo the group is using for the particular document. This may be
in the form of a pull request (preferred), by raising an issue, or by
adding a comment to an existing issue.

All Github repositories attached to the Community Group must contain a
copy of the
[CONTRIBUTING](https://github.com/w3c/licenses/blob/master/CG-CONTRIBUTING.md)
and [LICENSE](https://github.com/w3c/licenses/blob/master/CG-LICENSE.md)
files.

Transparency
------------

The group will conduct all of its technical work in public. If the group
uses GitHub, all technical work will occur in its GitHub repositories
(and not in mailing list discussions). This is to ensure contributions
can be tracked through a software tool.

Meetings may be restricted to Community Group participants, but a public
summary or minutes must be posted to the group's public mailing list, or
to a GitHub issue if the group uses GitHub.

Decision Process
----------------

This group will seek to make decisions where there is consensus. Groups
are free to decide how to make decisions (e.g. Participants who have
earned Committer status for a history of useful contributions assess
consensus, or the Chair assesses consensus, or where consensus isn't
clear there is a Call for Consensus \[CfC\] to allow multi-day online
feedback for a proposed course of action). It is expected that
participants can earn Committer status through a history of valuable
contributions as is common in open source projects. After discussion and
due consideration of different opinions, a decision should be publicly
recorded (where GitHub is used as the resolution of an Issue).

If substantial disagreement remains (e.g. the group is divided) and the
group needs to decide an Issue in order to continue to make progress,
the Committers will choose an alternative that had substantial support
(with a vote of Committers if necessary). Individuals who disagree with
the choice are strongly encouraged to take ownership of their objection
by taking ownership of an alternative fork. This is explicitly allowed
(and preferred to blocking progress) with a goal of letting
implementation experience inform which spec is ultimately chosen by the
group to move ahead with.

Any decisions reached at any meeting are tentative and should be
recorded in a GitHub Issue for groups that use GitHub and otherwise on
the group's public mail list. Any group participant may object to a
decision reached at an online or in-person meeting within 7 days of
publication of the decision provided that they include clear technical
reasons for their objection. The Chairs will facilitate discussion to
try to resolve the objection according to the [decision
process](#decision).

It is the Chairs' responsibility to ensure that the decision process is
fair, respects the consensus of the CG, and does not unreasonably favour
or discriminate against any group participant or their employer.

Chair Selection
---------------

Participants in this group choose their Chair(s) and can replace their
Chair(s) at any time using whatever means they prefer. However, if 5
participants, no two from the same organisation, call for an election,
the group must use the following process to replace any current Chair(s)
with a new Chair, consulting the Community Development Lead on election
operations (e.g., voting infrastructure and using [RFC
2777](https://tools.ietf.org/html/rfc2777)).

1.  Participants announce their candidacies. Participants have 14 days
    to announce their candidacies, but this period ends as soon as all
    participants have announced their intentions. If there is only one
    candidate, that person becomes the Chair. If there are two or more
    candidates, there is a vote. Otherwise, nothing changes.
2.  Participants vote. Participants have 21 days to vote for a single
    candidate, but this period ends as soon as all participants have
    voted. The individual who receives the most votes, no two from the
    same organisation, is elected chair. In case of a tie, RFC2777 is
    used to break the tie. An elected Chair may appoint co-Chairs.

Participants dissatisfied with the outcome of an election may ask the
Community Development Lead to intervene. The Community Development Lead,
after evaluating the election, may take any action including no action.

Amendments to this Charter
--------------------------

The group can decide to work on a proposed amended charter, editing the
text using the [Decision Process](#decision) described above. The
decision on whether to adopt the amended charter is made by conducting a
30-day vote on the proposed new charter. The new charter, if approved,
takes effect on either the proposed date in the charter itself, or 7
days after the result of the election is announced, whichever is later.
A new charter must receive 2/3 of the votes cast in the approval vote to
pass. The group may make simple corrections to the charter such as
deliverable dates by the simpler group decision process rather than this
charter amendment process. The group will use the amendment process for
any substantive changes to the goals, scope, deliverables, decision
process or rules for amending the charter.
