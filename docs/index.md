# Selvejj

Selvejj brings the powerful features of the [Jujutsu Version Control System](https://jj-vcs.github.io/jj/latest/) to
JetBrains IDEs (IntelliJ, PyCharm, and
others). It hooks into native VCS integration so you can keep using the same interface as with Git.

Selvejj treats `jj` repositories as first-class. You do not need co-located Git repositories.

**Selvejj is currently in pre-release and far from feature complete.**

## Download

The plugin is [available on the JetBrains Marketplace](https://plugins.jetbrains.com/plugin/28081-selvejj).

The best way to install it is to use the IDE's built-in plugin manager and search for Selvejj.
Go to Settings > Plugins > Marketplace and search for Selvejj.

## Current features (v0.5.1)

* View the jj log in the VCS log window
  * Branches are grouped by remote in the Branch filter.
  * Branch refs use the IDE's VCS colors for easier navigation.
* Create new jj commits
  * Includes support for committing partial hunks
* Annotate (blame) files

See the [changelog](changelog.md) for the complete release history.

## Planned features

* Support advanced commit features
  * Amend
* Editing changes - reword, abandon, split, merge and so on
* Bookmark support
* Repository creation/import
* Multiple working copies
* Multiple .jj repositories per project