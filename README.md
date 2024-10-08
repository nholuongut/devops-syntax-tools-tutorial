# DevOps syntax for all Programming Languages and Developer Tools with Sublime Text - Text Editing

We recommend you to visit Docker Roadmaps in order to find the learning path for your career in the future

![](https://i.imgur.com/waxVImv.png)

# Roadmaps are now interactive, you can click the nodes to read more about the topics.

### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)

![](https://i.imgur.com/waxVImv.png)


## Installation

To make changes to these packages and test them locally, fork this repository. Then symlink the changed packages into your [`Packages`](https://www.sublimetext.com/docs/packages.html) folder. (Replace `Python` in the following commands with the name of the syntax to install.)

### OS X

```bash
$ git clone https://github.com/nholuongut/devops-syntax-tools-tutorial.git
$ ln -s `pwd`/Packages/Python ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
```

### Linux

```bash
$ git clone https://github.com/nholuongut/devops-syntax-tools-tutorial.git
$ ln -s `pwd`/Packages/Python ~/.config/sublime-text-3/Packages/
```

### Windows

On Windows, you can use directory junctions instead of symlinks (symlinks require administrative rights; directory junctions don't):

```powershell
# Using PowerShell
PS> git clone https://github.com/nholuongut/devops-syntax-tools-tutorial.git
PS> cmd /c mklink /J "$env:APPDATA/Sublime Text 3/Packages/Python" (convert-path ./Packages/Python)
```

Alternatively, download the portable version and clone this repository directly as a subdirectory of the `Data` folder.

### ⚠️ Things to keep in mind

After you've finished, keep in mind that you're now overriding a default package.
If other people make upstream changes to an overridden package, yours will be out-of-date when Sublime Text updates to a new version. To get the latest version, pull the changes from this repository.

## Reference

Please refer to the official documentation:

* [Syntax definitions](https://www.sublimetext.com/docs/syntax.html#ver-dev)
* [Scope naming](https://www.sublimetext.com/docs/scope_naming.html)

## Pull Requests

Pull requests should:

 1. Start with the name of the package in square brackets, e.g. `[XML]`.
 2. Be as small and self-contained as is reasonable. Smaller changes are quicker to review.
 3. Include a new (or enhanced) [syntax test](https://www.sublimetext.com/docs/syntax.html#testing) when changing a `.sublime-syntax` file.
 4. Have multiple syntax tests and a set of performance measurements (old vs. new) when making significant changes.

### New Packages

Pull requests for new [packages](https://www.sublimetext.com/docs/packages.html) won't be accepted at this stage, as new packages can cause issues for users who have a package with the same name installed via [Package Control](https://packagecontrol.io/).
There are some planned changes that will address this in the future.

Complex plugins such as auto complete systems and linters should generally be in a stand-alone package, rather than included in the default set of packages.

## Missing Packages

This repository only contains syntax-definition-focused packages.
Notably, packages such as `Default` and `Theme - Default` are not included.


I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com) 

![](bitfield.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.
