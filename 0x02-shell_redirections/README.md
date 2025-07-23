7-file question : Write a shell script that creates a file named exactly *\'"Best School"\'\*$\?*****:), containing the text Best School, and ending with a new line.

10-no_more_js : Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its sub-folders.
"code : find . -type f -name "*.js" -delete"
✅ Explanation:
find . – Start in the current directory (.).
-type f – Only match regular files, not directories.
-name "*.js" – Match files ending in .js.
-delete – Delete each matched file (safe and efficient).
