<h1> TEN MORE LINUX COMMANDS </h1>

<h2>1.  Find Command </h2>
You use the find command to locate files within a given directory.
As an example, find /home/ -name notes.txt command will search for a file called notes.txt within the home directory and its subdirectories.
To find the test2.txt file in my home directory, i use this:

![find](https://user-images.githubusercontent.com/36430909/193411185-e0fb011c-af81-45bd-836c-242c8a790406.JPG)

<h2>2. Grep Command </h2>
<p> Another basic Linux command that is undoubtedly helpful for everyday use is grep. It lets you search through all the text in a given file.

To illustrate, grep Egineering test2.txt will search for the word **Engineering** in the notepad file. Lines that contain the searched word will be displayed fully.</p>

![grep](https://user-images.githubusercontent.com/36430909/193411493-e0d77f98-7fcd-4640-80f6-941921a23f02.JPG)

<h2>3. du Command </h2>
<p> If you want to check how much space a file or a directory takes, the du (Disk Usage) command is the answer. 
However, the disk usage summary will show disk block numbers instead of the usual size format. 
If you want to see it in bytes, kilobytes, and megabytes, add the -h argument to the command line.</p>

![du](https://user-images.githubusercontent.com/36430909/193411659-f6ac65e7-4cd2-4631-9fb3-05204e269c48.JPG)


<h2>4. diff Command </h2>
<p> Short for difference, the diff command compares the contents of two files line by line. After analyzing the files, 
it will output the lines that do not match. Programmers often use this command when they need to make program alterations
instead of rewriting the entire source code. The simplest form of this command is diff file1.ext file2.ext </p>

![diff](https://user-images.githubusercontent.com/36430909/193412060-b3baaffe-bf41-4327-91f0-5eae7ab39063.JPG)

<h2>5. ping Command </h2>
<p> Use the ping command to check your connectivity status to a server. For example, by simply entering ping google.com, 
    the command will check whether you’re able to connect to Google and also measure the response time. </p>
  
  ![ping](https://user-images.githubusercontent.com/36430909/193412328-d4d1d7b8-0d09-47ff-9432-25872a4d989a.JPG)
  
  ![ping2](https://user-images.githubusercontent.com/36430909/193412338-0fd58746-8dcb-4c23-963d-79060e41db15.JPG)

<h2>6. history Command </h2>
<p> When you’ve been using Linux for a certain period of time, you’ll quickly notice that you can run hundreds of commands every day. 
    As such, running history command is particularly useful if you want to review the commands you’ve entered before.</p>

![History](https://user-images.githubusercontent.com/36430909/193412474-c6880680-113d-4eea-aa5c-614af0d4c739.JPG)


<h2>7. echo Command </h2>
<p> This command is used to move some data into a file. For example, if you want to add the text, “Hello, my name is Dubem” into a file called test.txt, 
  you would type echo Hello, my name is Dubem >> test.txt</p>
  
  ![echo](https://user-images.githubusercontent.com/36430909/193412775-22ce3771-9f9d-48bb-8d11-ff019c0dd323.JPG)
  
 <p> This is the full output </p>
 
 ![echo 2](https://user-images.githubusercontent.com/36430909/193412791-6ee15b7e-18cd-43ea-81ce-041f421dec11.JPG)

 <h2>8. hostname Command </h2>
 <p> If you want to know the name of your host/network simply type hostname. Adding a -i to the end will display the IP address of your network. </p>
 
 ![hostname](https://user-images.githubusercontent.com/36430909/193412871-aec198f8-bf2f-4208-a7ac-ca2f56f9a8a3.JPG)

  <h2>9. exit Command </h2>
<p> The exit command does exactly what its name suggests: With it, you can end a shell session and, in most cases, automatically close the terminal you’re using. </p>
 
 ![exit](https://user-images.githubusercontent.com/36430909/193413105-708dda04-4155-4175-b2a2-d3ced310ea2b.JPG)

  <h2>10. wc Command </h2>
 <p> Wc stands for “word count,” and as the name suggests, it returns the number of words in a text file thus:</p>
 
 ![wc](https://user-images.githubusercontent.com/36430909/193413305-b621f21e-b477-4558-8f27-334d0e65e146.JPG)

 <p> Let’s breakdown the output of this command:
2 lines
13 words
82 byte-size
The name of the file (test.txt)

If you only need the number of words, use the -w flag:</p>

![wc2](https://user-images.githubusercontent.com/36430909/193413469-d6389817-9cef-4a4f-ac5e-0eaeaea6da09.JPG)

  
