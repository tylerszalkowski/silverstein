Open the Find and Replace Panel:

Press Cmd + F to open the Find panel, then Cmd + Option + F to switch to Replace mode.
Enable Regular Expression by clicking the .* icon or pressing Alt + Cmd + R.
Enter the Find and Replace Criteria:

Find: Use a pattern that matches a line, followed by a line break, and then another line. For Unix/Mac style line breaks, use: ^(.*\n)(.*\n)
Replace: Use $1 to keep the first line (including its line break) and remove the second line break. The $1 refers to the first capturing group in the regular expression.
Execute Replace All:

Click the Replace All button or press Cmd + Alt + Enter.
Save Your File.
