THIS FILE WILL EXPLAIN THE FUNCTION OF EACH FILE WITHING THE DIRECTORY

.gitignore - ignores emacs autosave files (ending with ~)

0-hello_world - echo command writes in the console Hello, World

1-confused_smiley - some special characters are needed to stop bash from interpreting other special characters

2-hellofile - the cat command writes in the console the content of the file

3-twofiles - a space between arguments is enough

4-lastlines - the tail command displays the last 10 lines by default

5-firstlines - the head command displays the first 10 lines by default

6-third_line - a combo of head and tail with their respective -n options makes this happen

7-file - same as 1, just more tedious

8-cwd_state - a pipe should be enough

9-duplicate_last_line - tail command and append to same file

10-no_more_js - find command with delete option plush a wildcard to specify .js files should do it

11-directories - find with mindepth to avoid current directory and wc -l to show lines

12-newest_files - pipe result of ls -t into head

13-unique - sort before uniq for uniq to work, u option to only print duplicate lines

14-findthatword - grep command finds patterns in lines. grep "root" works fine

15-countthatword - grep has a -c option that counts the times the pattern appears

16-whatsnext - grep has a -A option that adds the next number of desired lines after the pattern line

17-hidethisword - the -v option for grep makes it do the opposite of what i would normally do

18-letteronly - grep for ^[[:alpha:]] (alphabetic characters, first letter of the line)

19-AZ - tr command changes a set of characters to another, in this case a and c for z and e

20-hiago - tr command option -d deletes the sets characters

21-reverse - rev command reverses input file, also, it should be "Write a script that reverseS its input."

22-users_and_homes - the cut command has a -f option, (in this case we would use a : separator) then sort

23-empty_casks find empty then cut the extension with cut

24-gifs - find command then cut the extensions, then sort by version in reverse fashion

25-cut the first character then paste without the tab and eliminate space

26-cut then sort uniq count and then eliminate the extra stuff 