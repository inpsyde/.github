# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue 
with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

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

When working on this repository, we encourage you to adhere to the following commit message format. Following this convention will lead to an **easier to read commit history** and is especially helpful in projects that use automated release versioning.

*Note: commit message formats are still under review at Inpsyde, so do not be surprised if you different formats being used in our projects. The most important thing to remember is to write clear and concise commit messages. The following specification helps you do exactly that. It is inspired by the [AngularJS commit message format][commit-message-format]. For more information, see [https://www.conventionalcommits.org](https://www.conventionalcommits.org).*


Each commit message consists of a **header**, a **body**, and a **footer**.


```
<header>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The `header` is mandatory and must conform to the [Commit Message Header](#commit-header) format.

Any line of the commit message cannot be longer than 100 characters.

#### <a name="commit-header"></a>Commit Message Header

```
<type>: <short summary>
  │             │
  │             └─⫸ Summary in present tense. Not capitalized. No period at the end.
  │
  └─⫸ Commit Type: build|ci|docs|feat|fix|perf|refactor|test
```

The `<type>` and `<summary>` fields are mandatory.

##### Type

Must be one of the following:

* **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
* **ci**: Changes to our CI configuration files and scripts (example scopes: Github Action)
* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **perf**: A code change that improves performance
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **test**: Adding missing tests or correcting existing tests
