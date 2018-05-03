# GitHub Flow

## What is it?
GitHub Flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly:

- [] first
- [] second

![GitHub Flow diagram](https://cloud.githubusercontent.com/assets/4215/16997425/a1e816a2-4e72-11e6-9de7-0961ada64ea6.png)

At GitHub, we consider the GitHub Flow to be an ideal to strive for in any software development team. It does have some prerequisites: automated testing, continuous integration, and the ability to deploy feature branches.

With GitHub Flow, your developers create focused and short-lived feature branches from master, discuss implementation in pull requests, test their feature branches automatically, and merge only after the feature has been deployed to staging or production environments.

GitHub Flow helps your teams avoid merge conflicts and makes your project history easier to understand. These tightly focused and short-lived branches also make code review faster and easier. It's our experience that the laborious, process-heavy code review that some other tools quietly encourage is often a result of overly-large feature branches.

**Additional resources:**
- [Our interactive GitHub Flow guide](https://guides.github.com/introduction/flow/) [[PDF](https://guides.github.com/pdfs/githubflow-online.pdf)]
- [Scott Chacon's GitHub Flow blog post](http://scottchacon.com/2011/08/31/github-flow.html)
- :tv: [Effective GitHubbing: The GitHub Flow](https://vimeo.com/68378254)

## Let's try it together!
In the `participants` directory in this repository, we'll be creating a new [Markdown](https://guides.github.com/features/mastering-markdown/) (`*.md`) file with your first name or GitHub username, e.g.: `mfilosa.md`.

As you follow along in the workshop, we'll show you how to do this in a new Git branch, then merge the proposed changes back into `master` via a pull request.

You can use the below raw markdown template to create your [your-github-username].md file in your branch and fill in the relevant information.

 ```
 ### Hi, I'm [your-github-username]

 | Property | Value |
 |:---------------|:-----------------|
 | Name | [Your Name] |
 | Favorite color | Yellow |
 | Favorite emoji | :sparkles: |
 ```
