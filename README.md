# TEALS GitHub Codespaces for Ephrata High School
## Creates a Development Container for Java on GitHub Codespaces

These instructions will guide you through the process of setting up Codespaces, an online IDE. _IDE_ stands for _Integrated Development Environment_, which is a program that software developers use to write code. You can use any text editor to write code, but an IDE makes it _much_ easier.

Think of Codespaces like Microsoft Word for code. You can write a really long essay in Notepad if you want to, but you'll almost always prefer to do it in Word or Google Docs.

This step will involve entering some commands into the terminal, or command line. If this if the first time you've used a terminal, it can be intimidating. Don't worry! Just follow the directions and copy and paste the commands exactly. When an instruction says to _enter_ a command, it means to type (or paste) the command, and then press the Enter key to execute it.

  1. Open a terminal in your Codspace using the keyboard shortcut ``Ctrl + ` `` (you can also go to the menu in the top left and select Terminal > New Terminal) 
       

  Make sure it is a bash shell

  2. In the terminal, type or paste the following command and hit Enter:

```
pwd
```

  3. Now enter the following command (remember, "entering" a command means typing or pasting it into the terminal, then pressing Enter to execute it):

```
git status
```


  4. Enter the following command, replacing `<GitHubusername>` with the `<firstname>-<lastinitial>-ephrata-teals` username you created earlier:

```
git config --global user.name "<GitHubusername>"
```

  5. Confirm that you have set the username correctly by entering the following command:

```
git config --global user.name
```

  6. Enter the following command, replacing `email@example.com` with your `@ephrataschools.org` email:

```
git config --global user.email "email@example.com"
```

  7. Confirm that you have set the email address correctly by entering the following command:

```
git config --global user.email
```

  
  
At the end of every class, you will run the following sequence of commands:

```
git add -A
git commit -m "<description of your work for the day>"
git push origin main
```
This will save your changes by pushing them changes to your forked repository.

