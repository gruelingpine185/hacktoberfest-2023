# Contributing

## Guidelines

- Have Fun! I cannot reiterate how important this is. 
- Do Not Delete Files. These file are made by your fellow Github peers, so respect them and their contributions.
- Follow the style of your language. This includes whitespace (e.g 4 space tabs) and variable cases (e.g snake_case).

## Making Contributions

Be sure to look for similar ideas you may have that already exist within the repository. Avoid making duplicates of issues or Pull Requests when you can. With that in mind, here are 6 simple steps you need to do to contribute.

1. Fork this repository

At the top right corner of the Github repository, there will be a button that says `fork`. After clicking it, there will be a green button that creates the fork.

2. Clone your fork of this repository

Now, you should have a new repository in your repo panel in the form of `<your-username>/hacktoberfest-2023`. From a terminal, run these commands to clone this repository and enter it.

```sh
git clone https://<your-username>/hacktoberfest-2023
cd hacktoberfest-2023/
```

3. Create a branch

This branch is where all of your contributions for a particular feature or item will reside.

```sh
git checkout -b <branch-name>
```

The branch name can be anything, but ideally it should be a one to three word summary of a feature or contribution you plan to make.

4. The fun part (your contribution)

At this point, everything is setup for you to make your changes to the repository.

Name your file `hw.<file-extension>` and place it in the `./hellow_world/` directory.

The goal is to have fun and learn. Once you are ready to save your changes, add and commit them.

This command allows git Git to track your changes.

```sh
git add <files you added/changed>
```

This command commits (saves) your changes for each file specified in the command. Make sure to add a useful and informative comment to document your changes.

```sh
git commit -m "<your commit message>" <files you added/changed>
```

5. Push to origin

Make your commits visible on Github.

```sh
git push origin <your-branch>
```

6. Create a Pull Request

The final step is to create a Pull Request. This allows your changes to be reviewed, commented on, and accepted. From your forked repository on Github, click the `New Pull Request` button at the top of your repository page. Add a fitting title and write an informative description about the changes you made.

At this point your work is done! Give yourself a pat on the back and patiently wait for your PR (Pull Request) to be reviewed and accepted. Happy Coding :)
