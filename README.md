# Empty_42School_Project

This repository is an empty project for [42School](https://42.fr/) Project. It has some useful things ready to use for any 42project:

 - Ready to use unitest for your project;
 - Makefile rules to debug with `lldb`, `sanitize` or `leaks`;
 - Makefile to check leaks;
 - Refresh makefile files list with [Sublime 42 tools](https://github.com/GlaceCoding/sublime-42-tools#in-action-);
 - Deployment script to make a rendered project for Moulinette & defense (this script will ignore all debug & test file for your last pull request) `sh ./hooks/deploy`.

**Example of rendered project generated by the deployment script:** [git@github.com:GlaceCoding/Empty_42School_Project_vogsphere.git](https://github.com/GlaceCoding/Empty_42School_Project_vogsphere)


**Goal of the deployment script:** Have on repository for github and vogsphere (intra 42), and be able to push with only one command.

You can get more explanation about the deployment script here: [hooks/README.md#script-deploy](https://github.com/GlaceCoding/exemple_rendu/tree/main/hooks#script-deploy)  


# Init step

## 1) Add vogsphere

Add vogsphere remote with `git remote` :

```sh
git remote add vogsphere git@github.com:GlaceCoding/Empty_42School_Project_vogsphere.git
```

