# Test
This is *just* a **test**.
Basic syntax for a markdown file can be found [here](https://www.markdownguide.org/basic-syntax/). 

## Writing a Readme 
A Read me file should:
<ul>
  <li>List the contents of the repository.</li>
  <li>Need to be descriptive so that anyone can understand our project.</li>
</ul>
It should include: 
<ul>
  <li>Title</li>
  <li>Desciption of the technology</li>
    <ul>
      <li>And why</li>
    </ul>
  <li>Desciption of the process</li>
    <ul>
      <li>And why</li>
    </ul>
  <li>Table of contents</li>
</ul>
Extras in a readme are:
<ul>
  <li>How the project came about</li>
  <li>The motivation</li>
  <li>Limitations</li>
  <li>Challanges</li>
  <li>What the problem it hopes to solve</li>
  <li>What the intended use is</li>
  <li>Credits if other sources are used</li>
</ul>

## Branches
<ul>
  <li>Enable concurrent work on different parts of a project</li>
  <li>Help reduce the risk of conflicting file verions</li>
  <li>Makes sense if multiple people want to work on different tasks at the same time</li>
</ul>

Branch protection rules 
<ul>
  <li>Rules for specific branches</li>
  <ul>
    <li>Require a pull request before merging</li>
    <li>This adds a layer of protection against bringing incorrect code into the main branch</li>
    <li>Requie that pull request are approved before merging</li>
    <li>Restrict who can delete a protected branch</li>
  </ul>
  <li>To edit the settings, go to settings and there in the "Code and automation" section choose Branches</li>
</ul>

## Authentication
We can use Git in the terminal to interact with GitHub
<ul>
  <li>git clone followed by the url </li>
  <li>git will then ask for a username and password</li>
  <li>However, we actually need to provide a personal access token PAT</li>
  <li>PATs are required since August 2021 when we want to access a remote repo using the terminal</li>
</ul>

## Using other repos 
Cloning 
<ul>
  <li>Similar to copy-paste, however cloning creates a link to the original repo</li>
  <li>Creates a copy on a local comnputer</li>
  <li>Allows updates to go back and forth using Git</li>
</ul>
Forking
<ul>
  <li>We can copy without linking to the original repo </li>
  <li>Forking creates an independet copy: We can experiment without risk</li>
  <li>Anyone can fork a public repo</li>
  <li>Subit changes with a pull request</li>
</ul>
Cloning creates a linked copy on a local computer, forking creates an independet copy on GitHub.
Cloning works using Git while forking can all be done within GitHub. 
Issues 
<ul>
  <li><Messages to help track problems fixes, plans, task and other project communication </li>
    <li>Issues use markdowns</li>
    <li>We need to assigne or tag someone to make them aware of the issue</li>
    <li>Use # symbol to link to another issue </li>
    <li>You can respond to issues in the form of comments to keep the conversation going and ask or answer any questions from your team. Use > symbol</li>
</ul>

# Pull Requests 
What is a PR?
<ul>
  <li>A way to notify others about changes</li>
  <li>Allows the repo owner to check changes before they are added</li>
  <li>Best practice to add changes to a branch that is not the main branch. This ensures that main only contains finished work</li>
  <li>A successful PR is merging two branches</li>
</ul>
How to create a PR:
<ul>
  <li>In the forked repo go to the Pull request section and click on New pull request</li>
  <li>Base branch: the branch we want to add our updates to</li>
  <li>Comapre branch: contains our changes</li>
</ul>
Reviewing pull requests
The assignee apporves the PR. The Reviewer looks at the changes before the PR is merged.
<ul>
  <li>In the Pull request section click on Files Changed</li>
  <li>Red indicates removal</li>
  <li>Green indicates an addition</li>
  <li>Click on Review changes</li>
  <li>We can add comments or questions by clicking on the plus icon.</li>
  <li>We can:</li>
    <ul>
      <li>Comment only: For feedback or suggestions that do not require a change.</li>
      <li>Comment and approve</li>
      <li>Comment and request changes: For feedback that needs to be incorporated</li>
    </ul>
  <li>Once a branch has been merged it is good practice to delete that branch. Note: we have the option to restore a branch once it has been deleted</li>
</ul>


