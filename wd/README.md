# Web design

## Instructions
1. In your terminal, do `git clone git@github.com:hstatsep/wd.git` to clone this repository
2. In your terminal, do `cd wd` to get into the `wd` folder
3. In your terminal, do `rm -rf .git` to "turn off" git in this folder.

## Files/Folders
* `classwork` is a folder for organizing classwork, assignments, etc.
* `projects` is a folder for your when you want to make something large
* `sandbox` is a folder for when you want to try something small (and keep it)
* `templateFile.html` is a standalone template file to duplicate in order to practice small concepts
  * to duplicate, use either:
    * `cp templateFile.html sandbox/newFileName.html`
    * `cp templateFile.html classwork/newFileName.html`
* `templateFolder` is a template folder to duplicate in order to make large projects
  * to duplicate, use `cp -r templateFolder projects/newProjectName`

## Previewing HTML
* Make sure you are in the folder of the file you want to preview, then run `http-server`
* You will see something that looks like this:
```bash
Available on:
  https://username-code50-12345678-7c3q5t9qyxgr3-8080.githubpreview.dev
Hit CTRL-C to stop the server
```
* To open that link:
  * On a Mac: <kbd>COMMAND</kbd>+**click**
  * On a Windows/Chromebook: <kbd>CONTROL</kbd>+**click**
* Then click on the file you want to preview.
* As it says, press <kbd>CONTROL</kbd>+<kbd>C</kbd> to stop the server
