# Project Management
Repository for Managing various projects within the XChem group.
The main project board will house a list of projects within the XChem group and project convenient links to the specific repositories and corresponding project boards which should be used for bug and feature requests (and discussion).

## Non-Developer (Frank's) Instructions

1. Submit a new project/issue using the `Add a brand NEW Project (one that needs creating)` template: 

[Click Here Frank!](https://github.com/xchem/ProjectManagement/issues/new?assignees=&labels=PROJECT+-+NEEDS+INIT&template=add-a-brand-new-project--one-that-needs-creating-.md&title=%5BNEW+PROJECT%5D)

2. Follow the steps, assigning people and giving a highly indepth description of what is required of the project

3. We may have to assimilate the NEW project into other projects, so please consider if this is in fact a new project OR merely a feature request for an existing project then please go to existing project board and follow the issue requests there.

## Developer Instructions

1. Create a new repository using the [xchem/TemplateRepo](https://github.com/xchem/TemplateRepo) OR use an existing repo that you would like to add to the main project. Ensure it has it's own project board for it's own feature requests and bug reports. 

2. (Optional) If not using the template add the `ISSUE_TEMPLATE` from `AdditionalFiles` folder to the `.github` folder into the root of your git repo. So your git repo contains the following:
```
reponame/.github/ISSUE_TEMPLATE/bug_report.md
reponame/.github/ISSUE_TEMPLATE/feature_request.md
```

This will add a standardised set of Issue Templates we will use across the group.

3. [Submit issue to this repo](https://github.com/xchem/ProjectManagement/issues/new?assignees=&labels=PROJECT&template=add-project-from-existing-repository.md&title=%5BPROJECT%5D). Please follow all the steps in the template. Link urls to the existing git repo, the corresponding project board, assigning people who are working on this project and providing a brief overview of the project. 

## Once a Issue is submitted

1. Ensure all links are correctly set-up

2. Discuss/clarify the specifications in the project if required.

3. Assign additional members and outline steps required (these can become individual features/bug reports by referencing comments and linking to the corresponding git repos

4. If handling a `PROJECT - NEEDS INIT`, either alter the issue to be mirror what the existing project look like, or close, link and archive the old issue into a new issue following developers instructions.

## Last Steps:
Go to the [Main Projects Board](https://github.com/orgs/xchem/projects/1) and move the card to whereever it needs to go in from triage.
