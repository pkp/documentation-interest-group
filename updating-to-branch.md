# Branches and GitBook

In prep for OJS 3.1 release, we'll be updating our documentation while also explicitly focusing on versions of existing docs. GitBook and GitHub make it possible to use branches for documentation. The way that works, is that we can identify specific branches of a doc and update them individually, while working on a broader "master" branch for current doc updates. 

Take "Learning OJS" for example. There's a github directory for the book now, and you if you click on the "branch" icon, you can see that it has multiple branches. 

![branches in github]()

The same is true for GitBook. When editing, we can see that a GitBook has multiple branches. You simply select which branch you want to edit and make your changes. The version of the book you're updating will receive the changes you make. 

![branches in gitbook]()

## "master" vs "branch"

Ideally, we'll create new branches for documentation whenever we release a new major 0.1 stable version of OJS. This means that we'll end up with slightly different docs for: 

- 3.0
- 3.1
- 3.2
- 3.3 
- and so on... 

The first branch we have in our Learning OJS doc is 3.0.2. This is a little weird because we didn't use branches before this point. It's simply the first branded branch we have had for the software. 

**Which branch do I edit?**

If you are working for documentation for OJS 3.1, make those changes to the "master" branch of the GitBook. You can direct people to the 3.0.2 documentation with this link: https://pkp.gitbooks.io/ojs-user-guide/content/v/ojs-stable-3_0_2/en/ 

Once we release OJS 3.1 and our documentation is up to date, we'll create a 3.1 branch and use the master branch for continued updates as we go. The 3.1 Branch will become the official 3.1 release doc. 

By pairing book releases against releases of the software, we'll have more easily tracked versions of our books for folks who are using older versions. It also means that we can largely retire some of the language of our separate books per version. Learning OJS 3 can simply be "Learning OJS" and we can link to the individual versions if necessary.
