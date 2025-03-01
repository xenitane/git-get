# git-get

> fetch the specific content from a git repo

## Motivation

I've been a long time git user, and there are times when all you want to do is not clone the whole repository but just some specific files and(or) directories from the repository but for that there is no direct tooling which is easy to wrap your head around.

So..., I decided to bite this bullet, read the git-manual and make a bash script that will achieve this, though it is a bit rough around the edges, it functional.

## Features

- Clear flags for selecting what you want to checkout, be it a branch, tag or a specific commit.
- Flag for setting a desired output directory.
- Select file(s) using glob patterns that you want to fetch.
- Independent of the git service provider.
- Works with both git over ssh and http(s).
- Single bash script implementation, which means that you can rename this script to whatever you like while install.

## Installation

1. Copy the `git-get` file in the in any directory on your system that's available on the `PATH` variable, see reference [here](https://en.wikipedia.org/wiki/PATH_(variable)).
2. Change the permisions of the file to make it executable like `chmod a+x <path>/<to>/git-get`.
3. Optionally you can rename the file `git-get` to whatever that fits your taste.

And now you have this utility installed on your system ready to use.

## Usage

Try running the script directly without any flags and it will print the help message.

[License](LICENSE.MD)
