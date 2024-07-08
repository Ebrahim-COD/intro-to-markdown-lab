# How to create a file using the Terminal

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