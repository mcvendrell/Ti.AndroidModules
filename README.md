# Ti.AndroidModules
Compiled Android modules for Appcelerator Titanium

I'm seeing continuously people asking for a specific version of a compiled Android module for a specific Ti SDK version (no all Ti devs know how to compile a module).

In our Slack Titanium group ([https://ti-slack.slack.com](https://ti-slack.slack.com)) some people do some special compilations very useful for others, but are all lost in time after then, so I decided to do here a compilation.

You can find here some newest versions of the original modules and even special compiled packages with modified jars to solve temporary issues until a fix to the original arrives (this can represent some months...).

# Latest/"Nighty" Titanium builds
The official released SDKs are all finished in *GA* and you can get the latest with the CLI command `appc ti sdk install`, but if you want to use versions in development, you can download it from http://builds.appcelerator.com

# Collaborating: upload your packages
If you have some of this packages and want to share it, you can do a pull request: fork this project, add your ZIP file to the right folder and ask for the PR.
You even don't need to use git to do this task and upload the files. You can do it all through GitHub easily with 3 simple steps:

1. Click create new file button
2. Set "title" of the file as files/ProjectName/readme.md
3. Fill readme info
4. Click "upload file" and set the commit info

The folder structure I've thought is:

```text
Ti.AndroidModules
|-files
|--projectname
|---readme.md to show the path to the original project and a brief copy&paste from original project of what does this module.
```
