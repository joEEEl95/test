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
