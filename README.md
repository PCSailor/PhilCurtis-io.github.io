<b>Enabling GitHub Pages to publish your site from master or gh-pages</b><br>
To select master or gh-pages as your publishing source, you must have the branch present in your repository. If you don't have a master or gh-pages branch, you can create them and then return to source settings to change your publishing source.
On GitHub, navigate to your GitHub Pages site's repository.
Repository settings buttonUnder your repository name, click  Settings.
select-gh-pages-or-master-as-sourceUse the Select source drop-down menu to select master or gh-pages as your GitHub Pages publishing source.
click-save-next-to-source-selectionClick Save.<br>
<br>
<b>Publishing your GitHub Pages site from a /docs folder on your master branch</b><br>
To publish your site's source files from a /docs folder on your master branch, you must have a master branch and your repository must:
have a /docs folder in the root of the repository
not follow the repository naming scheme <username>.github.io or <orgname>.github.io
GitHub Pages will read everything to publish your site, including the CNAME file, from the /docs folder. For example, when you edit your custom domain through the GitHub Pages settings, the custom domain will write to /docs/CNAME.
Tip: If you remove the /docs folder from the master branch after it's enabled, your site won't build and you'll get a page build error message for a missing /docs folder.
On GitHub, navigate to your GitHub Pages site's repository.
Create a folder in the root of your repository on the master branch called /docs.
Repository settings buttonUnder your repository name, click  Settings.
select-master-branch-docs-folder-as-sourceUse the Select source drop-down menu to select master branch /docs folder as your GitHub Pages publishing source.
Tip: The master branch /docs folder source setting will not appear as an option if the /docs folder doesn't exist on the master branch.
click-save-next-to-master-branch-docs-folder-source-selectionClick Save.
Added Publish info to ReadMe file<br>
https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/<br>
https://github.com/blog/2289-publishing-with-github-pages-now-as-easy-as-1-2-3<br>
