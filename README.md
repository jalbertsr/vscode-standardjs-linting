# Visual Studio Code linting with Standard JS.

Linters analyze your source code and can warn you about potential problems before you run your application.

Linters can provide more sophisticated analysis, enforcing coding conventions and detecting anti-patterns. A popular JavaScript linter is [ESLint](https://eslint.org/). ESLint when combined with the ESLint VS Code [extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) provides a great in-product linting experience.

First install the ESLint command line tool:

```
npm install -g eslint
```

Install the extension for VSCode:

![ESLint](https://code.visualstudio.com/images/reactjs_eslint-extension.png)

Now set up a ESLint configuration file

```
eslint --init
```

Choose ```use a popular style guide``` and the ```Standard``` Style Guide

![Screenshot 1](https://i.imgur.com/dqxFScs.png)  

![Screenshot 2](https://i.imgur.com/0lbT9DQ.png)  

After that you will have a ```.lintrc``` configuration file created on your project folder path, you can check it has been successfuly created doing ```ls -la```

![Screenshot 3](https://i.imgur.com/ZrgT28p.png)  

![Screenshot 4](https://i.imgur.com/DKDsl2j.png)

Also install the following VSCode plugins and restart Visual Studio:   
+ [JavaScript Standard Style](https://marketplace.visualstudio.com/items?itemName=chenxsan.vscode-standardjs)  
+ [JavaScript standardjs styled snippets](https://marketplace.visualstudio.com/items?itemName=capaj.vscode-standardjs-snippets)

If you are developing your projects in React I recommend to install this plugin too:
+ [React Standard Style code snippets](https://marketplace.visualstudio.com/items?itemName=TimonVS.ReactSnippetsStandard)

