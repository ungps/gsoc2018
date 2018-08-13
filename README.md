# Google Summer of Code 2018 with Git

## Proposal

You can check out my proposal [at this link](https://docs.google.com/document/d/1TtdD7zgUsEOszHG5HX1at4zHMDsPmSBYWqydOPTTpV8).

## Blogs posts:
 * [Week 1 (introduction)](https://ungps.github.io/2018/05/06/week-1-(introduction)/)
 * [Week 2](https://ungps.github.io/2018/05/13/week-2/)
 * [Week 3](https://ungps.github.io/2018/05/20/week-3/)
 * [Week 4](https://ungps.github.io/2018/05/27/week-4/)
 * [Week 5](https://ungps.github.io/2018/06/03/week-5/)
 * [Week 6](https://ungps.github.io/2018/06/10/week-6/)
 * [Week 7](https://ungps.github.io/2018/06/17/week-7/)
 * [Week 8](https://ungps.github.io/2018/06/24/week-8/)
 * [Week 9](https://ungps.github.io/2018/07/01/week-9/)
 * [Week 10](https://ungps.github.io/2018/07/08/week-10/)
 * [Week 10 (update)](https://ungps.github.io/2018/07/13/week-10-(update)/)
 * [Week 11](https://ungps.github.io/2018/07/15/week-11/)
 * [Week 12](https://ungps.github.io/2018/07/22/week-12/)
 * [Week 13](https://ungps.github.io/2018/07/29/week-13/)
 * [Week 14](https://ungps.github.io/2018/08/05/week-14/)

Additional:

 * [About GSoC (halfway blogpost)](https://ungps.github.io/2018/07/16/About-GSoC/)

## Patches

### `git stash`

This is what I have been working on during this summer. It is a series consisting of 26 patches. At the moment, they are on the mailing list, waiting to get reviewed. A part of them were already reviewed (up to and including "stash: convert store to builtin").

 * [Github pull request](https://github.com/git/git/pull/495)

#### V7:
 * [Github tag](https://github.com/ungps/git/releases/tag/git-stash-v7)
 * [Mailing list](https://public-inbox.org/git/cover.1533753605.git.ungureanupaulsebastian@gmail.com/)

Link to every patch (mailing list)

 * [01/26: sha1-name.c: added 'get_oidf', which acts like 'get_oid'](https://public-inbox.org/git/03006713a841adf68340f0dcf39ee17c99060eeb.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [02/26: stash: improve option parsing test coverage](https://public-inbox.org/git/57c8f7ebbd3cf5631bbec51c0cae9cb9978ae2c0.1533753605.git.ungureanupaulsebastian@gmail.com/) *
 * [03/26: stash: update test cases conform to coding guidelines](https://public-inbox.org/git/b37da07c02064bb2f427196234710021b0c49184.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [04/26: stash: renamed test cases to be more descriptive](https://public-inbox.org/git/cb70dc2317b8bdbe640a50de7050cb405067c0f0.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [05/26: stash: convert apply to builtin](https://public-inbox.org/git/7ba9a8515d445d10af36a8a79071af51b90f5aef.1533753605.git.ungureanupaulsebastian@gmail.com/) *
 * [06/26: stash: convert drop and clear](https://public-inbox.org/git/6831636969a588833f42530fda29602447085848.1533753605.git.ungureanupaulsebastian@gmail.com/) *
 * [07/26: stash: convert branch](https://public-inbox.org/git/ee70cc83b9b57c43672cfa5065d3c6156d089d92.1533753605.git.ungureanupaulsebastian@gmail.com/) *
 * [08/26: stash: convert pop](https://public-inbox.org/git/0996e18f410508602525c71e49a0d6614169b77e.1533753605.git.ungureanupaulsebastian@gmail.com/) *
 * [09/26: stash: implement the "list" command in the builtin](https://public-inbox.org/git/47556d40a9944e8cc45ba3df8e12c80a1898b160.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [10/26: stash: convert show to builtin](https://public-inbox.org/git/05246e813c810156c07385052ec59d6dec34623e.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [11/26: stash: change `git stash show` usage text and documentation](https://public-inbox.org/git/5e477e5a62c3e2cc7066487bf6e0a68c922457a5.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [12/26: stash: refactor `show_stash()` to use the diff API](https://public-inbox.org/git/35e6fdfab85c21f0554da061cfab3f643d1aa794.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [13/26: stash: update `git stash show` documentation](https://public-inbox.org/git/46b04e256f045a53111d52439de376a5f332cb55.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [14/26: stash: convert store to builtin](https://public-inbox.org/git/84b0086287c683d33bd456957700199b22fd1c49.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [15/26: stash: convert create](https://public-inbox.org/git/0393bbd09daeb7ab67da4a343ba58d824c35532b.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [16/26: stash: replace spawning a "read-tree" process](https://public-inbox.org/git/0683dfe7cf0528c0288b57914e7626b5c7108909.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [17/26: stash: avoid spawning a "diff-index" process](https://public-inbox.org/git/ec5b2c9ac9e0e58710bdc385e03a01e2a7fd10bd.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [18/26: stash: convert push to builtin](https://public-inbox.org/git/b41bff3b5188ac014f9cb5024e535d6804ef1834.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [19/26: stash: make push to be quiet](https://public-inbox.org/git/c778a6aa99edd1ab58cfebc0976f1475f759611c.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [20/26: stash: add tests for `git stash push -q`](https://public-inbox.org/git/5ec3429340f43caad79e4213a7994738cb5d33c7.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [21/26: stash: replace spawning `git ls-files` child process](https://public-inbox.org/git/3286e8443ed1c8f9560aa6bef01aa18ed78266df.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [22/26: stash: convert save to builtin](https://public-inbox.org/git/d39aca1880ccf94f9f207cd09b4a5cc2c3c233e7.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [23/26: stash: convert `stash--helper.c` into `stash.c`](https://public-inbox.org/git/c659174b1be950072580ee176d59f85574cdb96c.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [24/26: stash: optimize `get_untracked_files()` and `check_changes()`](https://public-inbox.org/git/9bde85eacb94db54763aab35efe287c5af7c8316.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [25/26: stash: replace all `write-tree` child processes with API calls](https://public-inbox.org/git/3b4a3b766598589df30e16cddf175f039eb4e290.1533753605.git.ungureanupaulsebastian@gmail.com/)
 * [26/26: stash: replace all "git apply"](https://public-inbox.org/git/56500d98f9d5daaa5f21a43767885baede86e3a0.1533753605.git.ungureanupaulsebastian@gmail.com/)

*<sub>\* The project was originally started by Joel Teichroeb. During the bonding period, he [agreed](https://public-inbox.org/git/CA+CzEk_qwHs5qUstyFeepzwvCBR=9SvH90+__f-gfxFySETZzQ@mail.gmail.com/) to give me custody of his patches (the ones marked with \*). I independently modified the original patches and developed new ones.</sub>*

Status: *waiting to get reviewed*

#### V6:

[GitHub tag](https://github.com/ungps/git/releases/tag/git-stash-v6)

Link to every patch (mailing list):

 First series of patches:

 * [1/4: sha1-name.c: added 'get_oidf', which acts like 'get_oid'](https://public-inbox.org/git/4c1f71b067ac235c3003d58e1f3dfb07866be129.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [2/4: stash: improve option parsing test coverage](https://public-inbox.org/git/16a4ed177d885ab0db270201ba52f07ed2234ea1.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [3/4: stash: update test cases conform to coding guidelines](https://public-inbox.org/git/2fe77c0946231dd9235d88922e4d56dd7f5c66c7.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [4/4: stash: renamed test cases to be more descriptive](https://public-inbox.org/git/0f49fc90bee5e6a297c49224f1451a7aee4c8635.1529943789.git.ungureanupaulsebastian@gmail.com/)

Second series of patches:

 * [1/4: stash: convert apply to builtin](https://public-inbox.org/git/45df77241155792bef2ce44c29f1fca09d8fa485.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [2/4: stash: convert drop and clear](https://public-inbox.org/git/5373f422a82da2357828b8cc4a2b84fb2bedd780.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [3/4: stash: convert branch](https://public-inbox.org/git/ac0a24da8a583a137176d1d215df65bb1a3ada0e.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [4/4: stash: convert pop](https://public-inbox.org/git/5d5b05caecc01d8f252ef5f8495549663815ed63.1529943789.git.ungureanupaulsebastian@gmail.com/)

Third series of patches:

 * [1/6: stash: implement the "list" command in the builtin](https://public-inbox.org/git/a4b25124d0d3f28c5d122f8226a50978e39c9200.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [2/6: stash: convert show to builtin](https://public-inbox.org/git/b5c8ad3ae96a1464cf024cabc219d0191709715a.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [3/6: stash: change `git stash show` usage text and documentation](https://public-inbox.org/git/8d428b70338821bddd5c3210cf49cc84753685f0.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [4/6: stash: refactor `show_stash()` to use the diff API](https://public-inbox.org/git/a3b02c25de08579df65ecb1de62a7b8f0434077e.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [5/6: stash: update `git stash show` documentation](https://public-inbox.org/git/dcd10e941418cbf4bbc50719f1f567f4025fe123.1529943789.git.ungureanupaulsebastian@gmail.com/)
 * [6/6: stash: convert store to builtin](https://public-inbox.org/git/a75e7208e62b9008524dbb993d692fb8d9604cbe.1529943789.git.ungureanupaulsebastian@gmail.com/)

### `GET_OID_GENTLY`

When I started working on `git stash`, I did not forsee that `get_oid()` might die in case there is an empty reflog. The purpose of this patch is to replace spawning `git rev-parse --verify --quiet`.

[GitHub pull request](https://github.com/git/git/pull/504)

[GitHub tag](https://github.com/ungps/git/releases/tag/get_oid_gently_v1)

[Mailing list](https://public-inbox.org/git/cover.1531778417.git.ungureanupaulsebastian@gmail.com/)

Link to every patch (mailing list)

 * [1/6: sha1-name: Add `GET_OID_GENTLY` flag](https://public-inbox.org/git/973c4d380743b4a0491ec63909fef862413db065.1531778417.git.ungureanupaulsebastian@gmail.com/)
 * [2/6: tree-walk: Add three new gentle helpers](https://public-inbox.org/git/b1f385105f790cafc65c26699282919a2735d4bd.1531778417.git.ungureanupaulsebastian@gmail.com/)
 * [3/6: refs.c: Teach `read_ref_at()` to accept `GET_OID_GENTLY` flag](https://public-inbox.org/git/c62fecd41db87b22d3605029685eb0281d67fc96.1531778417.git.ungureanupaulsebastian@gmail.com/)
 * [4/6: sha1-name: Teach `get_oid_basic()` to be gentle](https://public-inbox.org/git/d91384ff0e23cd845bcfdf170c8a162ec5551f6b.1531778417.git.ungureanupaulsebastian@gmail.com/)
 * [5/6: sha1-name: Teach `get_oid_with_context[_1]()`](https://public-inbox.org/git/dc1abfca46cd536f060b9097b9f2d1a64988f932.1531778417.git.ungureanupaulsebastian@gmail.com/)
 * [6/6: sha1-name: Add gentle alternative for `get_oid()`](https://public-inbox.org/git/046f5f7a3495acbbb53ee2b7007d5c058f18cc0b.1531778417.git.ungureanupaulsebastian@gmail.com/)

Status: *not merged*


## TODO:

 * One thing which was not included in the schedule, but might be a welcomed feature, is to introduce a new subcommand: `git stash commit` which would act like `git stash pop` and `git commit`.

 * Add the possibility to see untracked files in a stash. There has been a discussion about this on the [mailing list](https://public-inbox.org/git/1505626069.9625.6.camel@gmail.com/).

 * Running `git stash show -p` and trying to split a hunk does not work properly in all the cases. There has been a discussion about this on the [mailing list](https://public-inbox.org/git/aa43f1ff-9095-fb4d-43bc-bf8283b7dabb@gmail.com/)

Initial file:

```
 Text1.
 Text2.
 Text3.
 Text4.
 Text5.
```

Case 1:

```
 Text1.foo
 Text2.
 Text3.
 Text4.bar
 Text5.
```

Case 2:

```
 Text1.foo
 Text2.
 Text3.
 Text4.
 Text5.bar
```

Running `git stash push -p`, splitting the hunk, accepting one and refusing the other one:

 * in the first case an error messaged is falsely (to some degree) displayed. The stash was created, but the changes were not removed from the index.

 * in the second case everything works fine.

So, the problem occurs only when there are 2 or less lines between the edited lines.

## Results

Running time on:

### Linux (Ubuntu 17.10)

 * git test suite (t3903-stash.sh, t3904-stash-patch.sh,
t3905-stash-include-untracked.sh and t3906-stash-submodule.sh)
```
        t3903-stash.sh:
        ** SHELL: 12,69s user 9,95s system 109% cpu 20,730 total
        **     C:  2,67s user 2,84s system 105% cpu  5,206 total

        t3904-stash-patch.sh:
        ** SHELL: 1,43s user 0,94s system 106% cpu 2,242 total
        **     C: 1,01s user 0,58s system 104% cpu 1,530 total

        t3905-stash-include-untracked.sh
        ** SHELL: 2,22s user 1,73s system 110% cpu 3,569 total
        **     C: 0,59s user 0,57s system 106% cpu 1,085 total

        t3906-stash-submodule.sh
        ** SHELL: 2,89s user 2,99s system 106% cpu 5,527 total
        **     C: 2,21s user 2,61s system 105% cpu 4,568 total

        TOTAL:
        ** SHELL: 19.23s user 15.61s system
        **     C:  6.48s user  6.60s system
```
 * a git repository with 4000 files: 1000 not changed,
1000 staged files, 1000 unstaged files, 1000 untracked.
In this case I ran some of the most used commands:

        git stash push:

        ** SHELL: 0,12s user 0,21s system 101% cpu 0,329 total
        **     C: 0,06s user 0,13s system 105% cpu 0,185 total

        git stash push -u:

        ** SHELL: 0,18s user 0,27s system  108% cpu 0,401 total
        **     C: 0,09s user 0,19s system  103% cpu 0,267 total

        git stash pop:

        ** SHELL: 0,16s user 0,26s system 103% cpu 0,399 total
        **     C: 0,13s user 0,19s system 102% cpu 0,308 total


### Windows 8.1:

 * git test suite (t3903-stash.sh, t3904-stash-patch.sh,
t3905-stash-include-untracked.sh and t3906-stash-submodule.sh)

```
        TOTAL:
        ** SHELL: 17m20.407s
        **    C:   5m 6.967s

        =================================

        t3903-stash.sh:
        ** SHELL:
        real    11m28.043s
        user    0m11.042s
        sys     0m24.278s

        ** C:
        real    1m56.922s
        user    0m11.725s
        sys     0m25.462s

        ================================

        t3904-stash-patch.sh:
        ** SHELL:
        real    0m35.436s
        user    0m1.117s
        sys     0m2.669s

        ** C:
        real    0m32.015s
        user    0m2.346s
        sys     0m5.151s

        ================================

        t3905-stash-include-untracked.sh
        ** SHELL:
        real    2m11.608s
        user    0m2.482s
        sys     0m4.737s

        ** C:
        real    0m24.749s
        user    0m2.171s
        sys     0m5.060s

        =================================

        t3906-stash-submodule.sh
        ** SHELL:
        real    3m5.032s
        user    0m7.563s
        sys     0m21.697s

        ** C:
        real    2m13.281s
        user    0m8.644s
        sys     0m20.799s
```
