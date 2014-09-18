# Builder for gh-pages

Build and deploy a simple setup to build your static site and push the build back to GitHub pages on [devo.ps](http://devo.ps).

## Install

Simply use the link below:

[![Fork on devo.ps](https://app.devo.ps/assets/images/fork.png)](https://app.devo.ps/#/fork?git_url=https://github.com/devops-community/gh-pages)

Once you've forked the repository, open it in devo.ps and you will be prompted for a few settings, including the Git URL for the code of your application.

To deploy your app, you will need to navigate to the tasks page of the repo and run the task manually (click on "play" icon, right of the "Build Laravel app" task).

## What's in the box?

This setup contains one server (`nodes/build-server.yml`) with **Node.js** (with [Bower]() and [Gulp]())

We have included as well a task (`tasks/gh-pages-build.yml`) that will be executed when GitHub sends a webhook:

1. Clone your to-be-compiled site from GitHub.
1. Execute your `make build` to generate the site
1. Commit and push the built version over to the `gh-pages` 

The current repo provides a very simple setup. Hack at will!

## Questions?

If you have any question, come ask us on the [devo.ps chat](https://www.hipchat.com/gyHEHtsXZ) or shoot us an email at [help@devo.ps](mailto:help@devo.ps) (though, you should really just [ask us in the chat](https://www.hipchat.com/gyHEHtsXZ)).

# Reference

- [Nodes in devo.ps](http://docs.devo.ps/manual/nodes)
- [Tasks in devo.ps](http://docs.devo.ps/manual/tasks)
