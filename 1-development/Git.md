# Git

## What is Git?
[Git](https://en.wikipedia.org/wiki/Git) is a version control system widely used in software development.

## Installation
Pop on over to [git-scm.com/downloads](https://git-scm.com/downloads) to find download/installation information for all your favorite operating systems. On Windows, ther is an installation `.exe` available - download and tun that (btw, all the default setting are a-okay). If you're on MacOS or Linux, you may need to have a package manager (ex. `apt` on Linux or `brew` on MacOS) installed - or build from source. If either of those options sounds unknown and scary, reach out to your team lead and we can help you get set up.

Once you've gone through all the installation steps, you can verify you've set up _git_ correctly by running the command `git --version` from the terminal/console. If you see a version number that means you're good to go.

## GitHub Authenitication
In order to secure code/files, GitHub has to autheniticate both you and you're computer. There are a number of ways in which they do this (for an overview of GitHub's authentication methods, see [docs.github.com/en/authentication](https://docs.github.com/en/authentication)). Feel free to set up authentication in whatever way you like; however, in this tutorial I'll walk you through how to do it using SSH keys.

### SSH Keys
For a more infromation, and a detailed look at how to setup and manage your SSH keys, see [docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh). However, for the sake of brevity, I will outline the main steps here:

1. To generate an SSH key on your local computer, run the following command from a terminal/console. It'll ask you for a location & passphrase, but just hit enter to skip these (tbh you don't really need a password, it just gets more frustrating than is helpful later on). If you've already done this in the past, you can skip this step (to check if you've done this before, run `ls ~/.ssh` on Linux/MacOS or `dir ~/.ssh` on Windows and if you see a `id_rsa.pub` file then that means you've previously generated an SSH key).
  ```shell
  ssh-keygen
  ```
2. Once generated, we need to get your generated _public key_. To do this run the following commands, and copy the resulting string (it'll be a bit of doozy) to your clip-board (if you haven't yet I highly recommend enabling clip-board history with `Windows`+`v` - sorry Linux/MacOS users idk if there's an equivalent).
  ```shell
  cd ~/.ssh
  cat id_rsa.pub
  ```
3. Once you've got your key, head over to your GitHub's account settings and navigate to [SSH and GPG keys](https://github.com/settings/keys). Here, click on _New SSH Key_ and paste the key you copied earlier. Now you should be all set. Remember when cloning repositories to now copy the _SSH_ link rather than _HTTP_. Happy git-ing!

## Popular Commands
Here I've included a few of the most useful git commands, one's that you will likely use quite often. For a full list of commands and their details, visit [git-scm.com/doc](https://git-scm.com/doc) or run `git --help` from your terminal/console.
