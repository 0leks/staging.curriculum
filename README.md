# Oleks' fork of the League's curriculum website.

This repo is used to validate changes to the curriculum website in as similar of an environment as possible.

## How to use this repo

1. Implement changes in a topic branch.  
1. Validate locally by hosting the website using `python -m http.server 80`  
1. Make a Pull Request to merge changes into `mirror` and add reviewers.  
1. Wait for automatic merge of `mirror` into `hosted` and validate the changes at [staging.templeague.com](http://staging.templeague.com/)
1. Create Pull Request to merge this repository's `mirror` branch into the upstream repository's `master` branch.
1. Once the PR is approved and merged, all done!


## Important Branches

### `hosted` 
This is the branch that is hosted on github pages.  
It has changes to CNAME and this README.md and therefore must NEVER be merged into any other branch.

### `mirror`
This is the branch that mirrors the state of the `master` branch on the upstream repository.


## TODO
- Set up auto-merges (https://www.jessesquires.com/blog/2021/10/17/github-actions-workflows-for-automatic-rebasing-and-merging/)
  - ~~Merge `mirror` into `hosted`~~
  - Merge upstream/master into mirror
