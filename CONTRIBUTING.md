# Contributing

First of all, thank you for your interest in contributing to (one of) Syde's public repos. We greatly appreciate your feedback, suggestions and code contributions. 
When contributing to any repository, please first discuss the change you wish to make with the owners of this repository via an Issue, a Pull Request, or both.

Since Syders need to prioritize their day-to-day work for our client projects and products over the maintenance of public repositories, the responsible maintainers might not be able to respond to your requests or comments straight away. Still, as a rule, we try to respond to requests within a week. If you have been waiting for longer than two weeks, it's OK to post a friendly reminder in the issue thread.

On that note: we have a [code of conduct](./CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.


## Pull Request Process

### <a name="submit-pr"></a> Submitting a Pull Request (PR)

Before you submit your Pull Request (PR) consider the following guidelines:

1. Search [GitHub](./pulls) for an open or closed PR that relates to your submission.
   You don't want to duplicate existing efforts.

2. Ensure any install or build dependencies are removed before the end of the layer when doing a 
   build.

3. Make your changes in a new git branch:

     ```shell
     git checkout -b my-fix-branch main
     ```
   
4. Commit your changes using a descriptive commit message that follows our [commit message conventions](#commit).
   Adherence to these conventions is necessary because release notes are automatically generated from these messages.

     ```shell
     git commit --all
     ```
   Note: the optional commit `-a` command line option will automatically "add" and "rm" edited files.

5. Push your branch to GitHub:

    ```shell
    git push origin my-fix-branch
    ```

6. In GitHub, send a pull request to `main` branch.

## <a name="commit"></a> Commit Message Format

When working on this repository, we encourage you to follow the [7 rules of a great commit message](https://cbea.ms/git-commit/#seven-rules):

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

While our company standard is based upon these seven rules, do not be surprised if you encounter slightly different formats being used in our projects. Some of our public projects were created years ago, in a time where we did many things differently, including the composition of commit messages. Currently, we also allow prefixes in the commit message header for repositories that rely on those prefixes for release automation. Still, this is something you might not see in use on the repository you may be interested in.  
The most important thing to remember is to use common sense and write clear and concise commit messages.
