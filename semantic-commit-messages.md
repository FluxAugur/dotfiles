# Semantic commit messages

<type>(<scope>)[#<issue#>@<pull request#>]: <short summary>
  |       |         |            |                 |
  |       |         |            |                 --> Short summary in present tense. Not capitalized. No terminating period.
  |       |         |            |
  |       |         |            --> Pull request number.
  |       |         |
  |       |         --> Issue number.
  |       |
  |       --> Scope of change, e.g. api|authentication|common|compiler|core
  |
  --> Type: bump|chore|configure|document|feature|fix|license|localize|make|no-make|optimize|refactor|revert|style|test

e.g. feature(core)[#1234@13]: add hat wobble

Types:
- bump: change version
- chore: change other files that aren't source or test files
- configure: change continuous integration pipeline, build, or repo
- document: change documentation
- feature: change source to add feature
- fix: change source to fix bug
- license: change license
- localize: change localization
- make: trigger new build
- no-make: trigger no new build
- optimize: change source for performance
- refactor: change source for other reasons
- revert: revert to previous commit
- style: change style or formatting
- test: change test files
