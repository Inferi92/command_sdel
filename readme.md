# Steps to deploy "sdel" command in Linux:

1. Save the file as sdel in a directory that's in your system's $PATH. You can use the command echo $PATH in the terminal to see a list of directories that are in the $PATH.
2. Make the script executable with the command chmod +x sdel.
3. Verify that the script is in your $PATH by typing sdel in the terminal. If the command is not found, you may need to restart your terminal or add the directory where the script is located to your $PATH.
   - **Add the directory where the script is located to your $PATH:**
     - Open .bashrc file using text editor (type in shell "**nano ~/.bashrc**")
     - Add at the end of it the following "**export PATH=$PATH:<your_directory_file_location>**"
     - Close and save (Ctrl + X)
4. Test "sdel" command 
