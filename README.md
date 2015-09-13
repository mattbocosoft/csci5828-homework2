**CSCI 5828: Foundations of Software Engineering**  
*Fall 2015, Professor Kenneth Anderson*

Student: **Matthew Thomas**

##Homework 2
Due before the start of Lecture 9, which starts at 12:30 PM MDT on September 22, 2015.

1. *[master]* mkdir "Homework 2"  
2. *[master]* cd "Homework 2"  
3. *[master]* git init  
4. *[master]* touch README.md  
5. *[master]* open -e README.md  
// [EDIT README.md] Add header and initial commands  
6. *[master]* git add README.md  
7. *[master]* git commit -m "Commit 0 - Create README.md file, add header and initial commands"  
// [EDIT README.md] Add next list of commands  
8. *[master]* git add README.md  
9. *[master]* git commit -m "Commit 1 - [README.md] Add next list of commands"  
// [EDIT README.md] Add next list of commands  
10. *[master]* git add README.md  
11. *[master]* git commit -m "Commit 2 - [README.md] Add next list of commands"  
// Find hash of first commit  
12. *[master]* git log  
13. *[master]* git checkout 2cbe8d0b0236fa673eec4b6bd48a9738d7c88024  
14. *[HEAD]* git checkout -b bug-fix  
// [EDIT README.md] Add next list of commands  
15. *[bug-fix]* git add README.md  
16. *[bug-fix]* git commit -m "Commit 3 - Add next list of commands"  
// [EDIT README.md] Add next list of commands  
17. *[bug-fix]* git add README.md  
18. *[bug-fix]* git commit -m "Commit 4 - Add next list of commands"  
19. *[bug-fix]* git merge master  
// [EDIT README.md] Resolve merge conflict (and add next list of commands)  
20. *[bug-fix]* git add README.md  
21. *[bug-fix]* git commit  
// Update commit message using vim, and save using ESC :wq  
// [EDIT README.md] Add next list of commands  
22. *[bug-fix]* git add README.md  
23. *[bug-fix]* git commit -m "Commit 6 - Add next list of commands"  
// Find hash of commit 4  
24. *[bug-fix]* git log  
25. *[bug-fix]* git checkout e9a5e71e4fe02d92ec84bea4640b39d7d0de0ea2  
26. *[HEAD]* git checkout -b bug-fix-experimental  
// [EDIT README.md] Add next list of commands  
27. *[bug-fix-experimental]* git add README.md  
28. *[bug-fix-experimental]* git commit -m "Commit 7 - Add next list of commands and add missing line breaks to README.md"  
// [EDIT README.md] Add next list of commands  
29. *[bug-fix-experimental]* git add README.md  
30. *[bug-fix-experimental]* git commit -m "Commit 8 - Add next list of commands"  
// [EDIT README.md] Add next list of commands  
31. *[bug-fix-experimental]* git add README.md  
32. *[bug-fix-experimental]* git commit -m "Commit 9 - Add next list of commands"  
33. *[bug-fix-experimental]* git checkout master  
// [EDIT README.md] Add next list of commands  
34. *[master]* git add README.md  
35. *[master]* git commit -m "Commit 10 - Add next list of commands"  
36. *[master]* git checkout bug-fix  
37. *[bug-fix]* git merge bug-fix-experimental  
// [EDIT README.md] Resolve merge conflict (and add next list of commands)  
38. *[bug-fix]* git add README.md  
39. *[bug-fix]* git commit  
// Update message for Commit 11 using vim, and save using ESC :wq  
// [EDIT README.md] Add next list of commands and add missing line breaks  
40. *[bug-fix]* git add README.md  
41. *[bug-fix]* git commit -m "Commit 12 - Add next list of commands and add missing markdown line breaks to README.md"  
42. *[bug-fix]* git checkout master  
43. *[master]* git merge bug-fix  
// [EDIT README.md] Resolve merge conflict (and add next list of commands)  
44. *[master]* git add README.md  
45. *[master]* git commit  
// Update message for Commit 13 using vim, and save using ESC :wq  
