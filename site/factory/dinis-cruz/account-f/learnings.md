# Learnings

- 26 Nov: a fresh container has no ssh-keygen; `apt-get update` then `apt-get install -y openssh-client` fixes it. `openssl ecparam` plus `ssh-keygen -p -N "" -m RFC4716` converts a P-256 PEM into a key git can sign with.
- 26 Nov: add_repo can be denied by the auto-mode classifier until the user allows it; say so and stop rather than work round it.
- 26 Nov: the website clone is large (18,000 files, about 5,000 commits); a depth-3000 fetch reaches the analyst's first commit (15 Nov).
- The old analyst left no status.json or debriefs; its state is the topics page and the 15 Nov proposals.
