# Discovering the Capabilities of Sass

This [repo](https://swanie21.github.io/sass-discovery/) covers these Sass topics:


* Installing Sass locally and implementing it
* Sass Features and examples
* SCSS Formatting


When compiled Sass creates a `.sass-cache` folder containing all the templates and partials to speed up the creation of CSS.

If you want to ignore this folder in your repo you need to create a `.gitignore` file and state `*.sass-cache` to ignore this folder in the root directory.

If you have already pushed the `.sass-cache` folder to your repo you can remove it by typing `git rm -r --cached .sass-cache/` in the terminal and you will immediately see those files deleted. If you check your `git status` you won't see those deleted files, but you'll still need to `add`, `commit` and `push` these changes to your repo.
