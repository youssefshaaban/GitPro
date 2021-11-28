##Git
Git is a `free and open source` distributed version control system designed to 
handle everything from small to very large projects with speed and efficiency

##git glow
Giflow is an alternative Git branching model that involves the use of feature branches and multiple primary branches.
It was first published and made popular by `Vincent Driessen at nvie`. Compared to trunk-based development,
Giflow has numerous, longer-lived branches and larger commits. Under this model, developers create a feature branch and delay merging it to the main trunk branch until the feature is complete. These long-lived feature branches require more collaboration to merge and have a higher risk of deviating from the trunk branch. They can also introduce conflicting updates.
`benefits of git flow`

##Git Rebase
## Usage
- The primary reason for rebasing is to maintain a linear project history. 
  For example, 
  consider a situation where the main branch has progressed since you started working on a feature branch.
  You want to get the latest updates to the main branch in your feature branch, but you want to keep your branch's history clean so it appears as if you've been working off the latest main branch. This gives the later benefit of a clean merge of your feature branch back into the main branch
