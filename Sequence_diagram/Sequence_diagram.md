# This is example for sequence diagram
```mermaid
sequenceDiagram
    participant User
    participant AdminTeam
    participant HR
    participant CEO
    participant MarketingTeam

    User ->> AdminTeam: Submit Onboarding Request
    AdminTeam ->> HR: Notify Onboarding
    HR ->> AdminTeam: Provide Onboarding Details
    AdminTeam ->> CEO: Notify Onboarding
    CEO ->> HR: Review Onboarding Plan
    HR ->> CEO: Provide Plan Details
    CEO ->> AdminTeam: Approve Onboarding
    AdminTeam ->> HR: Confirm Approval
    HR ->> AdminTeam: Proceed with Onboarding
    AdminTeam ->> MarketingTeam: Notify Onboarding
    MarketingTeam ->> User: Welcome Email
    HR ->> User: Provide Company Policies
    AdminTeam ->> User: Provide Equipment
    MarketingTeam ->> User: Introduce Company Culture 