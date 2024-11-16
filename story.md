# The Case of the Disappearing Commit

Detective Clara Jenkins was known in her precinct as "The Code Whisperer." Before joining the force, Clara had been a software developer, writing code for complex systems. Her unique blend of technical prowess and detective instincts made her the go-to investigator for any case with a technological edge.

One morning, Clara was called to the scene of a murder at a tech startup called CodeCove, a rising star in the AI world. The victim was Arthur Greaves, the company’s lead developer, found lifeless in the conference room. The death was clearly suspicious, and the evidence was sparse. A coffee cup smeared with fingerprints sat on the table, but it yielded no DNA matches. The only other clue? Arthur’s laptop, still open to a terminal window displaying Git logs.


## Clues in the Code

Clara examined the Git logs. The startup was developing a groundbreaking AI model, and Arthur had been the gatekeeper of the repository. A quick glance at the commit history revealed something odd: an unusual commit message from just hours before his death.

The message read:

`fix critical bug - rollback required`

This commit was out of character for Arthur. He was known for detailed, precise commit messages. Clara knew the clue lay in the code.

She cloned the repository onto her secure investigation server and used Git’s powerful tools to analyze its history. A `git diff` between the current branch and the previous commit showed that the “rollback” commit had reverted critical sections of the AI model, effectively sabotaging weeks of work.
