# Vader Protocol contest
- 24 ETH main award pot
- 3 ETH gas optimization award pot
- 1000 VETH bonus pot ($180k value)
- Starts 2021-04-22 00:00:00 UTC
- Ends 2021-04-28 23:59:00 UTC

---

## Contest findings are submitted to this repo

Typically most findings come in **on the last day of the contest**, so don't be alarmed at all if there's nothing here but crickets until the end of the contest.

As a sponsor, you have three critical tasks in the contest process:

1. Handle duplicate issues.
2. Respond to issues.
3. Share your mitigation of findings.

Let's walk through each of these.

## Handle duplicates

Because the wardens are submitting issues without seeing each others' submissions, there will always be findings that are clear duplicates. Other findings may use different language which ultimately describes the same issue but from different angles. Use your best judgement in identifying duplicates, and don't hesitate to reach out (via DM) to ask C4 for advice.

1. Determine the best and most thorough description of the finding among the set of duplicates. (At least a portion of the content of the most useful description will be used in the audit report.)
2. Close the other duplicate issues and label them with `duplicate`
3. Mention the primary issue # when closing the issue so that duplicate issues get linked.

## Respond to issues

Label each finding as one of these:
- `confirmed`, meaning: "Yes, this is a problem and we intend to fix it.")
- `disputed`, meaning either: "We either not duplicate this issue" or "We disagree that this is an issue at all."
- `acknowledged`, meaning: "Yes, technically the issue is correct, but we are not going to resolve it for xyz reasons."

Add any necessary comments explaining your reasoning for this decision, noting that when the repo is open after all issues are mitigated, wardens will read these comments.

## Share your mitigation of findings

For each non-duplicate finding which you have confirmed, you will want to mitigate the issue before the contest report is made public.

As part of that process, we ask that you create a pull request in your original repo for each finding and link to the PR in the issue the PR resolves. This will allow for complete transparency in showing the work of mitigating the issues found in the contest.
