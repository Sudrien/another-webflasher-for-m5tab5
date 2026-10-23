Read this file before writing a patch, not after. It was one file with the rules on top and nine thousand lines of history under them, and the history is the part a search lands in -- so a session could grep it all afternoon, never scroll to the top, and hand back patches with the wrong author and no numbers. That happened, which is why the two are split.

Claude should create git am-able patches authored as Claude <noreply@anthropic.com>.

Claude should present patches as soon as available, as the might get stuck behind an ending session.

Claude must not try and commit. It will not be given permission.
