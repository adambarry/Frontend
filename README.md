# Frontend
Frontend portal (3mand.dk)


## Development machine setup
In order for the solution to run you need to have the following software installed on your computer:

1) Microsoft Windows 10, Apple macOS.
1) Google Chrome browser.
1) Git SCM:
    1) Execute the following command in Git Bash after Git has been installed (run as administrator):
	
	```
	git config --system core.longpaths true
	```
	
	This will enable long paths which is e.g. used for some Bower packages (Angular HTTP Batcher to be specific).
1) Atlassian SourceTree (visual Git tool).
1) DiffMerge.  
1) ..
1) .


## Getting started
Clone the repository to your local development machine. To ensure consistency across machines, you’re are encouraged to make sure that the local repository is located in the folder:

- Windows:`C:\Development\Repos\Auwau\`
- macOS: ``

Once the project has been cloned ...

You're should now be all set to start developing.


## Code commit guidelines
We have very precise rules over how our git commit messages can be formatted. This leads to more readable messages that are easy to follow when looking through the project history.

### Commit message format
Each commit message consists of a header, a body and a footer. The header has a special format that includes a type, a scope and a subject:

```
<type>((optional) <scope>): <subject>
<BLANK LINE>
<(optional) body>
<BLANK LINE>
<(optional) footer>
```

Any line of the commit message shouldn't exceed 100 characters! This allows the message to be easier to read on GitHub as well as in various git tools.

#### Type
Must be one of the following:

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug or adds a feature
- perf: A code change that improves performance
- test: Adding missing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

#### Scope
The scope could be anything specifying place of the commit change, e.g. the "app" as a whole, the name of a component/service etc.

#### Subject
The subject contains succinct description of the change:

- use the imperative, present tense: "change" - not "changed" nor "changes"
- don't capitalize first letter
- no period/full stop (.) at the end

#### Body
Just as in the subject, use the imperative, present tense: "change", not "changed" nor "changes" The body should include the motivation for the change and contrast this with previous behavior.

#### Footer
The footer should contain any information about breaking changes and is also the place to reference items (in your project management tool) that this commit relates to.
