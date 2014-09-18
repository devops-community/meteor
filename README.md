# Builder for Meteor based apps

Build and deploy [Meteor](http://docs.meteor.com/) based apps.

## Install

Simply use the link below:

[![Fork on devo.ps](https://app.devo.ps/assets/images/fork.png)](https://app.devo.ps/#/fork?git_url=https://github.com/devops-community/meteor.git)

Once you've forked the repository, open it in devo.ps and you will be prompted for a few settings, including the Git URL for the code of your application, the names of your application and database.

To deploy your app, you will need to navigate to the tasks page of the repo and run the task manually (click on "play" icon, right of the "Build Meteor app" task).

## What's in the box?

This setup contains one server (`nodes/meteor.yml`) with **Node.js**, **Meteor**, **MongoDB** and **Nginx**

We have included as well a task (`tasks/meteor-build.yml`) that can be executed and will deploy your Meteor app.

The current repo provides a very simple setup. Hack at will!

Feel free to extend the task and add the support for webhooks to install any kind of Meteor app! Checkout the [gh-pages builder](https://github.com/devops-community/gh-pages) for some examples.

## Questions?

If you have any question, come ask us on the [devo.ps chat](https://www.hipchat.com/gyHEHtsXZ) or shoot us an email at [help@devo.ps](mailto:help@devo.ps) (though, you should really just [ask us in the chat](https://www.hipchat.com/gyHEHtsXZ)).

# Reference

- [Nodes in devo.ps](http://docs.devo.ps/manual/nodes)
- [Tasks in devo.ps](http://docs.devo.ps/manual/tasks)
