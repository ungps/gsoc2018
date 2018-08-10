Hello,

My name is Paul (you can call me Sebi) and I am one of the Google Summer of Code 2018 participants.

You can find me on `#git-devel` Freenode IRC channel and on [GitHub](https://github.com/ungps). There is a good chance you will find me on IRC, considering that XChat (the client I am using) starts up at boot.

My project for this summer is [Convert `git stash` to built-in](https://summerofcode.withgoogle.com/projects/#5431410714738688). The name of the title is pretty self-explanatory: at the end of the summer `git stash` is going to be 100% C (yay!). For a more thorough description of my project, please see [my proposal](https://docs.google.com/document/d/1TtdD7zgUsEOszHG5HX1at4zHMDsPmSBYWqydOPTTpV8).

So... the community bonding period has started... what have I been up to?

* Started discussing a plan with my mentor, Johannes Schindelin. We pretty much talked about existent work on this topic, what should I do next and a few administrative matters.

* Got in touch with Joel Teichroeb. In the past few months, he submitted some really [good patches](https://public-inbox.org/git/20180405022810.15796-2-joel@teichroeb.net/#t) towards making `git stash` a built-in. I am going to get those patches merged and continue my work on top of them.

* Read more carefully the documentation (by the way, [_Pro Git_](https://git-scm.com/book/) is a great read for anyone interested) and analyzed older `git stash` bugs. For example, there is a [bug](https://public-inbox.org/git/aa43f1ff-9095-fb4d-43bc-bf8283b7dabb@gmail.com/) for `git stash -p` which affects users when they try to split a chunk, containing edits to nearby lines. Hopefully, this will be fixed during the rewrite.

* Got more involved with the community on IRC and got the chance to congratulate Alban Gruin and Pratik Karki, the other GSoC students. They will be working on a similar project about `git rebase -i`.

Thanks!