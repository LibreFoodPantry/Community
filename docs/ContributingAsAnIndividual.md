Contributing as an Individual
=============================


Using the Issue Tracker
-----------------------

* If there isn't an issue for the work you want to do, create one. This could be a pull-request or a plain issue.
* If an issue hasn't been discussed and has not been prioritized (check the labels, or the project boards) by a project maintainer, start that discussion. This has several goals: 1) ensure that the project maintainer is interested in this work being done, 2) clarifying the requirements of the work to be done, 3) establish an acceptable solution strategy, and 4) convey to others that you are interested in working on the issue.  Working on something without doing this step may lead to a waste in effort. You may work on something the maintainers are not interested in. You may miss-understand (or incompletely understand) the issue and solve the wrong problem.
* If the issue is not claimed, claim it. You can do this in three ways; 1) if you are contributor on the project, you can assign the issue to yourself, 2) if you aren't a contributor on the project, you can leave a comment that says that you are claiming the issue, or 3) open a (draft) pull-request that claims that it closes the issue (using [GitHub's keywords](https://help.github.com/en/articles/closing-issues-using-keywords) in the pull-request). The latter is preferred as it also provides a place to observe and discuss implementation.
* If an issue has been claimed (look for an assignment, a comment, or a linked pull-request), check if it is done (merged into master). If so, close it. If you can't close it, [prompt a maintainer](https://github.blog/2011-03-23-mention-somebody-they-re-notified/) to close it. If the work isn't done, and hasn't been worked on in a while, [ask the person](https://github.blog/2011-03-23-mention-somebody-they-re-notified/) who was working on it if they are still working on it. If they aren't, then you can claim it and start working on it. If so, maybe you can help them.
* Push to your pull-request regularly. This let's others know that you are working on it. Others can also give you feedback as you go. Your pull request is a great place to get help if you get stuck.
* If you give up, leave a comment on the issue explaining the problem and indicating that you are abandoning your effort. Be sure to unclaim it (e.g., leave a comment saying you give up, unassign it, and/or close your pull-request without merging it). That way someone else can claim it.


* Post an issue if you find a problem or have an idea to propose.
* Post issues to the project they are most related to. If you are unsure which is most related, post it to the LibreFoodPantry/Community issue tracker.
* Upvote issues that you would like to see completed.
* Help clarify issues by providing more information and by asking or answering questions.


Contributing Code
-----------------

* Follow a fork-pull-request model
    * See [Forking](https://guides.github.com/activities/forking/)
    * See [GitHub Flow](https://guides.github.com/introduction/flow/)
    * See [GitHub Standard Fork & Pull Request Workflow](https://gist.github.com/Chaser324/ce0505fbed06b947d962)
* Claim issues by creating a pull-request early and autolink to the issue in your merge-request description
    * See [Introducing Draft Pull-Requests](https://github.blog/2019-02-14-introducing-draft-pull-requests/)
    * See [Autolinked references and URLs](https://help.github.com/en/articles/autolinked-references-and-urls)
    * See [Closing issues using keywords](https://help.github.com/en/articles/closing-issues-using-keywords)
* Unclaim an issue if you stop working on an issue by closing your pull-request.
* Get feedback on your work by mentioning users you would like to review your work in a comment on your pull-request
    * See [Mention @sombody. They are notified.](https://github.blog/2011-03-23-mention-somebody-they-re-notified/)
* Mark pull-requests as "ready for review" (i.e., not a draft) and ask for a review by mentioning users on your pull-requests
    * See [Changing the status of a pull-request](https://help.github.com/en/articles/changing-the-stage-of-a-pull-request)
* Provide feedback on others work by commenting on pull-requests and/or commits on pull-requests.


Developer Certificate of Origin
-------------------------------

Before a contribution may be accepted by LibreFoodPantry, to ensure that each
contribution is compatible with this project's open source license, its
contributors must sign-off on the following statement about their contribution
(also found in DCO in the root directory of this project).

    Developer Certificate of Origin
    Version 1.1

    Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
    1 Letterman Drive
    Suite D4700
    San Francisco, CA, 94129

    Everyone is permitted to copy and distribute verbatim copies of this
    license document, but changing it is not allowed.


    Developer's Certificate of Origin 1.1

    By making a contribution to this project, I certify that:

    (a) The contribution was created in whole or in part by me and I
        have the right to submit it under the open source license
        indicated in the file; or

    (b) The contribution is based upon previous work that, to the best
        of my knowledge, is covered under an appropriate open source
        license and I have the right under that license to submit that
        work with modifications, whether created in whole or in part
        by me, under the same open source license (unless I am
        permitted to submit under a different license), as indicated
        in the file; or

    (c) The contribution was provided directly to me by some other
        person who certified (a), (b) or (c) and I have not modified
        it.

    (d) I understand and agree that this project and the contribution
        are public and that a record of the contribution (including all
        personal information I submit with it, including my sign-off) is
        maintained indefinitely and may be redistributed consistent with
        this project or the open source license(s) involved.

Contributors sign-off on this statement by adding a `Signed-off-by` line in
the commit message for each (co)author on the commit:
e.g., `Signed-off-by: Armadillo Aardvark <Armadillo.Aardvark@earth.com>`.
This is conveniently done if the commit is by a single author by using
the `-s` option to `git commit`: e.g., `git commit -s`.
If you need to add `Co-authored-by` lines,
manually add a `Signed-off-by` line for each co-author. Note that the
names and emails on the `Signed-off-by` lines must match the `Author`
and `Co-authored-by` lines.
