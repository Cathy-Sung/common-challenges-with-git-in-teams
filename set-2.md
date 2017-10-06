# Challenge Set 2

1. Let's wreak some havoc! Have a member of your team delete multiple files on GitHub. Talk with your team about how to properly restore the missing files. Then, fix it!
    <details>
      <summary>Documentation and info</summary>

    - Git documentation: [`git revert`](https://git-scm.com/docs/git-revert)
    - Git documentation: [`git reset`](https://git-scm.com/docs/git-reset)
    - Git documentation: [`git push --force`](https://git-scm.com/docs/git-push#git-push--f)
    - Pro Git: See section on _Distributed Version Control Systems_ in [About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

    </details>

1. You would like to ensure that nothing is merged into the `master` branch without a human gate. Devise and implement a strategy amongst your team for approving merges into master.
    <details>
      <summary>Documentation and info</summary>

    - GitHub Help: [About protected branches](https://help.github.com/articles/about-protected-branches/)
    - GitHub Help: [About pull request reviews](https://help.github.com/articles/about-pull-request-reviews/)
    - GitHub Help: [About CODEOWNERS](https://help.github.com/articles/about-codeowners/)
    </details>

1. Create a test scenario to validate the strategy you devised above.
    <details>
      <summary>Documentation and info</summary>

    - What happens if someone tries to push to a protected branch?
    - Can a developer open a pull request against a protected branch? Can they merge it?
    - What happens when a file or filetype that is referenced of CODEOWNERS is modified?
    </details>

1. Imagine your project is growing, and people are opening many issues without text in the body. Have someone on your team install the [request-info](https://probot.github.io/apps/request-info/) Probot app into your shared repo. Then, test it out by opening a blank issue!
    <details>
      <summary>Documentation and info</summary>

    - Probot: [App directory](https://probot.github.io/apps/)
    - Probot: [Building your own app](https://probot.github.io/docs/)
    - Probot: [Organization + source code](https://github.com/probot)
    - GitHub Marketplace: [Tools to build and improve your workflow](https://github.com/marketplace/)
    </details>



[:next_track_button: To set 3](set-3.md)
