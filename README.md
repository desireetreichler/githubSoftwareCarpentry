# githubSoftwareCarpentry
github software carpentry course

Etherpad: http://pad.software-carpentry.org/2017-05-24-github  
Project we work on: https://github.com/desireetreichler/guacamole-recipe
______________________________________________________________

Difference between corporate and private account: with uio account you cannot make your repository public. Github private: everything is public (unless you pay)

This readme: stored as markdown language (.md). 
* hash tag: heading 1
* line break: needs double space, otherwise it will be ignored..?
* asterisk: bulleted list
* number and dot: numbered list - numbers correctly even if you mix up the numbers!
* italics: underscore, bold: asterisk, code mode: accent grave - before and after


Make a new repository: 
"+"   -> name it, public (private is paid)

Edit it: with the pen -> two tabs, edit and preview changes ("the diff"), e.g. adding or deleting text. 

Make a new file: 
"create new file" -> commit changes: you can give your changes a name

On the repository main page: 
Commits -> view all your commits (and diffs), each change has a unique code that stores your diff (e.g.  38ec376aed7cca048604a1976bf33c877d9daf8f @desireetreichler desireetreichler committed on GitHub 4 minutes ago ) that can also be commented  
The first line in any commit are instructions on where to add/delete lines (change files)


Collaborate:
Tab "Settings", -> "Collaborators".
Collaborators get an email when you comment on their commit.

Comments: Possible on commits only, not on the file directly! - but you can click on the number in front of a line to create a link that points directly to that place in a file: 
https://github.com/desireetreichler/guacamole-recipe/blob/master/instructions#L4

Issues: (tab)
Create a new task to to. Written in markdown. You can also assign this to a person and discuss it interactively (in comments) 
When closing issues, you can refer to pull requests/issues (see below) by typing hashtag, then a list of all linkable actions pops up.

New branch: create one to try out things. Can be merged later!
* either in the main project view manually
* or when commiting a change - instead of pushing it onto the master branch. Usually followed by the invitation to create a new pull request, good practice.

Pull requests: (tab)
(requires that first a new branch is opened, and something is changed there - for example, the instructions list) 
Create a pull request: will show up as a commit, and give everyone the opportunity to comment on it. 
Reviewing pull requests: check the changes and comment on them interactively. In the comments, you can refer to an issue by typing hashtag for a list of linkable actions.  
It is also possible to request the changes and block the pull request until the reviews are done!
Following step: confirm merge - can be the same person, or someone else, or the owner of the project, subject to internal customs/rules in the collaboration project (:

Conflicts: If a pull request results in a conflict (because the two branches edit the same line), this ought to be resolved - there is an option to do this in an editor (link comes up), manually. If ignored, some remaining conflict text (lots of >>> and ===) will stay in the file!


Collaborate with a project that I am not officially collaborator on:




To print this in a formatted style: plugin in chrome, or clone it locally and use the tools there.
