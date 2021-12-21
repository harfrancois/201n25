# Code201ReadingNotes
## **cheat sheet**
  > #### Terminal Cheat Sheet
- pwd: present working directory
- ls: List all of the contents within the directory
- cd [name-of-folder] : go into a specific folder
- cd .. - Go back a directory level
- touch [filename.ext]: create a new file
- mkdir [name-of-directory]: Create a new folder/- - - directory
- code .: open the whole directory into VS Code
- code [nameoffile.ext]: open the single file in VSCode
- cp [current-location-of-file] [new-location-of-file]: copy a file to a new location
- mv [current-location-of-file] [new-location-of-file]: Move a file from one location to another
- rm [name-of-file.ext]: remove/delete a file (edited)

  > #### **HTML** 
  sorce from link - examples/js/pure_js_greating.html
1. <html>
2. <head>
3.   <title>Hello World</title>
4. </head>
5. <body>
6.  
7. First name: <input id="first_name">
8. Last name: <input id="last_name">
9. <button id="say">Say hi!</button>
10.  
11. <hr>
12. <div id="result"></div>
13.  
14. <script>
15. function say_hi() {
16.     var fname = document.getElementById('first_name').value;
17.     var lname = document.getElementById('last_name').value;
18.  
19.     var html = 'Hello <b>' + fname + '</b> ' + lname;
20.  
21.     document.getElementById('result').innerHTML = html;
22. }
23.  
24. document.getElementById('say').addEventListener('click', say_hi);
25. </script>
26.  
27. </body>
28. </html>

