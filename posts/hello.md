---
title: Testa blogg-grejen
description: this is a great description
date: 2023-11-30
tags: [test, blog, attempt1]
---

## test

Dessa bloggposter är var och en endast en markdownfil (github-markdown stöds), och laddas helt enkelt upp med

    scp fil.md prose.sh:/

Det finns stöd för metadata per post (anges i frontmatter), samt egen css (för hela siten).

En särskild fil `_footer.md` ger en global footer, och en annan särskild markdownfil `_readme.md` används för content och metadata för bloggens startsida (där länkar till alla posts också visas).

Man kan visa bloggen på en egen domän genom att registrera ett `CNAME-` och ett `TXT`-record, vilket jag gjort för denna site - annars nås den av default på https://&lt;användarnamn&gt;.prose.sh/
