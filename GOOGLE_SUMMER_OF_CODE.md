# Project ideas for Google Summer of Code 

1. [Automatically merge pull requests that pass all checks](#project-1)
2. [Automatically move inactive contributors to an alumni team](#project-2)
3. [Weekly digest](#project-3)
4. [Set expectations for response time](#project-4)
5. [Twitter Integration](#project-5)
6. [Background check](#project-6)
6. [Enforce documentation updates in pull requests](#project-7)

<a name="project-1"></a>
## 1. Automatically merge pull requests that pass all checks

For projects that fully trust their test coverage and that enforce pull request reviews, the merge of pull requests could be automated once all checks are passing. The branch of the merged pull request can be deleted.
https://github.com/probot/ideas/issues/22

- Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
- Possible mentors: Brandon, Gregor, Jason

<a name="project-2"></a>
## 2. Automatically move inactive contributors to an alumni team

Every collaborator on a team with write access is a potential risk. As collaborators become inactive they could be moved to an alumni group with read-access only. That would also help the maintainers to keep an oversight of the amount of active contributors a community has
https://github.com/probot/ideas/issues/23

- Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
- Possible mentors: Brandon, Gregor, Jason

<a name="project-3"></a>
## 3. Weekly digest

A bot that summarizes weekly activity in a locked issue. It would comment what issues have been mostly discussed / upvoted, new releases, welcome new contributors, give shoutouts to recurring contributors, etc
https://github.com/probot/ideas/issues/24

- Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
- Possible mentors: Brandon, Gregor, Jason

<a name="project-4"></a>
## 4. Set expectations for response time

Acknowledging contributions in a timely matter and setting expectations for response is one of the most important things you can do to keep a contributor engaged. Based on recent activity, a bot should be able to let contributors know when they can expect to receive a response.
https://github.com/probot/ideas/issues/6

- Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
- Possible mentors: Brandon, Gregor, Jason

<a name="project-5"></a>
## 5. Twitter Integration

Use GitHub’s Pull Requests & Reviews to collaborate on a shared twitter account. Tweets are simply files in a repository. The GItHub app would enforce the character limit by setting a pull request status. Tweets could be allowed to be scheduled or be queued based on a configured tweet schedule

- Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
- Possible mentors: Brandon, Gregor, Jason

<a name="project-6"></a>
## 6. Background check

Each time someone comments on something in a GitHub repository, the github app checks if the user is new to the project. If they are, the bot loads the most recent ~100 comments and runs a sentiment analysis on it. If any of the comments stand out as aggressive then create an issue in a private repository or a discussion for a configurable team to point the maintainers to the new user’s comment and their comments on other projects that might show that they have been hostile before

Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
Possible mentors: Brandon, Gregor, Jason

<a name="project-7"></a>
## 7. Enforce documentation updates in pull requests

This bot can be installed to make sure that documentation is updated whenever code changes. In order for the bot to know that there is a new feature or breaking change it would parse all commit messages using [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog). The [preset option](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog#preset) would allow to use one of the officially supported commit message conventions to be used.

If `conventional-changelog` detects a new feature or a breaking change it will check if the repository's README file was updated (configurable, too). If documentation was not updated it sets status to error, otherwise to success

More ideas

- look for (configurable) labels like `feature` or `breaking change` for pull requests that do not follow the commit message conventions.
- if a pull request gets squash & merged then bot could do the check after the merge and if documentation was not updated it could create an issue

https://github.com/probot/ideas/issues/30
- Expected outcome: GitHub Application like https://github.com/apps/stale that can be installed on GitHub repositories
- Possible mentors: Brandon, Gregor, Jason

---

Google Summer of Code reference: [Defining a Project (Ideas List)](https://google.github.io/gsocguides/mentor/defining-a-project-ideas-list)
