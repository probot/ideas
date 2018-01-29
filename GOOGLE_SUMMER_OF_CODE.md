# Project ideas for Google Summer of Code 

1. [Automatically merge pull requests that pass all checks](project-1)
2. [Automatically move inactive contributors to an alumni team](project-2)
3. [Weekly digest](project-3)
4. [Set expectations for response time](project-4)
5. [Twitter Integration](project-5)
6. [Background check](project-6)

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
