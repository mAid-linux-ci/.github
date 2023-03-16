# About

Often enough it happened in the past that packages in the AUR broke (for various reasons). When that happens a mAid build will fail until the package maintainer fixed his/her package (which can take days, weeks and yes not unlikely even months).

Besides that it is needed sometimes to mod an AUR (or official) package to make it fully working in mAid.

For those reasons above automation is needed to handle that. The idea is to include more and more packages I use in mAid here, automate syncing them upstream and rebasing needed changes on top. That way we do not depend on a needed change by a third party anymore.

For the automation tasks Ansible (+Semaphore) is used. Why:

- I abandoned Jenkins some time ago (and I am so still sooooo happy that I did) 
- github actions are too complicated for the things I need to do for mAid 
- github actions costs MONEY (when using it a lot)
- last but not least because Ansible just works

Read all about my reasons for movin away from Jenkins and the implementation itself [here](https://github.com/sfX-android/automation_scripts)
