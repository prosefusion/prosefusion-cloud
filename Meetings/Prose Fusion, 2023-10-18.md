# Prose Fusion, 2023-10-18

## Terminals and Command History

- observation: each terminal window has its own history, which is saved to the saved-history file when you exit that terminal instance
- observation: in Windows, I'm not sure the shell history always works correctly
- idea: there could be a way to merge all the histories together in real time
    - we asked ChatGPT about this, and it gave us [a clunky way to keep a merged history in bash](https://chat.openai.com/share/d2d8383c-f89d-41aa-8979-35b157a0c253) (link into Pete's ChatGPT history, link will break some day)
- observation / idea: keep a notepad/textedit/obsidian page with your commonly-used commands, and copy/paste to/from your terminal
    - use `history > tmp.txt` to save history (in zsh, `history 1 > tmp.txt`)
- observation / idea: 

## A Hypothesis About Learning Git

Old: Git is complicated.

New:

- Git has a small number of key moving pieces.
- There is a non-trivial (but not necessarily complicated) way the pieces interact and need to be used.
- However, using it could be understandable by a 7-year-old, it's not rocket science.
- The Git "user interface" (commands, etc.) is a mess for historical reasons, which means advanced use is done in "wizard mode" by consulting a book of spells (formerly Stack Overflow, now more by asking ChatGPT).
- But normal day-to-day use doesn't have to be in wizard/spellbook mode.
- There are not (yet) many really good, accessible explanations; Git has historically been learned by apprenticing rather than by reading good explanations.
- Together, we can make good explanations.

## Git File Management

Referring to the diagrams in [[Oliver Steele's 'My Git Workflow']] and [[[[Git Workflow Diagram]]]].

- **workspace** = my files I'm working on and making changes to
- **commit** - a related set of changed files; done as one more-or-less atomic task
- **index** or **staging** = an area where I'm assembling a commit (under the hood, this is just a list of files, not actual copies of files)
- **local repository** = where sequential commits are held (under the hood, this is copies of versions of files, in sort of a filesystem database)
- **remote repository** = either a centralized or peer repository I sync to and from

Other terminology and notes:

- upstream
- downstream
- branch
    - main (fka master)

Git conflict resolution works per "line" of text.

- A line of text is all the text before a linebreak. (Might be displayed on more than one line on the screen, if the line is long and it wraps.) Sometimes also thought of as a "paragraph" in text editors and word processors.