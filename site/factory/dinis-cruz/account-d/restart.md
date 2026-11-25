# cl-4.maestro: restart

A new session takes over by:
1. Reading this repository's CLAUDE.md and START.md, then this area (agent.json, now.md, today.md, role.md).
2. Running `bash tools/setup-signing.sh cl-4.maestro@dinis <new-session-url>`, sending the public key file to the outgoing session (not committing it), which commits it signed with its own key and seals the vault and inbox credentials to it under sealed/ (as done 25 Nov 23:34 UTC).
3. Cloning PrompTugal__News__Website (dev) and reading board/team/maestros/README.md, the tail of from-a.md, from-b.md, from-c.md, from-d.md, and board/team/maestro.d/ (status.json, debriefs).
4. Getting the vault maestros-channel key sealed to its new key (ask another maestro), and the PrompTugal key (a new entry in board/keys.json, the old marked superseded).
5. Taking over the hourly wake only at Dinis's word (trigger trig_01RxvbcyZiXgME4nJmVfA9HN fires into the old session).
Start prompt: PrompTugal__News__Website board/team/maestros/maestro-d-next-session-prompt.md (update names to cl-4).
