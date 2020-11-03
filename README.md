## Hosting your resume on Github Pages <br/> and learn principles of good technical communication along the way

Github Pages is a great way to host a resume or simple website. It's cost-free, ad-free, and very easy to use. In this readme I will explain the steps to hosting your resume with Github Pages. I will also explain a few principles of good technical communication.  These are the italicized sections. If you want to learn more about technical communication, I highly recommend Andrew Etter's book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

*Andrew Etter is a big advocate for storing technical documents (like resumes) on static websites. This allows the document to be easily updated and prevents readers from ever seeing an out-dated version of the document. For example, if you have a new job to add to your resume, just update the webpage. Every job you have applied to will automatically have access to you up-to-date resume.*

### Step 1: Create/Log-in to you Github account
- Create Github account, if you don't have one already. It is a simple process, just like signing up for any other site.

***Consider your audience:*** *As you think about the document you are about to write, consider the audience. This is the most important step, as it will define what you can assume the reader will already know. This is very relevent to a resume. If you are applying for a comp sci job, you can assume the hiring manager will know technical lingo, allowing you omit basic explanations and keep your resume concise.*

### Step 2: Create a new repository called [username].github.io
- Click !["New"](images/new.png) to create a new repository.
The repository's name MUST be [username].github.io.
This creates a special repo that contains a Github Page.<br/>
!["New"](images/repoName.gif)<br/>
Then, click "Create Repository" at the bottom of the page.

### Step 3: Create a new file called "index.md"
Once the repo is made, you will be sent to a Quick Setup page. Click on !["Creating a new file"](images/creatingANewFile.png) and name the file "index.md". This is a markdown file that will be displayed when you visit [username].github.io from a web browser. It works exactly like an index.html, except is it a markdown file.

If you need a refresher on github flavored markdown, here is [a great resource](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### Step 4: Pick a Jekyll theme
In the repo settings, there is a section called Github Pages that lets you configure some aspects of your page. Most importantly, there is a "Change Theme" button that opens a new page of themes for you to browse and select from. These are Jekyll themes. Jekyll is a web software that processes Markdown code and converts it to customizable HTML.  This is what allows our standard Markdown code to appear as an attractive website.  For more information on Jekyll check out [Barry Clark's blog](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/). Once you have picked a theme, return to the main page of your repo and click on "index.mb" to start creating your resume.

### Step 5: Start creating!
Now you have a webpage that natively supports markdown! Githubs preview feature lets you switch back and form from code to preview, to see what your page looks like. It's important to note that any custom css will not be displayed in the preview window, so it is a good idea to have your new website open in a separate tab.

<br/>

![](images/demo.gif)

### FAQs

- *I updated my index file, but why isn't the change showing up on my website?*<br/>
The time it takes for your webpage to reflect your changes can be as long as 10 minutes and as short as 10 seconds. Also, remember that you need to commit any changes to you file with the "Commit Changes" button at the bottom of the editing window.

- *What other tasks can I use markdown for?*
You can use markdown in blogs, emails and some group messaging applications like Discord. There are also services that will convert markdown to PDF, effectively allowing you to ship Markdown documentation with your software.

Thanks to everyone who contributed to the Cayman theme.
