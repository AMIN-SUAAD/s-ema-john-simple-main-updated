I have made an e-commerce platform, where users can select products, review products, and finally can place order. I have deployed the project into firebase and I already provided the live link in the description. 

I will discuss now the 11 software engineering points and where you can find them. 


1. I used GitHub to store my front-end and back-end part of the code. I also used GitHub action for continuous delivery.

   Front-End Part: https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated
   Back-End Part: https://github.com/AMIN-SUAAD/s-ema-john-simple-server-main

   
2. UML


3. DDD


4. I used SonarCloud. SonarCloud assists in evaluating the health of code and developing applications with clean, secure code. Detect bugs and vulnerabilities and receive immediate feedback. I used SonarCloud for front-end part and back-end part both. Please, have a look at the provided links below:

  Front-End: https://sonarcloud.io/project/overview?id=AMIN-SUAAD_s-ema-john-simple-main-updated
  Back-End: https://sonarcloud.io/project/overview?id=AMIN-SUAAD_s-ema-john-simple-server-main


5. I tried to follow the standards of clean code. 

   My five points: 
   1. Commenting where needed
   2. Proper naming of variables and functions
   3. Proper naming of files
   4. Avoiding repeat
   5. Standard formatting implemented
   6. No useless variables or functions defined

I also have my own personal cheat sheet. Please visit https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/11%20points/5/Cheat%20Sheet_Amin%20Suaad.pdf


6. I used “npm run build” to build my project. The build folder is then used to deploy my project. Unless indicated what "build" does in package.json file, “npm run build” does nothing. “npm run build” produces a build directory containing a production build.

Link of the package.json file: https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/package.json

I also have some screenshots for help. Please visit https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/tree/main/11%20points/6


7. Unit testing is a software development technique in which the smallest testable pieces of a program, referred to as units, are examined separately and independently for proper operation. I integrated some nice unit tests in my project. 

Links of tests: 

  1. https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/src/components/Info/_test_/Info.test.js
  2. https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/tree/main/src/components/Inventory/_test_
  3. https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/src/components/NotFound/_test_/NotFound.test.js
  4. https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/src/App.test.js

Also, please visit https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/tree/main/11%20points/7


8. Continuous delivery is a software development process in which code updates are prepared for production release automatically. I used Github actions for continuous delivery of the front-end part. As I deployed in firebase, I connected firebase with GitHub for continuous delivery. Now, I can just make an edit in my code and push the code into the GitHub repo and my live site will follow.

Please visit: https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/actions

For the .yml files please visit the following link:

https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/tree/main/.github/workflows

I used Heroku for the continuous delivery of the back-end part. Please visit: 
https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/11%20points/8/4.PNG


9. I used VS Code. 

    Favorite shortcut keys:
    1. Ctrl + F for find
    2. Ctrl + H for replace
    3. Ctrl + P for quick open
    4. Ctrl + X for cut line
    5. Ctrl + C for copy line
    6. Ctrl + Shift + k for delete line
    7. Ctrl + End for going to end of a file
    8. Ctrl + Shift + Enter for inserting line above
    9. Ctrl + Home for going to the beginning of a file
    10. Ctrl + N for new file


10.  A domain-specific language cleverly employs the features and syntax of a programming language to make completing a given task appear to have first-class support from the programming language itself. I made a DSL that converts arrays to HTML. Please, visit:

https://github.com/AMIN-SUAAD/Additional-files-for-Advanced-Software-Engineering/blob/main/Dsl.js


11. Most of my functions are side effect free.

For function as parameter and return value and closure, visit:
https://github.com/AMIN-SUAAD/Additional-files-for-Advanced-Software-Engineering/tree/main/Funtional%20Programming

For anonymous function, visit: 
https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/blob/main/src/components/Shop/Shop.js and have a look at the “handleAddProduct” function.

“handleAddProduct” is an anonymous function as it has no name. 


Additionally, visit the following link for screenshots:

https://github.com/AMIN-SUAAD/s-ema-john-simple-main-updated/tree/main/11%20points
