### Checking Out the Tyrus Sources

Tyrus uses GIT version control system and this fact allowed us to have the project sources available
on [GitHub][tyrusgh]. The repository can be cloned
in a read-only mode by invoking:

```bash
git clone git@github.com:tyrus-project/tyrus.git
```

If you're only interested in reading the latest version of the sources and do not wish
to a) contribute code back to the repository or b) do not care about the history,
you can speed up the clone process by invoking:

```bash
git clone --depth 1 git@github.com:tyrus-project/tyrus.git
```
instead. This may speed up the clone process considerably.

### Understanding Tyrus Branches and Tags

Tag & Branch information:

Tag/Branch Name                                                     | Details
---                                                                 | ---
[master][tyrusgh]                                                   | This is effectively Tyrus development branch ("trunk" in SVN terms).
[1.0](https://github.com/tyrus-project/tyrus/releases/tag/1.0)      | This is the Tyrus 1.0 release tag. A sustaining branch for Tyrus 1.0 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16078).
[1.1](https://github.com/tyrus-project/tyrus/releases/tag/1.1)      | This is the Tyrus 1.1 release tag. A sustaining branch for Tyrus 1.1 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16467).
[1.2](https://github.com/tyrus-project/tyrus/releases/tag/1.2)      | This is the Tyrus 1.2 release tag. A sustaining branch for Tyrus 1.2 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16550).
[1.2.1](https://github.com/tyrus-project/tyrus/releases/tag/1.2.1)  | This is the Tyrus 1.2.1 release tag. A sustaining branch for Tyrus 1.2.1 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16601).
[1.3](https://github.com/tyrus-project/tyrus/releases/tag/1.3)      | This is the Tyrus 1.3 release tag. A sustaining branch for Tyrus 1.3 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16600).
[1.3.1](https://github.com/tyrus-project/tyrus/releases/tag/1.3.1)  | This is the Tyrus 1.3.1 release tag. A sustaining branch for Tyrus 1.3.1 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16797).
[1.3.2](https://github.com/tyrus-project/tyrus/releases/tag/1.3.2)  | This is the Tyrus 1.3.2 release tag. A sustaining branch for Tyrus 1.3.2 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16808).
[1.3.3](https://github.com/tyrus-project/tyrus/releases/tag/1.3.3)  | This is the Tyrus 1.3.3 release tag. A sustaining branch for Tyrus 1.3.3 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16810).
[1.3.4](https://github.com/tyrus-project/tyrus/releases/tag/1.3.4)  | This is the Tyrus 1.3.4 release tag. A sustaining branch for Tyrus 1.3.4 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16838).
[1.3.5](https://github.com/tyrus-project/tyrus/releases/tag/1.3.5)  | This is the Tyrus 1.3.5 release tag. A sustaining branch for Tyrus 1.3.5 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16860).
[1.4](https://github.com/tyrus-project/tyrus/releases/tag/1.4)  | This is the Tyrus 1.4 release tag. A sustaining branch for Tyrus 1.4 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16770).
[1.5](https://github.com/tyrus-project/tyrus/releases/tag/1.5)  | This is the Tyrus 1.5 release tag. A sustaining branch for Tyrus 1.5 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16825).
[1.6](https://github.com/tyrus-project/tyrus/releases/tag/1.6)  | This is the Tyrus 1.6 release tag. A sustaining branch for Tyrus 1.6 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16874).
[1.7](https://github.com/tyrus-project/tyrus/releases/tag/1.7)  | This is the Tyrus 1.7 release tag. A sustaining branch for Tyrus 1.7 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16944).
[1.8](https://github.com/tyrus-project/tyrus/releases/tag/1.8)  | This is the Tyrus 1.8 release tag. A sustaining branch for Tyrus 1.8 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/16966).
[1.8.1](https://github.com/tyrus-project/tyrus/releases/tag/1.8.1)  | This is the Tyrus 1.8.1 release tag. A sustaining branch for Tyrus 1.8.1 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17031).
[1.8.2](https://github.com/tyrus-project/tyrus/releases/tag/1.8.2)  | This is the Tyrus 1.8.2 release tag. A sustaining branch for Tyrus 1.8.2 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17042).
[1.8.3](https://github.com/tyrus-project/tyrus/releases/tag/1.8.3)  | This is the Tyrus 1.8.3 release tag. A sustaining branch for Tyrus 1.8.3 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17050).
[1.9](https://github.com/tyrus-project/tyrus/releases/tag/1.9)  | This is the Tyrus 1.9 release tag. A sustaining branch for Tyrus 1.9 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17022).
[1.10](https://github.com/tyrus-project/tyrus/releases/tag/1.10)  | This is the Tyrus 1.10 release tag. A sustaining branch for Tyrus 1.10 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17086).
[1.11](https://github.com/tyrus-project/tyrus/releases/tag/1.11)  | This is the Tyrus 1.11 release tag. A sustaining branch for Tyrus 1.11 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17199).
[1.12](https://github.com/tyrus-project/tyrus/releases/tag/1.12)  | This is the Tyrus 1.12 release tag. A sustaining branch for Tyrus 1.11 release will be created from the tag if necessary. [Fixed issues](https://java.net/jira/browse/TYRUS/fixforversion/17326).

In order to check out a branch in git, you simply need to issue
`git checkout <branch name>` (e.g. `git checkout master`).

If you're interested in working with an existing tag, you'll first need to issue
`git fetch --tags` in order to obtain the tag references.  After successful completion
of this command, you can issue `git checkout <tag name>`. Note that when doing so, you'll
get a message about being in a detached state - this is normal and nothing to worry about.
All fetched tags can be listed using `git tag -l` In general, we keep our tag names
inline with the released version.  For example, if you wanted to checkout the tag
for Tyrus 1.0, the tag name would be *1.0* This convention is consistent for
all branches/versions/releases.

### Submitting Patches and Contribute Code

Contributing to Tyrus project can be done in various ways: bug fixes, enhancements, new features,
or even whole new extension modules. In general, all contributions must comply with following
requirements:

*   All contributors must sign the [Oracle Contributor Agreement][oca].

*   Any new contribution must be associated with an existing [Tyrus issue][tyrus-jira].
    If no existing issue has been yet opened for the problem your contribution attempts to solve,
    please open a new one.

*   All bug fixes must be accompanied with a new unit test (or a set of unit tests) that
    reproduce the fixed issue.

*   New large feature contributions must be accompanied with:

    *   A patch for [Tyrus User Guide][tug-sources] that is written in DocBook 5. Either a
        new chapter or a new section to existing chapter must be provided as appropriate.

    *   At least one new [example][tyrus-examples] demonstrating the feature.

For small patches (minor bug fixes, correction of typos in documentation etc.), linking a
[gist][gist] that contains your patch with details on what you\'re resolving and how you\'ve
resolved it is most convenient approach. Alternatively, especially in case of larger contributions
or more significant changes in code, please follow the process of opening a new
[GitHub pull request][gpr].

### GIT Tips and Tricks for Developers

First, for anyone not familiar with Git, before attempting to work with the repository,
we highly recommend reading the [Git tutorial][gitorial].

When collaborating, before you push your changes to the remote repository, it's best
to issue `git pull --rebase` This will 'replay' any changes that have occurred in the
remote repository since your last pull on top of your current work.  If you don't do this,
Git will perform a merge for you, however, the result of the commit will look like
you've touched files that you haven't.  This is fine, but it generally raises a few eyebrows
and makes code reviews of any patches slightly more complicated. As usual, more complications
means more time spent in review.

There are times when you may need to move changes back and forth between branches.
In cases where the code bases are very similar, you can use
`git cherry-pick <SHA1 of the commit to pick and apply>` to do this quickly.



[gist]: https://gist.github.com/
[gitorial]: http://schacon.github.com/git/gittutorial.html
[gpr]: https://help.github.com/articles/using-pull-requests
[oca]: http://www.oracle.com/technetwork/community/oca-486395.html

[tyrus-jira]: http://java.net/jira/browse/TYRUS
[tyrus-examples]: https://github.com/tyrus-project/tyrus/tree/master/samples/
[tyrusgh]: http://github.com/tyrus-project/tyrus/
[tug-sources]: https://github.com/tyrus-project/tyrus/tree/master/docs/src/main/docbook/
