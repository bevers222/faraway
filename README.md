# ![faraway](https://raw.githubusercontent.com/bevers222/faraway/master/resources/faraway.png)
[![GitHub stars](https://img.shields.io/github/stars/bevers222/faraway.svg?style=social&label=Star)](https://github.com/bevers222/faraway)
> Quickly search for and jump to directories in a git repository

---

![faraway usage example](https://raw.githubusercontent.com/bevers222/faraway/master/resources/faraway.gif)


## What is farway?
Have you ever been several folders deep in a repository and you needed to cd all the way up and into another directory? ex: cd ../../../../dev

faraway is a tool that lets you search a git repository for a folder and switch to it from a simple menu!

## Quick Start
1. Clone this repository

    `git clone https://github.com/bevers222/faraway.git`
2. Source the script in your .bash_profile by adding this line to your .bash_profile

    `source ~/path/to/repo/faraway/faraway`

3. Remember to source your .bash_profile so you can use the new tool by running this command in your terminal window

    `source ~/.bash_profile`

4. Profit

## Usage
The base command is `far`

`far` - move you to the git repository's root directory

`far [dirtosearchfor]` - search the git repository and give you a menu based on results

Use the Up or Left arrow to move up the list

Use the Down or Right arrow to move down the list

## Additional Information
This is the first version of this tool. It was built and tested in iTerm2 on macOS with bash 5.0.2. I don't know specifically where it will not work, so try it out! Additional support for different terminals and OS is coming! 

It's a work in progress. I'm not fluent in bash. If you want to help me do things better and improve this tool, submit a PR! I love new ideas.

faraway was inspired by another great tool [bitcar](https://github.com/carsdotcom/bitcar) - allows you to seamlessly jump between repos from your command line. I highly suggest checking it out!
