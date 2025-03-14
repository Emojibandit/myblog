# How to contribute
I like to encourage you to contribute to the repository.

This should be as easy as possible for you but there are a few things to consider when contributing. The following guidelines for contribution should be followed if you want to submit a pull request.

## How to prepare
<ul>
  <li>You need a <a href="https://github.com/">GitHub account</a> </li>
  <li>Submit an issue ticket for your issue if there is no one yet.
    <ul>
     <li>Describe the issue and include steps to reproduce if it's a bug.</li>
     <li>Ensure to mention the earliest version that you know is affected.</li>
  </li>
    </ul>
  <li>If you are able and want to fix this, fork the repository on GitHub</li>
</ul>

## Make Changes
<ul>
  <li>In your forked repository, create a topic branch for your upcoming patch. (e.g. feature/new-backend or 
    bug/auth-fails)
    <ul>
       <li> Usually this is based on the master branch.</li>
      <li> Create a branch based on master git branch bug/auth-fails master then checkout the new branch with git 
       checkout bug/auth-fails. Please avoid working directly on the master branch.</li>
    </ul>
  </li>
<li> Make commits of logical units and describe them properly.</li>
<li>Make sure you stick to PEP8 coding style that is used already.</li>
 <li>If possible, submit tests to your patch / new feature so it can be tested easily.</li>
  <li>Assure nothing is broken by running all the tests.</li>
  <li>Add a meaningful entry to the CHANGELOG.md document.</li>
</ul>

## Submit Changes
<ul> 
  <li>Push your changes to a topic branch in your fork of the repository.</li>
  <li>Open a pull request to the original repository and choose the right original branch you want to patch.</li>
  <li>If not done in commit messages (which you really should do) please reference and update your issue with the code changes. But please do not close the issue yourself.</li>
  <li>Even if you have write access to the repository, do not directly push or merge pull-requests. Let another team member review your pull request and approve.</li>
</ul>
# Additional Resources
<ul>
  <li><a href="https://support.github.com/">General GitHub documentation</a></li>
  <li><a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request">GitHub pull request documentation</a></li>
  <li><a href="https://github.com/necolas/issue-guidelines/blob/master/CONTRIBUTING.md">Read the Issue Guidelines by @necolas for more details</a></li>
</ul>

# Notes
This documented is based in the work from <a href="https://github.com/anselmh/CONTRIBUTING.md">anselmh/CONTRIBUTING.md</a>, licensed as <a href="https://github.com/anselmh/CONTRIBUTING.md/blob/master/README.md#license">Creative Commons Attribution 3.0 Unported License</a>.
