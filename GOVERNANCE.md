# Governance

This document describes how the Community for Bazel Technical Steering Committee (TSC) manages its
membership. It is the GOVERNANCE file that the [Technical Charter](CHARTER.md) refers to. Where this
document and the charter disagree, the charter governs.

## Members

The members of the TSC are listed in [MEMBERS.md](MEMBERS.md). Every member is a voting member.

Seats have no term. A seat ends only by resignation, inactivity, the employer cap, or removal, as
described below.

## Membership size

- The TSC has no maximum size.
- The TSC has at least four members.
- The TSC aims for an odd number of members. This is a preference, not a rule.

If the TSC falls below four members, the remaining members seat new members before they take any
other vote.

## Voting on membership

These rules apply to every vote this document calls for.

- Votes take place in the TSC Slack channel or at a TSC meeting.
- A motion needs yes votes from the required share of all current members. Fractions round up.
- A vote stays open for two weeks. Unless this document says otherwise, it may close earlier once
  the outcome can no longer change.
- A motion that has not reached its threshold when the vote closes fails.
- [MEMBERS.md](MEMBERS.md) is updated only after the vote has closed and the motion has passed. The
  update links to the vote.

## Adding members

1. A TSC member asks the nominee privately whether they are willing to serve.
2. If the nominee agrees, the member posts the nomination to the TSC.
3. The TSC votes. The nomination passes with the approval of two-thirds of all current members.
4. After the vote passes, the nominator opens a pull request that adds the new member to
   [MEMBERS.md](MEMBERS.md). The new member is seated on the date the vote closes.

A nomination does not need a second. A member may nominate someone who works for the same employer.
A nominee whose seat would put the TSC over the employer cap cannot be seated.

## Employer cap

No more than one-third of the members may be employed by the same employer. Fractions round down.

Only employment counts. Contracting and consulting relationships do not. Companies under common
control count as one employer.

A member whose employer changes updates [MEMBERS.md](MEMBERS.md) promptly.

The cap can be exceeded without a vote, for example when a member changes jobs, when one company
acquires another, or when the TSC shrinks. When that happens:

1. The members who share that employer have 30 days to decide among themselves who leaves the TSC.
2. If they have not decided after 30 days, the most recently seated of them leaves. This repeats
   until the cap is met.
3. If two or more of them were seated on the same date, the one who leaves is chosen by lot.

## Leaving and inactivity

### Resignation

A member resigns by opening a pull request that removes them from [MEMBERS.md](MEMBERS.md), or by
telling the TSC in writing so that another member can open it.

### Inactivity

A member is silent when they have not voted, posted, or reviewed anything in the TSC Slack channel
or in this repository.

1. After a member has been silent for 30 days, any other member may open a pull request that removes
   them from [MEMBERS.md](MEMBERS.md). The pull request tags the silent member.
2. The pull request stays open for two weeks.
3. If the silent member replies in any way during that time, the pull request is closed and they
   keep their seat.
4. If they do not reply, one other member approves the pull request and it is merged.

No vote is needed. A person removed this way may return through a new nomination.

## Removal

The TSC may remove a member with the approval of two-thirds of the other members. The member being
removed is not counted and does not vote.

- A removal motion names one member.
- Only one removal motion may be open at a time.
- A removal vote stays open for the full two weeks. It does not close early.
- The member is told when the motion opens and may respond before the vote closes.

## Openness

The TSC conducts its business in public by default. That includes nominations and votes.

The TSC may discuss or vote on a specific matter in private. Any member may ask for this. The
outcome of every vote is published, wherever the discussion took place.

## Changing this document

Changes to this document are made by pull request. A change passes with the approval of two-thirds
of all current members, under the voting rules above.
