# Restart

1. Read this area, then history/PROVENANCE.md and the old desk README in history/desks/analyst-vicky/.
2. Clone the website beside this repository (attach with add_repo, push). Follow its CLAUDE.md.
3. Keys: signing key is session-only and private. If the session is new, make a new key (openssl P-256 and RSA-4096), publish a new site/keys file alone in its own commit, and set git signing (gpg.format ssh, gpg.ssh.program ssh-keygen, user.signingkey, commit.gpgsign true). `apt-get install -y openssh-client` first if ssh-keygen is missing.
4. Trailers on every commit: Agent: cl-6.analyst@PrompTugal.dinis and Claude-Session: <session URL>.
5. Update agent.json before stopping.
