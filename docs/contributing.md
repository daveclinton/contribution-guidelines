# Contributing to SAP documentation

SAP documentation is an extremely valuable asset and benefits everyone. While the ownership and responsibility will always remain with SAP for the content, we recognize that the wider community can help make our documentation better.

Your regular use of SAP documentation affords you a pragmatic experience that is unmatched, and we want to make use of that experience to improve our documentation. We would very much like you to collaborate with us to do that, by offering you the ability to submit contributions.

Understand that we are not looking for you to take over the authoring of content for us; rather, we value your feedback and eye for detail and realize that collaboration has many advantages here.

There are two ways in which you can contribute to SAP documentation. Briefly, there is feedback, and there is content contribution.

> Availability of these two contribution types will depend on the documentation in question. Sometimes only feedback will be available, sometimes only content contribution will be available, sometimes both, and sometimes neither. It all depends on the team managing the documentation set.

## GitHub account

Both feedback and content contributions are facilitated via mechanisms in GitHub. Specifically, feedback contributions are made via [GitHub issues][github-issues], and content contributions are made via [pull requests][github-pull-requests].

This means that in order to contribute, you will need a GitHub account. Read more about the signup process in the article [Signing up for a new GitHub account][github-signup]. A simple individual user account will suffice.

## Types of contribution

As mentioned earlier, there are two ways in which you can contribute to SAP documentation - either by providing feedback, or by offering a contribution of content.

### Providing feedback

We value feedback on our documentation, and want to make it possible for you to do that in a simple but structured way.

Where feedback is possible for a page, you will see an appropriate link at the bottom of the page, inviting you to contribute feedback.

![Feedback link](assets/feedback-link.png)

Following the link will take you to the "New Issue" page in GitHub, specifically for the repository containing the SAP documentation content that for which you want to provide feedback.

Note that there will be some content automatically added to the main feedback edit area; this is to provide us with a way of associating the feedback you are providing with the appropriate page in the documentation. This is very important in two respects:

1. You should not remove any of this information.
1. The implication is that feedback should be for a specific SAP documentation page, rather than generally.

So, please ensure that when creating a new feedback issue, that you add your feedback to the issue without removing any of the technical information that has been put there automatically, and limit your feedback to the content in the page for which you are providing feedback.

For more details about making a feedback contribution, please see [Contributing feedback via issues](feedback.md).

### Contributing content 

In some cases, we want to make it possible for you to contribute by providing small amounts of content. We're not asking or expecting you to provide large amounts of content; rather, we're opening up the opportunity for you to to contribute to SAP documentation by offering content such as:

- Corrections to typos that you spot.
- The rewording of a phrase or sentence for clarity.
- The addition of information or context to qualify or increase accuracy.

If you spot something that's missing, incorrect, lacking clarity or requiring more context, you can of course provide feedback via an issue, and ask us to address it.

But with content contribution, you have the opportunity to collaborate with us by adding that missing information, correcting the mistake, or providing clarification.

Where content contribution is available, you'll see a link like this:

![Content contribution link](assets/content-contribution-link.png)

If you're already familiar with collaboration by means of pull requests on GitHub, then this process will be familiar to you. If not, don't worry, it's straightforward, and the GitHub workflow infrastructure, combined with how we use it for collaboration on SAP documentation, will make the process easy for you to follow.

Briefly, here's what a typical pull request based content contribution workflow will entail. Note that you start out on the SAP Help Portal, but are taken to the corresponding SAP documentation repository, within the [SAP-docs][sap-docs-org] organization on GitHub, where most of the collaboration workflow steps will take place. Note also that some details have been omitted here for brevity but you can find those details in [Contributing content via pull requests](content.md).

**In the SAP Help Portal**

1. Your starting point is in the SAP Help Portal, and you're looking at a page of SAP documentation.

2. You spot something in the page that you think would benefit from a minor modification or addition.

3. You check for, find, and follow the link that allows you to make a content contribution.

**In GitHub**

4. You're taken to the source of the SAP documentation page, on GitHub, where you can confirm that this is indeed the page to which you want to make a contribution.

5. You use the "✎ Edit" link to launch the browser-based editor for that page, and make your contribution.

6. Once you're happy with your contribution, and have saved the changes you've made, you'll be guided in creating a pull request, which is the unit of conversation that combines the actual details of your content contribution offering, with the conversation that will then take place between you and the team responsible for the SAP documentation page in question.

7. During that conversation, various checks will be made, some automated, some human-based, to confirm whether the contribution is appropriate and will add value. A successful contribution will be merged into the SAP documentation page source and the pull request is then closed.

**Back in the SAP Help Portal**

8. For those content contributions that are successful, the changes will eventually be merged back into the source repository in the [SAP-docs][sap-docs-org] organization. From there, it is only a matter of time before those changes then also appear on the page in the SAP Help Portal.

9. Congratulations - you've just collaborated with us and made a valuable contribution to SAP documentation. Thank you!

For more details about making a content contribution, please see [Contributing content via pull requests](content.md).



[github-issues]: https://guides.github.com/features/issues/
[github-pull-requests]: https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests
[github-signup]: https://docs.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account
[sap-docs-org]: https://github.com/SAP-docs/