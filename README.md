## LaTeX Templates for RStudio, Jupyter, and Linux Terminal  

We created a few templates to demonstrate how to write LaTeX directly within RStudio, Jupyter, or Linux terminal. Some computing servers have these tools, but do not allow [Overleaf](https://www.overleaf.com/) (online LaTeX editor) or other LaTeX IDE installations.

Resource Links:

- [LaTeX 101. What is LaTeX? | by Lorin Fields | Medium](https://medium.com/@lorinlambda/latex-101-fc45d49f42ee)
- [Why Should I Use LaTeX over Word for Writing My Research? | Orvium](https://blog.orvium.io/latex-over-word/)
- [Why I Transitioned from Microsoft Word to LaTeX | by Michael R. Apostol | Blank Page | Medium](https://medium.com/blankpage/why-i-transitioned-from-microsoft-word-to-latex-7b9392705167)

## How to use the latex-test-template as a submodule

In your git repo, use this command in the terminal to add the submodule: 
- `git submodule add https://github.com/star1327p/latex-test-template.git`

The `.gitmodules` file will be auto-generated in your repo, and you need to add the last three lines:
```
[submodule "latex-test-template"]
	path = latex-test-template
	url = https://github.com/star1327p/latex-test-template.git
	update = merge
	branch = main
	recursive = true
```
Then commit and push these changes to your repo. You will see the directory `latex-test-template @ [commit hash]` added as a shortcut to your git repo.

Here are the commands to auto-update the submodule within your git repo:
- `git pull`
- `git submodule update --remote`

Enjoy!
