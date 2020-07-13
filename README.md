# Archived

This repository has been archived. Due to changes that have been made to the system, many of these features are either already implemented directly or no longer work. Other user scripts exist out there to do many of the remaining tasks that were not covered by recent tooling changes.

# Stack Exchange Moderator Tools Improved

This is a user script which moves most of the options *out* of the mod menu and directly onto the post.

# Functional

- Adds the protect/unprotect link back to the post options (which is normally hidden from moderators for the spare room).
- Moves the mod menu link down to the next line and adds (un)lock, merge (for questions), (de)notice, (un)wiki, and convert (for answers) options to the mod menu line.
- Revisions and timeline links for the post appear underneath the moderator-action links.
- The **(un)wiki** option will spawn a confirmation popup before immediately completing the action.
- A flags indicator will appear under the voting controls at the left of the post indicating the number of flags which have ever been cast on that post (only appears if greater than zero).
- The default moderator info box in the left gutter of a post will be hidden.
- The "show *x* more comments" option is shortened to just "*x* more comments" below the comment list.
- Adds options to purge all and move to chat at the bottom right of the comment list.
- The **purge all** options will spawn a confirmation popup before immediately completing the action.
- If there are deleted comments on the post, a "*y* deleted" option will appear to the right of the "*x* more comments" option, and will show all deleted comments upon clicking.
- Adds a "remove bounty" option at the bottom of a bounty notice, which will spawn a confirmation popup before immediately removing the bounty from the question.
- Adds a "show deleted" link to moderator election nomination posts so moderators can load the deleted comments.

**Note:** The moderator-only actions will appear in red for indication.

# Not Functional (To Be Done)

- The **lock** option should spawn a popup consisting of the various lock options for that post.
- The **merge** option should spawn a richer popup UI, allowing the user to input and lookup the URL/ID of a target master question in order to minimize possible mistakes.
- The **convert** option should spawn a popup for converting the answer to a comment (and possibly add an option for converting it to an edit also).
- The **notice** option should spawn a popup consisting of the various post notices for that post.
- The **move to chat** option should do... uhh... something. I don't know exactly how that function works to begin with.
