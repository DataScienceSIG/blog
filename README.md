# What this repository contains
A blog from the PSI DS SIG.

# How we work
We are using a branching model that requires:
- a main branch (protected - pull request requires 2 reviews), which always contains a working copy of the blog; this branch is used to deploy the website
- a test branch (protected), which always contains a working version of the code; we use this branch to test that everything is working before publishing the posts
- a lot of feature branches, which get created to add blog posts/specific features through pull requests and get closed when the merge is complete
