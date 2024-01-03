---
layout: default
title: "Contributing"
permalink: /contributing/
---
<div class="content-div">
<h1 class="category-title">Contributing to Jangala’s Knowledge Base</h1>
<p>
    This is a short guide on how to contribute to Jangala’s knowledge base. Our knowledge base can be found at the link <a href="https://github.com/jangala-dev/jangala-dev.github.io" target="_blank">here</a>.
</p>

<h2 id="creatingAPost">Creating a Post</h2>

<p>Step 1 - Go to the _posts folder <a href="https://github.com/jangala-dev/jangala-dev.github.io/tree/main/docs/_posts" target="_blank">here</a>. Click on the folder you want to add your post to. If the folder doesn't exist go to the <a href="#addingAFolderCategory">"Adding a New Folder / Category"</a> section:</p>
<img align="center" src="{{ '/assets/img/contributing1.png' | relative_url }}" width="60%" />

<p>Step 2 - Click “Add file” and then click “Create new file”:</p>
<img align="center" src="{{ '/assets/img/contributing2.png' | relative_url }}" width="30%" />

<p>Step 3 - Create a name for the file. The name should be the current date in YYYY-MM-DD format, followed by the topic name (hyphen-separated), and then .md:
</p>
<img align="center" src="{{ '/assets/img/contributing3.png' | relative_url }}" width="30%" />

<p>Step 4 - Add post metadata at top of posts. Copy and paste the example below (feel free to look at other posts for examples):</p>

<pre>
<code>
---
layout: post
title: REPLACE WITH TITLE e.g. Example Post
category: REPLACE WITH CATEGORY. This should be the folder you want the post to sit in, e.g. organisation or organisation/the_need_for_jangala
---
</code>
</pre>

<p>
Step 5 - Create the content. Here we can use markdown to write our post. Look at other articles for help:
</p>
<img align="center" src="{{ '/assets/img/contributing7.png' | relative_url }}" width="80%" />

<p>
Step 6 - Click “Commit changes…” and then follow the <a href="#createPullRequests">“Creating Pull Requests”</a> section in the knowledge base guide:
</p>
<img align="center" src="{{ '/assets/img/contributing5.png' | relative_url }}" width="30%" />

<p>
Once we have completed these steps our post should look like this:
</p>
<img align="center" src="{{ '/assets/img/contributing6.png' | relative_url }}" width="60%" />

<h2>Updating a Post</h2>
<p>Step 1 - Go to the <a href="https://github.com/jangala-dev/jangala-dev.github.io/tree/main/docs/_posts" target="_blank">_posts</a> folder and select the post you would like to update:</p>
<img align="center" src="{{ '/assets/img/contributing1.png' | relative_url }}" width="60%" />

<p>Step 2 - Click on the post, then click on the pencil icon which will take you to “Edit in place”:</p>
<img align="center" src="{{ '/assets/img/contributing8.png' | relative_url }}" width="30%" />

<p>Step 3 - Edit the post as you see fit:</p>
<img align="center" src="{{ '/assets/img/contributing5.png' | relative_url }}" width="30%" />

<p>Step 4 - Click “Commit changes…” and then follow the <a href="#createPullRequests">“Creating Pull Requests”</a> section in the knowledge base guide:</p>

<h2 id="addingAFolderCategory">Adding a New Folder / Category</h2>
<p>
We can add new folders to the knowledge base but there are some limitations. We can only go two folders deep before they are no longer displayed. For example, we can have subfolders like 'The Need for Jangala' within the top-level folder 'Organisation', but no subfolders can be created within the 'The Need for Jangala.' This is due to limitations with github pages being static.
</p>

<p>
Step 1 - You will first need to create a file defining the new category. Apply the explanation of creating a file in <a href="#creatingAPost">"Creating A Post"</a> but in the <a href="https://github.com/jangala-dev/jangala-dev.github.io/tree/main/docs/_pages/categories" target="_blank">categories</a> folder instead. The new document will need to look like the following:
</p>

<pre>
<code>
---
layout: category
title: "Our Partners And Deployments"
permalink: /organisation/our_partners_and_deployments/
taxonomy: organisation/our_partners_and_deployments
---
</code>
</pre>

<p>
layout should remain as "category". Title should be what we want to appear when we click on the category in the sidebar. The permalink and taxonomy should just be the path to the folder from _posts. Permalink needs "/" at the start and the end.
</p>

<p>
Step 2 - Click “Commit changes…” and then follow the <a href="#createPullRequests">“Creating Pull Requests”</a> section in the knowledge base guide:
</p>
<img align="center" src="{{ '/assets/img/contributing5.png' | relative_url }}" width="30%" />


<p>Step 3 - After this, go back to <a href="https://github.com/jangala-dev/jangala-dev.github.io/tree/main/docs/_posts" target="_blank">_posts</a>. Follow the directions in <a href="#creatingAPost">"Creating A Post"</a> to create your post. The only additional step is with regards to naming the file, as you will need to specify a new path for the file since you are creating a new folder. Rather than naming your file e.g. "2023-12-5-Example.md", name it e.g. "software/2023-12-5-Example.md" if you have created a new category called "software", and Github will create the new folder for you.
</p> 


<h2 id="createPullRequests">Creating Pull Requests</h2>

<p>Step 1 - Complete the popup form, add a commit name which describes what you are doing, select create a new branch, and create a unique branch name which is related to what you are doing. Example:
</p>
<img align="center" src="{{ '/assets/img/contributing9.png' | relative_url }}" width="60%" />

<p>Step 2 - To create a pull request add a title which briefly describes what the request is, a description which can go into more detail about the request, and add a reviewer this person will review the changes you have made:</p>
<img align="center" src="{{ '/assets/img/contributing10.png' | relative_url }}" width="60%" />

<p>For more information use github’s official documentation for creating pull requests <a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request" target="_blank">here</a>.</p>

<h2>Reviewing Pull Requests</h2>
<p>Follow github’s official documentation for reviewing pull requests <a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request" target="_blank">here</a>.</p>

