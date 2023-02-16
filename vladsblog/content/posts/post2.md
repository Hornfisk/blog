---
title: "Getting the hang of the workflow"
date: 2023-02-16T22:49:21Z
draft: false
---

After many trials and tribulations, it appears that I've managed to set up SSH authentication with GitHub, and also hardcoded main (instead of master) branch.

The workflow currently looks something like this:

'''
hugo newposts/[posttitle].md

subl [posttitle].md
'''

edit and save as needed, then from the root folder in the local blog repo:

'''
git add .

#checking if staged correctly
git status

#checking if pushing to the correct branch
git branch

#if yes, then:
git commit -m "comment here"

#and, at last:
git push origin main
'''

Now let's try and put this in practice and push and update that contains this actual post right here.