# Beginning Open Source Programming

This guide is primarily focused on beginning contributions to Python open
source projects because that is where I have experience.

# Git/Github

Github is one of the most common places to find open source repositories and one
of the easiest ways to contribute. As such this is the first step to learn
towards open source programming contributions. Below is a series of two videos,
the first describes how to use git the tool and the second describes how to
interact with Github the site.

In the videos he mentions the Github desktop client. I would recommend against
using the and use the command line interface instead.

1. [Github YouTube Tutorial](https://www.youtube.com/watch?v=0fKg7e37bQE)
1. [Github YouTube Tutorial 2](https://www.youtube.com/watch?v=oFYyTZwMyAg)

# Obtain Git

If your machine does not yet have git, it is easy to acquire. On windows follow
this [guide](https://git-scm.com/downloads). On mac or linux, if you try to use
a git command before git is installed, your system will suggest a command that
you can use to acquire git.

# Git SSH Keys

In order to be able to push and pull to your repositories without having to
enter your password every time you need to set up ssh keys with github. Github
has a useful
[guide](https://help.github.com/articles/connecting-to-github-with-ssh/) for
setting up ssh keys. Once you have ssh set up make sure you use the ssh link
for your `git clone` statement.

> _Warning_: When you are generating the ssh keys make sure to use the same
> email that is associated with your github account

# Find a project to which you'd like to contribute

Choose a topic you like or something that is meaningful to you. You'll be more
likely to stick with it and you'll learn more. Once you find a project clone it
to your local machine and use the `python setup.py develop`. By using the
`develop` option instead of `install` your python instance will use the git
repo version of the code rather than copying it internally. This means as you
work in the git repository you do not have to reinstall the code to see the
changes take effect.

> _Note:_ If `setup.py develop` is not working it may be that setup.py is using
> distutils instead of setuptools. You can try just changing them in the import
> statement to get it to work.

# First Contributions

When you find your project the first steps will be to read through the
documentation to familiarize yourself with their contribution process, any
standards they use and generally how the code works. I would recommend writing
down any and all spelling and gramatical errors you find while reading. When
you finish reading you can go in and create a pull request to fix all of the
errors you have found. This is a great way to make a first contribution, meet
your fellow contributors and get your feet wet with the contribution process.
