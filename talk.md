build-lists: true
footer: Bernd Haug – :envelope: [haug@berndhaug.net](mailto:haug@berndhaug.net)
slidenumbers: true

[.footer: ]
[.slidenumbers: false]

![inline](title.jpg)

[https://github.com/dilbernd/idea-productivity](https://github.com/dilbernd/idea-productivity)
Bernd Haug – :envelope: [haug@berndhaug.net](mailto:haug@berndhaug.net) – :bird: [@itbeha](https://www.twitter.com/itbeha)

---

# I. Some Settings

---

# Settings – Multi-Caret

![inline](kbd-multicaret.png)

Cursor placement (Keyboard):

| :apple:          | ⌥,⌥(hold)+⬆︎/⬇ |
|------------------|--------------------|
| :penguin:/:door: | Ctrl, Ctrl (hold) + ⬆︎/⬇︎ |

---

# Settings – Multi-Caret (cont'd)

|||
|---|---|
| Cursor placement (Mouse) | ⌥⇧(click) |
| Remove all but first-placed | ⎋ |

(All Platforms)

---

# Settings – Humps!

![inline](mouse-humps.png)
![inline](keyboard-humps.png)

---

# Settings – Surround Selection

Surround selection when typing anything quoty or parenish.

![inline](surround-parenish.png)

Affects whatever has surrounding-nature in the current language, e.g.

```
([{`'"<
```

---

# Keystrokes – Expand/Shrink Selection

- Navigation! – “Pareditish”
- Goes well with surround quotes/parens!

| Action | :apple: | :penguin:/:door: |
|---|:---:|:---:|
| Expand selection | ⌥⬆︎ | Ctrl + W |
| Shrink selection | ⌥⬇︎| Ctrl + Shift + W |

---

# II. Nice View

---

# Settings – No Tabs

![inline](./untabify.png)

---

# Tab Replacement

| Action | :apple: | :penguin:/:door: |
|---|:---:|:---:|
| Recent Files | ⌘E | Ctrl + E |
| Recently Edited Files | ⌘⇧E | Ctrl + Shift + E |

---

# View dropdown – No Deadweight

![inline](./view_menu.png)

- No Toolbar
- No Tool Buttons
- No Navbar
- Hadi Hariri says: hide the Status Bar – not for me!

---

# Get the tool buttons back temporarily

| :apple: | ⌘, ⌘ (hold) |
|---|---|
| :penguin:/:door: | Alt, Alt (hold) |

---

# Clean view – Manage Tool Windows Without Mouse

| Action | :apple: | :penguin:/:door: |
|---|:---:|:---:|
| back to editor | ⎋ | ⎋ |
| Hide current/last tool | ⇧⎋ | Shift + ⎋ |
| In editor, back to last tool | [F12] | [F12] |
| Hide/unhide all tools | ⌘⇧[F12] | Ctrl + Shift + [F12] |

---

# Clean view – Open on Demand – Keystrokes

| :apple: | ⌘[number] |
|---|---|
| :penguin:/:door: | Alt + [number] |

- Just learn the main tools’ numbers by heart!
- Criminally Underused: Bookmarks/Breakpoints (**2**), TODOs (**6**),
  Structure (**7**), Type Hierarchy (**8**)
- If you only use Project/Debug/VCS, *you’re cheating yourself!*

---
[.build-lists: false]

# Project Tool (#1) Alternative

![inline](navbar.png)

- Contextual navigation; super useful!
- Lots of further actions available directly

| :apple: | ⌘⬆︎|
|---|---|
| :penguin:/:door: | Alt + [Home] |

---

# III. Finding

---

# Navigate Content & IDE

| Search… | :apple: | :penguin:/:door: |
|---|:---:|:---:|
| Classes! | ⌘O | Ctrl + N |
| Files! | ⌘⇧O | Ctrl + Shift + N |
| Symbols! (methods…) | ⌘⌥O | Ctrl + Alt + Shift + N |
| Actions! | ⌘⇧A | Ctrl + Shift + A |
| **_Absolutely Everywhere!!!_** | ⇧, ⇧ | Shift, Shift |

---

# Navigate declarations & definitions

| Go to… | :apple: | :penguin:/:door: |
|---|:---:|:---:|
| _**declaration (on usage) / usage(s) (on declaration)**_ | ⌘B | Ctrl + Alt + B |
| _**implementation(s)**_ | ⌘⌥B | Ctrl + Alt + B |
| _**same symbol in parent type**_ | ⌘U | Ctrl + U |
| _**select elements in structure**_ | ⌘[F12] | Ctrl + [F12] |

---

[.build-lists: false]

# Search in Path

- Not _under_used, but under_used_!
- Check the options, esp. scope!

|:apple:          | ⌘⇧F |
|---|---|
|:penguin:/:door: | Ctrl + Shift + F |

---

[.build-lists: false]

# Usage Search

- Can into scope too!
- Especially useful and underused: Have IDEA open new tabs for each
  search (default is replace last search)
- All platforms: ⌥[F7]

---

# IV. Editing (Higher Level)

---

# Refactoring: So, so much too much to cover

- Probably most used is rename (⇧[F6]): highly consistent!
  - Also works for files, change lists, packages…
- Extract variable, field, method, constant… *loves* expand selection
- Underused: Change Signature (:apple:: ⌘[F6] // :penguin:&:door:: Ctrl + [F6])
  - also very consistent! Works e.g. for DB Tables Schema

---

# Analyze!

- Check out what’s available available inspections
  - Can integrate some external tools!
  - A lot support quick fixes; underused: “fix all … in file”
- When “fixing” a warning results in worse code, just disable the occurrence!
  - Depending on situation “with comment” + append reasoning
  - Really important to stay at 0 warnings: “Broken window code policing”

---

# Completions, Pre & Post

## Live Templates

`*` <abbreviation> + ⇥

## Postfix Completions

`*` <expr + . + abbreviation> + ⇥

---

# Language Injection

## Automatically, Ad-Hoc Using Heuristics

NTH, but a crapshoot

## `// language=LanguageName` (Above String)

- E.g. Oracle, PostgreSQL, Groovy, XML, HQL, HTML, CSS, …
- Also as Annotations – check Settings
- Checked-in documentation that triggers IDE magic!

---

# V. Other Stuff

---

# Accepting Autocompletions

Everybody uses ⏎ to insert the completion, but there’s also:

| Complete… | Keystroke |
|---|---|
| …and start autocompleting again on the accepted option: | ⌃. |
| …and overwrite until end of token | ⇥ |

---

# Nice Little Miscellania

| What | :apple: | :penguin:/:door: |
|---|---|---|
| progressively select word under cursor | ⌃G | Alt + J |
| keyword (throws, implements…) impact | ⌘⇧[F7] | |
| fold arbitrary selection | ⌘. | |

---

# Plugins!

- *_Advanced Java Folding_*: Get Kotlinish Syntax in Java Files
  - A multi-edged hypersword
- *_Kotlin_*: OK REPL, even if you don’t use Kotlin
  - you should use Kotlin
- *_Key Promoter X_*: Productivity Guide as a nag, and a scold
  - Great fun!

---

# More Plugins!

- *_Regex Plugin_*: Nicer than the more-used regex test plugin
  - advanced uses like testing group match / replace
- *_.ignore_*: Authoring and inspections for VCS ignore files
- *_Presentation Assistant_*: Shows shortcuts while using IDEA

---

# Former Plugins!

- JVM memory view now core debugger feature – great for debugging leaks, building mental model
- Stream debugger now core debugger feature

---

# Printable Ref Sheet

- `Help > Keymap Reference`
- The online help in IDEA is bredy gud generally
  - Don’t skip it b/c of experience with other software!

---

## More Great Information Can Be Found Through…

* Following links from [@hhariri](https://www.twitter.com/hhariri) (follow highly recommended!)
* Reading the startup “Tip of the Day” and the [IDEA Twitter](https://twitter.com/intellijidea)
* The built-in High Score (Dropdown: Help > Productivity Guide)

---

# VI. Speaker’s Eccentricities

---

# Take Rat Poison

## Just turn your mouse on its back, at arm’s length
### just for a day
#### occasionally

---

# Another Window? Second Editor?

![](wide.png)

---

# How About “All the Code”?

![35%](high.png)

---

# “In Eigener Sache”

- I can be hired for dev productivity workshops and consulting
    - IDEA + Java/Kotlin, Builds (CI/CD), Container Orientation, git
      Handling, …
- I’d love to hold this talk at your company!
    - for free!
        - (…and then chat about your development pain points :smirk:)

---

### Thank you for your attention!

# Q & A
