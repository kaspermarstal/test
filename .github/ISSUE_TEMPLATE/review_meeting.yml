name: Review meeting
description: Minutes from review meeting.
title: Monthly review
labels: [
  "Review Meeting",
]
body:
  - type: input
    id: description
    attributes:
      label: "Call to order"
      description: "List participants"
      placeholder: "@user1, @user2"
    validations:
      required: true
  - type: textarea
    id: agenda-minutes
    attributes:
      label: "Agenda & Minutes"
      description: Go through the items below, create new issues as necessary, and tick the boxes along the way. Add minutes to below each point on the agenda.
      value: |
        - [ ] Adjust the statement of applicability according to any issues resolved since last meeting. For example, if a new policy was implemented, update status and add link to the policy.
        - [ ] Review issues not resolved since last meeting and find out how to help the new responsible persons if necessary. Describe outcomes below.
        - [ ] Review incident reports and add new risks to the risk log. Any risk with a score higher than 12 needs to be addressed with a [contingency_plan.yml](contingency_plan.yml) issue. 
        - [ ] Review the risk log and (optionally) open issues for risks that should be addressed before next meeting.
  - type: textarea
    id: any-other-business
    attributes:
      label: "Any other business"
      description: Short and explicit description of other business discussed at the meeting. Bullet lists are fine.
