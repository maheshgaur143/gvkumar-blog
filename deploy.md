Your repo is good. Here are 3 ways to add articles in the future, from easiest to most flexible:



&nbsp; ---

&nbsp; Method 1: Edit directly on GitHub.com (Easiest — no tools needed)



&nbsp; 1. Go to https://github.com/maheshgaur143/gvkumar-blog

&nbsp; 2. Click "Add file" > "Create new file"

&nbsp; 3. Name it something like new-article.html

&nbsp; 4. Copy the structure from delhi-smog.html and paste your new content

&nbsp; 5. Click "Commit changes"

&nbsp; 6. Then redeploy with one command:

&nbsp; cd C:/Users/Qt-India/myWorkspace/Mystuff/gvkumar/blog

&nbsp; git pull \&\& npx netlify-cli deploy --prod --dir . --site 904fdc0b-971c-4280-90ad-3ad8bcca003c



&nbsp; ---

&nbsp; Method 2: Ask me again in Claude Code (Recommended)



&nbsp; Just come back here and say something like:

&nbsp; "Add a new article titled 'Monsoon Patterns in South India' to gvkumar blog"



&nbsp; I'll:

&nbsp; - Create the HTML page with proper formatting

&nbsp; - Update the articles listing page

&nbsp; - Push to GitHub

&nbsp; - Redeploy to Netlify



&nbsp; All in one go.



&nbsp; ---

&nbsp; Method 3: Do it yourself locally (Full control)



&nbsp; # 1. Create your new article HTML file in the blog folder

&nbsp; #    C:/Users/Qt-India/myWorkspace/Mystuff/gvkumar/blog/



&nbsp; # 2. Add it to articles.html listing



&nbsp; # 3. Push to GitHub

&nbsp; cd C:/Users/Qt-India/myWorkspace/Mystuff/gvkumar/blog

&nbsp; git add -A

&nbsp; git commit -m "Add new article: Article Title"

&nbsp; git push



&nbsp; # 4. Deploy to Netlify

&nbsp; npx netlify-cli deploy --prod --dir . --site 904fdc0b-971c-4280-90ad-3ad8bcca003c



&nbsp; ---

&nbsp; Quick Reference Card

&nbsp; ┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────┐

&nbsp; │      What       │                                       Value                                       │

&nbsp; ├─────────────────┼───────────────────────────────────────────────────────────────────────────────────┤

&nbsp; │ Blog URL        │ https://gvkumar-blog.netlify.app                                                  │

&nbsp; ├─────────────────┼───────────────────────────────────────────────────────────────────────────────────┤

&nbsp; │ GitHub Repo     │ https://github.com/maheshgaur143/gvkumar-blog                                     │

&nbsp; ├─────────────────┼───────────────────────────────────────────────────────────────────────────────────┤

&nbsp; │ Local files     │ C:/Users/Qt-India/myWorkspace/Mystuff/gvkumar/blog/                               │

&nbsp; ├─────────────────┼───────────────────────────────────────────────────────────────────────────────────┤

&nbsp; │ Netlify Site ID │ 904fdc0b-971c-4280-90ad-3ad8bcca003c                                              │

&nbsp; ├─────────────────┼───────────────────────────────────────────────────────────────────────────────────┤

&nbsp; │ Deploy command  │ npx netlify-cli deploy --prod --dir . --site 904fdc0b-971c-4280-90ad-3ad8bcca003c │

&nbsp; └─────────────────┴───────────────────────────────────────────────────────────────────────────────────┘

&nbsp; Would you like me to save this reference card somewhere on your machine for easy access later?

