# command-line-workshop

For this workshop, you will be working inside the DecodeMTL project in your Cloud9. However, you will be creating a separate Git repository to submit your answers.

* Start by forking this repository to your own GitHub account.
* In your Cloud9, move to your home directory and clone your fork of the repository
* You will be doing most of your work inside this cloned, empty repo

## History
 * Create a branch `cmd-history` off of `master`
 * Create a file called `history.txt` that contains all your history so far
 * Add and commit this file to Git
 * Push the branch to GitHub and create a pull request to submit your answer

## Searching for files
 * Create a branch called `finding-files` off of `master`
 * Find all the files in the DecodeMTL project that have the word "logo" in the file name
 * Take the output of the command to a file called `files-with-logo.txt`
 * Add/commit that file to Git
 * Find all the files in the DecodeMTL project that are over 500KB
 * Take the output of the command to a file called `files-over-500kb.txt`
 * Add/commit that file to Git
 * Push the branch to GitHub and create a pull request to submit your answer

## Searching for content in files
 * Create a branch called `finding-content` off of `master`
 * Find all the files in the DecodeMTL project that contain the word "javascript"
 * Take the output of the command to a file called `files-with-javascript.txt`
 * Add/commit that file to Git
 * Do the same thing you did, but adding the line numbers to the found files
 * Take the output of the command to a file called `files-with-javascript-numbers.txt`
 * Using the manual page, figure out how to only output the file names **only** rather than the content
 * Take the output of that new command to a file called `filenames-with-javascript.txt`
 * Add/commit that file to Git
 * Push the branch to GitHub and create a pull request to submit your answer

## Pipes and redirection
 * Create a branch called `pipes-and-redirection`
 * Install the command-line application called `fortune`
 * Try running the `fortune` application by itself
 * Read the manual page for the `fortune` application to see if you can do anything fun with it
 * Run the fortune application again and send its output to a file called `fortune.txt`
 * Using the `tr` command (you'll have to read the manual page), see if you can replace all instances of the letter `e` with an underscore `_` in the `fortune .txt` file
 * Again, using the `tr` command, send its output to a file called `fortune-replaced.txt`
 * Using a combination of `fortune` and `cowsay`, try to make the cow say a fortune
 * Take the output of the cow saying its fortune to a file called `cow-fortune.txt`
 * Add/commit all your files
 * Push the branch to GitHub and create a pull request to submit your answer

## Advanced pipes and redirection
 * Learn more about the `sort` command
 * Learn more about the `uniq` command
 * Learn more about the `wc` command
 * Using one of the previous commands, count the number of words in the `poem.txt` file and send that to a file called `poem-words.txt`
 * Using one of the previous commands, count the number of lines in the `poem.txt` file and send that to a file called `poem-lines.txt`
 * Sort the `poem.txt` file in alphabetical order, and send this output to `poem-sorted.txt`
 * Create a file called `poem-unique.txt` that contains the sorted poem, but without duplicate lines
 * Create a file called `poem-popular.txt` that contains the lines of the poem sorted in the order they appear most often
 * Create a file called `poem-hipster.txt` that contains **ONLY** the lines that appear once in the poem
