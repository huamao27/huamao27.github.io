@index.html is shown on huamao27.github.io as on webpage.
is it possible to add more web tabs/pages on it
I'll help you understand how to add more pages to your website. Let me first check the current structure of your repository.

Bash List HTML and markdown files in the repository
IN
find /c/HW/WorkspaceHW/huamao27.github.io -type f -name "*.html" -o -name "*.md" | head -20

OUT
/c/HW/WorkspaceHW/huamao27.github.io/index.html
Yes, it's absolutely possible! Your current site has just one index.html file. Here are the main approaches:

Option 1: Create Separate HTML Pages (Simplest)
Add new .html files in the same directory as index.html:

index.html (home page)
research.html (dedicated research details)
business.html (commercialization opportunities)
participation.html (how to get involved)
Users navigate via links like <a href="research.html">Research</a>

Option 2: Single-Page Navigation (No Page Reloads)
Keep everything in one HTML file but use JavaScript tabs or sections that show/hide content dynamically — this is what many modern sites do.

Option 3: GitHub Pages with Multiple Sections
Create a subfolder structure:


/docs/
  index.html
  /research/
    index.html
  /business/
    index.html
Which approach suits you best?

Quick & simple? → Option 1 (separate HTML files)
Faster navigation? → Option 2 (tabs in one file)
Professional structure? → Option 3 (organized folders)
If you'd like, I can refactor your current page into multiple pages or add tabbed navigation. What would work best for your workflow?