# Governance

This document describes how the Community for Bazel Technical Steering Committee (TSC) manages its
membership. It is the GOVERNANCE file that the [Technical Charter](CHARTER.md) refers to. Where this
document and the charter disagree, the charter governs.

## Members

The members of the TSC are listed in [MEMBERS.md](MEMBERS.md). Every member is a voting member. The
first members are the eight named in the charter as adopted on June 18, 2024.

Seats have no term. A seat ends only by resignation, inactivity, the employer cap, or removal, as
described below.

## Membership size

- The TSC has no maximum size.
- The TSC has at least four members.
- The TSC aims for an odd number of members. This is a preference, not a rule.

If the TSC falls below four members, the remaining members make seating new members their first
priority.

## Voting on membership

These rules apply to every vote this document calls for.

- A vote is held electronically or at a TSC meeting.
- An electronic vote is cast in the TSC's public Slack channel, `#community-for-bazel-tsc`. A vote
  on a private matter is cast in a private Slack channel of TSC members.
- An electronic vote stays open for two weeks. Unless this document says otherwise, it may close
  earlier once the outcome can no longer change.
- A vote at a meeting concludes at the meeting.
- A motion needs yes votes from the required share of all members at the time the vote opens.
  Fractions round up.
- A motion that has not reached its threshold when the vote closes fails.
- [MEMBERS.md](MEMBERS.md) is updated only after the vote has closed and the motion has passed. The
  update links to the vote or to its published result.

## Adding members

1. A TSC member asks the nominee privately whether they are willing to serve.
2. If the nominee agrees, the member posts the nomination to the TSC.
3. The TSC votes. The nomination passes with the approval of two-thirds of all current members.
4. After the vote passes, the nominator opens a pull request that adds the new member to
   [MEMBERS.md](MEMBERS.md). The new member is seated on the date the vote closes.

A nomination does not need a second. A member may nominate someone who works for the same employer.
A nominee whose seat would put the TSC over the employer cap cannot be seated.

## Employer cap

No more than one-third of the members may be employed by the same employer. Fractions round down,
but the cap is never less than one.

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

A member resigns by telling the TSC in writing. The resignation takes effect when the TSC receives
the message.

### Inactivity

A member is inactive when they have missed three TSC votes in a row. Abstaining counts as voting.

1. Any other member may open a pull request that removes an inactive member from
   [MEMBERS.md](MEMBERS.md). The pull request tags the inactive member.
2. The pull request stays open for two weeks.
3. If the inactive member replies in any way during that time, the pull request is closed, they keep
   their seat, and their count of missed votes starts over.
4. If they do not reply, a member other than the one who opened the pull request approves it and it
   is merged.

No vote is needed. A person removed this way may return through a new nomination.

## Removal

The TSC may remove a member with the approval of two-thirds of the other members. The member being
removed is not counted.

- Any member may open a removal motion.
- A removal motion names one member.
- Only one removal motion may be open at a time.
- The vote is held electronically. It stays open for two weeks and does not close early.
- The member is told when the motion opens and may respond before the vote closes.

> [!NOTE]
> These limits keep removals deliberate. They give the member time to respond, give every other
> member time to weigh in, and prevent several members from being removed in quick succession.

## Openness

The TSC conducts its business in public by default. That includes nominations and votes.

The TSC may discuss or vote on a specific matter in private. Any member may ask for this. The
outcome of every vote is published in the TSC's public Slack channel, wherever the vote took place.

## Changing this document

A change to this document passes with the approval of two-thirds of all current members, under the
voting rules above.
