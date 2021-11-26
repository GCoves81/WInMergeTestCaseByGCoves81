# WInMergeTestCaseByGCoves81
Winmerge Test Case for Comments in C++ and Java Source Files

Issue Description:
Folder comparison (folders A & B). The file in B has an additional line containing a tab and a comment. Comparison result should be "Text files are identical".

Options:
- General | Whitespaces : Ignore Change
- General | Ignore blank lines: Checked
- General | Ignore comment differences: Checked
- General | Diff algorithm : default (also tried minimal and patience)
- Compare Methods: Full Contents (also tried Quick Contents)
- Plugins : Enabled (IgnoreCommentsC is Enabled too, and the "Enable automatic unpacking/prediffing for the plugin" option is checked).
- Filters : <None>

Question:
- Is it enough to append ;\.java$ to the File Filters for the IgnoreCommentsC plugin to make it working for .java files as well? (comments syntax is the same, /* Comment */ and // Comment)
