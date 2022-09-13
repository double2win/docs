# Instruction

First, clone the repo:
  git clone https://github.com/double2win/docs.git
  
Second, honkit commands (https://github.com/honkit/honkit)
  
  $ npx honkit serve 
  to launch a local server: http://localhost:4000
  
  $ npx honkit build
  to build the HTML pages from the Markdown files

Third, edit the Markdown (.md) files:
  
  https://honkit.netlify.app/syntax/markdown.html

The READEME.md is the entry file. This is reserved for Double Introduction.

The SUMMARY.md is the TOC file and link the right .md file in the TOC on the left side bar.
New chapters (in .md file) can be added and updated the TOC in SUMMARY.md file.

Forth, after editing and ready to release, execute "npx honkit build" to create the html files
in the "./docs" directory. Then commit and push to Github
  
  git add .
  
  git commit -m "[replace with your own message for commit here]"
  
  git push

We should use "main" branch for content editing. The "public" branch is where the content is
being served to the public at "https://www.double2win.xyz/docs/".
