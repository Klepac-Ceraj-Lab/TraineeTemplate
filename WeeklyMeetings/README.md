# Periodic Meetings

This folder contains records of periodic meetings, to-dos, etc.
Longer-term goals or
tracking of individual development and projects
should be placed in `./Projects/`, `./IDP/`,
or in project-specific repositories.

## Usage

Each week (or whatever duration is appropriate),
the trainee should fill out a periodic report
using either the Issue Template or the markdown template
(described more below).
This should ideally be completed
_in advance_ of the meeting, so that the supervisor
has time to review.

Once the meeting is concluded, the trainee or supervisor
should commit the contents to a markdown file contained
in the folder, linking to relevant issues / PRs as appropriate.

### Issue template

For trainees that are less comfortable with git or with plain text/markdown,
a github issue template is provided to facilitate entering notes.
To use the issue template:

1. On the repo site on github, click the "Issues" tab.
2. Select "New Issue," and choose "Periodic Meetings"
3. Fill out the template as appropriate.
   1. In the free-text fields, unfinished To-Dos can be written with `- [ ]`,
      eg. `- [ ] Run a PCR with new primers` (note the space after the `-` and between the brackets).
   2. Completed To-Dos are written the same, except with an `x` between the brackets,
      eg. `- [x] Run a PCR with new primers`.
   3. It can be a good idea to link to the previous meeting's issue.
      Github will automatically expand eg `#4` to a link to issue/PR 4,
      though you can use an explicit link to make it more portable.
4. Submit the issue, ideally in advance of the meeting.
5. During the meeting, comments / additional notes may be added
   either by clicking the 3 dots button on the top right of the issue text and choosing "edit",
   or by using entering new comments to the discussion below the issue.

Once the meeting is concluded,
the contents of the issue should be commited to the repo.
The best way to do this is to copy the markdown contents of the top message
(this can be accessed by clicking "edit" as described in step 5 above)
to a new markdown file in the `./PeriodicMeetings/` directory,
committing this file, and making a Pull Request (see below),
linking the original issue.

This final step may be completed by the supervisor until the trainee
gets more familiar with git.

#### Using the issue template for the first time

Consider the following changes to the issue template prior to using for the first time:

1. Change "Periodic" to "Weekly" or "Monthly" or some other value as appropriate
2. Change the `- assignee` on ln7 to the github user name of your supervisor(s). 
   If your supervisor is Kevin Bonham, you can leave it as-is.

### Markdown template