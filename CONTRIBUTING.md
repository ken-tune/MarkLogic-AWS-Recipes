# Contributing to cloud-watch-for-marklogic

Thanks for taking an interest in this project. Although it's just a one man effort currently I'd like to support those using it as best I can, and also welcome contributions and ideas.

This document goes through how you can get those ideas/bugs/patches etc to me.

 - [Question or Problem?](#question)
 - [Issues and Bugs](#issue)
 - [Feature Requests](#feature)
 - [Submission Guidelines](#submit)
 
## <a name="question"></a> Got a Question or Problem?

If you have a question contact me personally at <a href="mailto:ken.tune@marklogic.com">ken.tune@marklogic.com</a>

## <a name="issue"></a> Found an Issue?
If you find a bug in the source code or a mistake in the documentation, you can help by
submitting an issue to the [GitHub Issue Tracker](https://github.com/ken-tune/cloud-watch-for-marklogic/issues). Even better you can submit a Pull Request
with a fix for the issue you filed.

## <a name="feature"></a> Want a Feature?
You can request a new feature by submitting an issue to the [GitHub Issue Tracker](https://github.com/ken-tune/cloud-watch-for-marklogic/issues).  If you
would like to implement a new feature then first create a new issue and I'll be in touch.

## <a name="submit"></a> Submission Guidelines

### Submitting an Issue
Before you submit your issue search the archive, maybe your question was already answered.

If your issue appears to be a bug, and hasn't been reported, open a new issue.
Help maximize the effort spent fixing issues and adding new
features, by not reporting duplicate issues.  Providing the following information will increase the
chances of your issue being dealt with quickly:

* **Overview of the Issue** - if an error is being thrown a stack trace helps
* **Motivation for or Use Case** - explain why this is a bug for you
* **AWS instance details** - OS/region/python version
* **Suggest a Fix** - if you can't fix the bug yourself, perhaps you can point to what might be
  causing the problem (line of code or commit)

### Submitting a Pull Request

#### Forking

Fork the project [on GitHub](https://github.com/ken-tune/cloud-watch-for-marklogic/fork) and clone
your copy.

```sh
$ git clone git@github.com:username/cloud-watch-for-marklogic.git
$ cd cloud-watch-for-marklogic
$ git remote add upstream git://github.com/ken-tune/cloud-watch-for-marklogic.git
```

All bug fixes and new features go into the dev branch.

I'd ask that you open an issue in the [GitHub Issue Tracker](https://github.com/ken-tune/cloud-watch-for-marklogic/issues) and get in touch with me before coding, if it's anything of substance.

#### Create a branch for your changes

Okay, so you have decided to fix something. Create a feature branch
and start hacking:

```sh
$ git checkout -b my-feature-branch -t origin/dev
```

#### Commit your changes

Make sure git knows your name and email address:

```sh
$ git config --global user.name "J. Random User"
$ git config --global user.email "j.random.user@example.com"
```

#### Test your code

Obviously!

#### Push your changes

```sh
$ git push origin my-feature-branch
```

