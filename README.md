# This is Oleks' fork of the League's curriculum website.

This repo is used to validate changes to the curriculum website in as close of an environment as possible.

## How to use this repo

1. Implement changes in a topic branch.
1. Merge changes into `main`.  
1. Merge `main` into `hosted` and validate the changes at [staging.templeague.com](http://staging.templeague.com/)
1. Create Pull Request to merge this repository's `main` branch into the upstream repository's `master` branch.
1. Once the PR is approved and merged, all done!


## Important Branches

### `hosted` 
This is the branch that is hosted on github pages.  
It has changes to CNAME and this README.md and therefore must NEVER be merged into any other branch.

### `main`
This is the branch that mirrors the state of the `master` branch on the upstream repository.


## TODO
- Rename main to mirror
- Set up auto-merges
  - Merge `main` into `hosted`
  - Merge upstream/master into main
