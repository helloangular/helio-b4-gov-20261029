# helio-b4-gov-20261029

Owned fixture repository of QA-guide worker B4 (227-case qualification, 29 Oct 2026): close/override/lock,
approval-policy and administration cases. One Helio-dispatched provider-managed workflow `b4-provider.yml`
(environments `b4-gov-test`, `b4-gov-production`; the B4 lane's Helio reviewer is the only required reviewer,
admin bypass off) and a push-only `b4-probe.yml` for the connection readiness probe.
Nothing is deployed; the production job records synthetic evidence. Every commit is pushed with its
`helio/workflow/<sha>` tag.
