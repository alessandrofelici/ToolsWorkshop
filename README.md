# Developer Tools & Git Features

### Developer

- [free-for.dev](https://free-for.dev)
- [it-tools.tech](https://it-tools.tech)
- [devtoollab.com/tools](https://devtoollab.com/tools)
- [Gemini for Students](https://gemini.google/students)
- [Google Antigravity](https://antigravity.google)

### Design

- [glyphs.fyi](https://glyphs.fyi)
- [coolors.co](https://coolors.co)
- [storyset.com](https://storyset.com)
- [magicpattern.design/tools](https://magicpattern.design/tools)
- [checklist.design](https://checklist.design)
- [colourcontrast.cc](https://colourcontrast.cc)
- [realtimecolors.com](https://realtimecolors.com)
- [Google Stitch](https://stitch.withgoogle.com)

### Other

- [learn-anything.xyz](https://learn-anything.xyz)
- [Free Programming Books](https://ebookfoundation.github.io/free-programming-books)
- [open-resume.com/resume-parser](https://open-resume.com/resume-parser)
- [Jake's Resume (Overleaf)](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs)
- [dropsha.re](https://dropsha.re)
- [tinywow.com](https://tinywow.com)
- [Wispr Flow](https://wisprflow.ai)
- [Lord Mango's Website Wiki](https://eggplant-waterlily-64e.notion.site/Lord-Mango-s-Website-Wiki-caab230982c54262b3cdbcb152488636)

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
