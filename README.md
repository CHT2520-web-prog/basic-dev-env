# Basic Development Set-Up for CHT2520 Advanced Web Programming

This repository is a template for creating a basic development set-up for CHT2520.

- To get started, click on the green button in the top-left that says 'Use this template' and then select 'Open in a codespace'.
- It will probably take a few minutes to set-up the codespace.

This codespace is where you will do all your practical work in the module. You will use separate codespaces for each of the assignments.

- In the codespace, using the file explorer, create a new folder. Name it 'test'.
- Inside this folder create a new page. Name it 'test.php'.
- Enter the following into this page:
  ````html
  <!DOCTYPE html>
  <html>
    <head>
      <title>Introduction to PHP</title>
      <meta http-equiv="content-type" content="text/html;charset=utf-8" />
    </head>
    <body>
      <?php
    echo "Welcome to CHT2520";
    ?>
    </body>
  </html>
  ```html
  ````
- Save the page
- In the terminal enter the following to start Apache
  ```
  apache2ctl start
  ```
- You should get a pop-up message stating your application is running

  - Select 'Open in a Browser' and a new tab will open.
  - Select the 'test' folder and 'test.php' and confirm you get can see the PHP generated message.

- Back in your codespace, make a simple change to the message e.g. delete a word.
- Save the file
- Switch to the second tab
- Refresh the page and confirm the changes have taken place.

This is the basic workflow we will follow to develop and test our PHP applications.

## When you've finished working

- Close both tabs.
- Visit [https://github.com/codespaces](https://github.com/codespaces).
- Find the codespace you have just created (it should say it is active).
- Click on the three dots and select 'Stop codespace'.

## Next time you want to do some work

- Visit [https://github.com/codespaces](https://github.com/codespaces).
- Click on the name of the codespace you want to open.
