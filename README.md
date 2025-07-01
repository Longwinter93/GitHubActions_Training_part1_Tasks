# GitHub Action Training Part 1 - Basic Building Blocks & Components - Tasks
<br>All steps are described in yaml files in .github/workflows directory.
<br>We simply learn about Basic Building Blocks & Components related to GitHub Action.
<br>We learn also about GitHub Context & Expressions.
<br> We need to create two workflows:
<br>1. First workflow that runs lint, test and build scripts. A workflow consists of one job and a few jobs was created. We can test it locally, then we can put all commands on a workflow
<br>2. Second workflow that is triggered by an issues event. It is necessary to use a github context and use shell via echo
