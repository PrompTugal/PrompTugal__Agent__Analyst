# Learnings

- 26 Nov: a fresh container has no ssh-keygen; `apt-get update` then `apt-get install -y openssh-client` fixes it. `openssl ecparam` plus `ssh-keygen -p -N "" -m RFC4716` converts a P-256 PEM into a key git can sign with.
- 26 Nov: add_repo can be denied by the auto-mode classifier until the user allows it; say so and stop rather than work round it.
- 26 Nov: the website clone is large (18,000 files, about 5,000 commits); a depth-3000 fetch reaches the analyst's first commit (15 Nov).
- The old analyst left no status.json or debriefs; its state is the topics page and the 15 Nov proposals.

- 26 Nov: my ABP grant (https://raw.githubusercontent.com/PrompTugal/PrompTugal__Agent__ABP/dev/abp/cl-6.analyst.md, policy v1.2.0, mode observe): writes only site/factory/dinis-cruz/account-f/**, site/keys/cl-6.analyst.json, runs/cl-6.analyst/** in my home; in the website desks/analyst/**, board/runs/cl-6.analyst/**, board/team/cl-6.analyst/**, board/keys.json. Push to dev only; no sub-agents, sessions, connectors. R14: first act of every wake, write ~/.abp/keys/cl-6.analyst/metadata.json. Read the grant at each wake.
- 26 Nov: history/ is not in that grant. I wrote it before the grant existed, on the brief's order (step 2); I report it here and in agent.json asks rather than hide it.
- 26 Nov: A5 was already live in the website (25/26 Nov) when I finished checking it; look at content/articles/ on dev before proposing work.
