# The Learn Storybook design system

The Learn Storybook design system is a subset of the full [Storybook design system](https://github.com/storybookjs/design-system/), created as a learning resource for those interested in learning how to write and publish a design system using best in practice techniques.

Learn more at [Learn Storybook](https://learnstorybook.com).

# COMMANDS USED: -----------------------------------------------

```bash
npx degit chromaui/learnstorybook-design-system --force
yarn install
yarn storybook
git init
git add .
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/AlexAxis/storybook-alexis
yarn init
yarn auto create-labels
yarn auto changelog
git reset HEAD^
git add CHANGELOG.md
git commit -m "Changelog for v0.1.0 [skip ci]"
npm version 0.1.0 -m "Bump version to: %s [skip ci]"
npm whoami
npm adduser
npm publish

git push --follow-tags origin master
yarn auto release

```
