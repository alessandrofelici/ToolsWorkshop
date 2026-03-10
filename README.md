# Developer Tools & Git Features

### Developer

- [free-for.dev](https://free-for.dev)
- [Lord Mango's Website Wiki](https://eggplant-waterlily-64e.notion.site)
- [it-tools.tech](https://it-tools.tech)
- [devtoollab.com/tools](https://devtoollab.com/tools)

### Design

- [glyphs.fyi](https://glyphs.fyi)
- [coolors.co](https://coolors.co)
- [storyset.com](https://storyset.com)
- [magicpattern.design/tools](https://magicpattern.design/tools)
- [checklist.design](https://checklist.design)
- [colourcontrast.cc](https://colourcontrast.cc)
- [realtimecolors.com](https://realtimecolors.com)

### Other

- [learn-anything.xyz](https://learn-anything.xyz)
- [Free Programming Books](https://ebookfoundation.github.io/free-programming-books)
- [open-resume.com/resume-parser](https://open-resume.com/resume-parser)
- [dropsha.re](https://dropsha.re)

### Git Reference

**Branching**

```
git branch <name>          create branch
git checkout -b <name>     create + switch
git merge <branch>         merge into current
git branch -d <name>       delete branch
git branch -a              list all (local + remote)
```

**Reflog**

```
git reflog                 show all HEAD movements
git checkout <hash>        jump to a "lost" commit
git reset --hard <hash>    restore to a previous state
```

- entries expire after 90 days by default
- saves you after bad rebase, reset, or branch delete

**Blame**

```
git blame <file>           who changed each line + when
git blame -w <file>        ignore whitespace changes
git blame -C <file>        detect moved/copied lines (same commit)
git blame -C -C <file>     also search file creation commit
git blame -C -C -C <file>  search entire repo history (slow)
git blame -w -C <file>     combined
```
