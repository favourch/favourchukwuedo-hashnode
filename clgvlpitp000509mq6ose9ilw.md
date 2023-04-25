---
title: "Supercharging Your Node.js Workflow: A Humorous DIY on Switching to pnpm"
datePublished: Tue Apr 25 2023 01:41:17 GMT+0000 (Coordinated Universal Time)
cuid: clgvlpitp000509mq6ose9ilw
slug: supercharging-your-nodejs-workflow-a-humorous-diy-on-switching-to-pnpm
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682386554065/48a5f686-4c45-472b-aec1-e22c57810a2f.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1682386853485/cd97f1cc-49ba-4292-a7ee-0fa910e778b3.jpeg
tags: workflow, nodejs, npm, diy, pnpm

---

Let's face it, waiting for npm to install packages can feel like watching paint dry. And if you're like me, you've probably wondered if there's a better way. Well, my friend, wonder no more! Enter **pnpm**, the package manager that's here to save the day.

With pnpm, you can say goodbye to sluggish installs and hello to a streamlined workflow. And let's not forget the best part: you get to say "pnpm" out loud and feel like a tech superhero. So, are you ready to take your Node.js development to the next level? Join me on this DIY journey to switch to pnpm!

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682363044587/8123cb13-b408-4a2d-a20e-360a893cb72c.png align="center")

**Npm** is like the dependable sidekick that's been around for ages. It's always there when you need it, ready to install packages with a simple command. But let's be real, sometimes npm can be a bit slow and bloated. It's like that friend who always takes forever to get ready before a night out.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682362976575/0add59f0-3de0-4048-8bbe-46ed6991375c.png align="center")

Then, there is **pnpm**, the flashy new superhero on the block. It's like the Flash, speeding through the installation process with lightning-fast efficiency. But don't be misled by its youthful energy, pnpm has some serious tricks up its sleeve. It uses a shared package store to save disk space and installation time, making it perfect for those large projects with tons of dependencies. <mark>Think of pnpm as your trusty sidekick, streamlining your workflow and making your development experience all the more joyful</mark>

But even with all its benefits, pnpm still has some skeptics. Some developers are hesitant to make the switch, afraid that they'll be left in the dust by the tried-and-true npm. It's like that classic car that you're afraid to sell, even though it's been sitting in your garage collecting dust for years.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682362868672/ba2a5d40-31be-4b44-a8c5-a8214e9c0083.jpeg align="center")

But fear not, dear developer! You don't have to choose between npm and pnpm, they can coexist peacefully in your development world. You can start using pnpm for your new projects and gradually transition your older ones. It's like a blended family, bringing together the best of both worlds and creating a happy, harmonious home.

## **Technical Details**

  
Alright, let's dive into the technical details and walk through the steps of setting up **pnpm** for a Node.js project.

### Step 1: Install pnpm

To install pnpm, run the following command in your terminal:

`npm install -g pnpm`

This will install pnpm globally on your machine, making it available for use in any project.

### Step 2: Initialize your project

Create a new directory for your project and navigate to it in your terminal. Then, run the following command to initialize a new Node.js project:

`npm init`

This will prompt you to enter some information about your project, such as its name, version, and description. Once you've entered all the required information, a package.json file will be created in your project directory.

### Step 3: Install dependencies with pnpm

To install dependencies for your project using pnpm, run the following command:

`pnpm install`

Replace `<package-name>` with the name of the package you want to install. Pnpm will download and install the package and its dependencies, and save them to a shared package store on your machine.

### Step 4: Use pnpm instead of npm

Now that you've installed pnpm and initialized your project, you can start using pnpm to manage your dependencies. To do this, simply replace any `npm` commands with `pnpm`.

**For example:**

`npm install express`

**Becomes:**

`pnpm install express`

And that's it! You're now using pnpm to manage your Node.js project dependencies. You can continue to use pnpm for all future package installations or switch back to npm if you prefer. Remember, pnpm and npm can coexist peacefully, so feel free to use whichever tool works best for your project.

### One last thing to note:

*<mark>If you're working on an existing project that already has a </mark>* `node_modules` *<mark>directory, you can migrate to pnpm by running the following command:</mark>*

`pnpm install --shamefully-flatten`

This will copy all the packages and their dependencies to the shared package store, allowing you to take advantage of pnpm's space-saving benefits. And don't worry, the original `node_modules` directory will still be there, just in case you need to switch back to npm.

pnpm is a powerful package manager that can help simplify and speed up your Node.js development workflow. With its shared package store and efficient installation process, pnpm can save you time and disk space, while still allowing you to manage your project dependencies with ease.

### Conclusion

While npm has been the go-to package manager for Node.js developers for many years, pnpm offers some significant advantages that are worth considering. Whether you're working on a new project or migrating an existing one, pnpm is worth exploring.

So why not give pnpm a try? With just a few simple commands, you can start using this powerful tool to supercharge your Node.js development experience. And who knows, you might just find that pnpm becomes your new superhero package manager.