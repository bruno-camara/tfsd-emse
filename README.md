# GIT basic features - tfsd-emse
> Repository for git and github basic features for Technological foundations of software development class.

## Questions

**0.5/5 points - Create a private key/public key pair, add your public key on github/gitlab.**

[See the image SSH.png](./screenshots/SSH.png)

**0.5/5 points - Configure Git to sign your commits with a gpg key. Add this key on github/gitlab so it can verify your commits**

- See the image [GPG.png](./screenshots/GPG.png) to view the configuration process

- Check the image [GPG2.png](./screenshots/GPG2.png) to see the prove that my commits are now verified

**0.5/5 points - Create a .gitignore file to not upload downloaded libraries and other temporary files.**

- [gitignore](./.gitignore) file adapted to Java programs

**1/5 points - Commit atomic changes. Commit with informative messages.**

```bash
git add README.md
git commit -S -m "update README"
```

**1/5 points - Create a milestone and assign it at least two nicely filled issues.**

- Check the image [Milestone_Issues.png](./screenshots/Milestone_Issues.png)

**1/5 points - Create a branch for a feature, push this branch, create a pull request to merge this feature branch in the main branch.**

- To create a new branch:
```bash
git checkout -b featuresum
```
- Push it to github:
```bash
git push --set-upstream origin featuresum
```
- Check the image [pull_request.png](./screenshots/pull_request.png) to view the pull request on github

**0.5/5 points - Create and push a git tag**

- Create a tag:

```bash
git tag -a v1.0 -m "version 1.0 of lecture2 assignements"
```

- Push tag to github:
```bash
git push origin v1.0
```
