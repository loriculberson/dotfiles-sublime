#Move Sublime preferences into dotfiles directory
<h3>How to create a repository of your .dotfiles</h3>

<ol>
	<li>In your root directory, mkdir a directory called: <strong>.dotfiles</strong></li>
	<li>cd into .dotfiles</li>
	<li>Move files into the .dotfiles directory by typing: <strong>mv ~/Library/Application\ Support/Sublime\ Text\ 3/ ~/.dotfiles/</strong></li>
	<li>This will take a little while since the files contain a lot of data.</li>
	<li>While still in the .dotfiles directory, type: <strong>ln -s $HOME/.dotfiles/Sublime\ Text\ 3/ $HOME/Library/Application\ Support/Sublime\ Text\ 3</strong></li>
	<li>Make sure the Sublime directory is in the .dotfiles directory. Type: <strong>ls</strong></li>
	<li>Still in .dotfiles? Good! Create a git repository. Type in the command line: <strong>git init</strong></li>
	<li>Add and commit your files. Type: <strong>git add .</strong> then, <strong>git -m "initial commit"</strong></li>
	<li>Visit github.com and create a new repository.</li>
	<li>Copy the name of the repository</li>
	<li>Type: git remote add origin <<then paste in the repo name>></li>
	<li>Type: git push -u origin master</li>
<ol>
<p>As you make changes to your Sublime or other .files, make sure to push them to your new repo!</p>