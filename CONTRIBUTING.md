# Contributor Strategy Technical Advisory Group Contributing Guide
*This is a bootstrapped document that will update frequently in the next few
months as we lay the groundwork for the operations of the TAG. Now onto the
show...:*

🛬Thanks for landing here! There's a good chance you want to help the
contributor side of the code in one of our working groups, get involved on a
regular basis, or simply be curious, no matter your reason, we are excited to have
you.

This [TAG] (Technical Advisory Group) is an extension of the [TOC] that works to
build programs and guidance to help scale and grow open source communities. We
work in this GitHub repository:  

🆕[cncf/tag-contributor-strategy]  
 contains our meta docs that cover our governance, how we operate, and resources that we
 collect along the way. The [website/content] directory contains the source for the
 web pages at [contribute.cncf.io/maintainers][maintainers] and is advice for people who
 are running and maintaining CNCF projects.

Note: Project data listed in [the Contributors section](https://contribute.cncf.io/contributors/) is pulled from the [CNCF landscape](https://landscape.cncf.io/). Submit a PR to [the landscape repo](https://github.com/cncf/landscape) to update any project data.

Our [charter] describes our mission and initial scope of what we’d like to
accomplish. Each of our members are closely involved with at least one CNCF
project; we are here to learn as much as those we serve.

## Contribute to the website

Read our [contributing guide] for details on how to contribute content for [contribute.cncf.io](https://cncf-contribute.netlify.app).

## Ground Rules
We very much welcome everyone on any of our [communication channels] including
through GitHub Issues and Pull Requests (PRs) and ask all contributors to
maintain our welcoming culture. We follow the [CNCF’s code of conduct].

Async communication is our preference because of our global nature but
absolutely value face to face time and meetings when it makes sense. Slack works
well for real time questions and discussion but we will move decisions and key
tasks to GitHub or the mailing list. See our full list of [communication channels].

We don’t sponsor specific company branded documentation and resources as
official guidance to contributors and/or projects. A resources list[link tbu]
that may link to other sources that are not official, including company branded
information, in the strategy repo, is strictly for our groups planning purposes
only.

## Sign Your Commits

### DCO
Licensing is important to open source projects. It provides some assurances that
the software will continue to be available based under the terms that the
author(s) desired. We require that contributors sign off on commits submitted to
our project's repositories. The [Developer Certificate of Origin
(DCO)](https://probot.github.io/apps/dco/) is a way to certify that you wrote and
have the right to contribute the code you are submitting to the project.

You sign-off by adding the following to your commit messages. Your sign-off must
match the git user and email associated with the commit.

    This is my commit message

    Signed-off-by: Your Name <your.name@example.com>

Git has a `-s` command line option to do this automatically:

    git commit -s -m 'This is my commit message'

If you forgot to do this and have not yet pushed your changes to the remote
repository, you can amend your commit with the sign-off by running 

    git commit --amend -s 

## How to Help

**Contributors and/or Maintainers of a CNCF incubated or graduated project:**  
- Be a liaison for your project with our group
  - Why? The ecosystem is very large, if you stay connected, you’ll be closer to
resources and advice.
  - Take back this information to build (or continue to build!) intentional
community and governance spaces and/or roles in your project to do this work at
an operational level
- Have questions? Drop in on a [meeting], either the main TAG meeting or the relevant working group meeting. This is your time to ask us general or
 specific questions that can give you ideas, unblock you, or help with strategy around TOC graduation or incubation project criteria.
- Give us feedback on where you need help, guidance, requested templates,
recommendations, and more here
  - Or you can provide feedback by filing issues against the
cncf/tag-contributor-strategy repo, send a note to the mailing list, or find a
chair or working group facilitator privately on slack.
- Become a contributor in one of our [working groups]
  - File issues and PRs
  - Project management
- Create workshops, talks, blogs, and papers on related contributor content (or
  reuse the good stuff you have!)
- Create templates and other scalable guidance
- Tell us what WORKS! Sounds like a lot of “what doesn’t work” above but we also
want to know what works well for projects in their contributor and governance
areas. Looking at you graduated projects but we see the incubation project crew
still working on great programs!
- Be a part of our work in progress [maintainers circle]!

Academics and open source enthusiasts that have completed research (or underway!)
, studied, and/or created programs for other ecosystems, we would love to hear
from you, too! Similar deal as above - watch out for our Issues, come hang out
in slack, or we'll see you at a meeting!

### Tips for filing issues
//TODO add in comments about how to label once we figure that out

### Pull Request Tips - Submitting and Reviewing
- Talk to us via GitHub issue, mailing list, or meeting before you start on major
work. If it’s typos and fixes to docs, please submit. 😀
- Tap one of the chairs or working group facilitators in slack if you haven’t
heard from us in 5 days.
- If this is a change that you intend to work on iteratively over multiple pull 
requests before it is ready to go live, please make the pull request against the 
drafts branch. When you are ready for the TOC to review your final changes, submit a pull request with your changes to the main branch.

  This makes it easier to collaborate on change sets with multiple people. You can preview changes made on the drafts branch at https://drafts--cncf-contribute.netlify.app
- When making changes to your PR, put them into a new commit (instead of rebasing
  or amending) so that it's easier for reviewers to see just your new changes.
- We will give you an opportunity to clean up your commits before merging or can
squash them for you.
- If a member asks you to "rebase" your PR, they're saying that a lot of docs/code
 has changed, and that you need to update your branch to incorporate the latest
 changes from main before we can merge your PR. You can use whatever you are
 comfortable with, either merging main into your branch or rebasing your
 branch on main.
#### Reviewers:
- We leave pull requests open for at least 48 hours, so that others have the
chance to review/comment except in cases of the following:
  - The majority of contributors in that working group have already reviewed
  - Something urgent or small operational document change like a meeting time
  - Spelling or grammar fixes

## Your First Contribution to GitHub
Open source communities use many different tools. If this is your first
experience with GitHub - yay! There are a ton of great resources out there to
educate on the UI and standard workflows. Everyone has been a beginner at some
point; always feel free to ask for help. You can absolutely use the GitHub UI
vs command line if that works best for your workflow.

https://www.firsttimersonly.com/
//TODO add more resources




[CNCF’s code of conduct]: https://github.com/cncf/foundation/blob/master/code-of-conduct.md
[communication channels]: https://github.com/cncf/tag-contributor-strategy/blob/main/README.md#communications
[TOC]: https://www.cncf.io/people/technical-oversight-committee/
[TAG]: https://github.com/cncf/toc/tree/main/tags
[README]: https://github.com/cncf/tag-contributor-strategy/blob/main/README.md
[charter]: https://github.com/cncf/tag-contributor-strategy/blob/main/CHARTER.md
[working groups]: https://github.com/cncf/tag-contributor-strategy/blob/main/README.md#working-groups
[cncf/tag-contributor-strategy]: https://github.com/cncf/tag-contributor-strategy
[maintainers circle]: https://github.com/cncf/tag-contributor-strategy/issues/1
[website/content]: website/content/
[contributing guide]: https://cncf-contribute.netlify.app/about/contributing/
[maintainers]: https://cncf-contribute.netlify.app/maintainers
[contributors]: https://cncf-contribute.netlify.app/contributors 
[meeting]: https://github.com/cncf/tag-contributor-strategy/#meetings
