# How to create a file using the Terminal

![Terminal](https://media.istockphoto.com/id/1473387015/vector/futuristic-pc-80s-90s-with-opened-terminal-console.jpg?s=2048x2048&w=is&k=20&c=iXg_hGnmqFnTjnKyYR6vSYGQ0bU2MlRL8XHzAMva0vQ=)

######  Files are created, edited, deleted, and used by many of the background OS processes. Files are also used by regular users to accomplish daily tasks such as taking notes, writing code, or simply duplicating content.


***Method #1:*** How to Create Files Using the ```touch``` Command

 - The touch command creates empty files. You can use it to create multiple files as well.
    
- Syntax of the touch command:

    ```bash
     touch FILE_NAME
    ```
***Method #2:*** How to Create Files Using the ```cat``` Command

 - The ```cat``` command is most commonly used to view the contents of a file. But you can also use it to create files.

 - Syntax of the ```cat``` command:

    ```bash
    cat > filename
    ```
***Method #3*** How to Create Files Using the ```echo``` Command

  - The ```echo``` command is used to add and append text to files. It also creates the file if it doesn't already exist.

  - Syntax of the ```echo``` command:

    ```bash
    echo "some text" > sample.txt
    OR
    echo "some text" >> sample.txt
    ```
### Conclusion

In this article, we discussed three different methods to create files in the Linux command line. I hope you found this tutorial helpful.

### Reference:

- [Picture Terminal](https://www.istockphoto.com/vector/futuristic-pc-80s-90s-with-opened-terminal-console-gm1473387015-503537438)
- [Tutorial Command Line](https://www.freecodecamp.org/news/how-to-make-a-file-in-linux-from-the-command-line-create-a-file-in-terminal/)