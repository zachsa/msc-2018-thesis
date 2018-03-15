# README #
Written and built using LaTeXTools - so there are some configurations that are specific to the original environment; specifically regarding the Minted (code highlighting) package.
https://github.com/SublimeText/LaTeXTools

### How do I get set up? ###
Install Sublime Text 3, LaTeXTools, Python (including Pip, Pygments and other libraries). Then, in Sublime, change the following LaTeXTools User configurations:

* Adjust your $PATH environment to include Pygments, pip, etc (Resolve error logs one-by-one)
* Adjust the LaTeXTools settings:
* * Set `aux_directory` to `C:\path\to\repo\_build` (this is an absolute path to this repository, + the `_build` folder that is created when the project is built)
* * Set `output_directory` to this same path as `aux_directory`

When the latex code is built, a directory `_build` should be created at the root of this repository containing PDF and temporary output.