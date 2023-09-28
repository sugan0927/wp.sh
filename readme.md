To run a Bash script on a Linux system, you need to follow these steps:

1. **Create the Bash Script:**
   Create a plain text file with a `.sh` extension. You can use a text editor like `nano`, `vim`, or `gedit` to create and edit the script.

   For example, if you have a script named `install_wordpress.sh`, you can create it with:

   ```bash
   nano install_wordpress.sh
   ```

2. **Write Your Bash Script:**
   Write the commands and code you want to execute in the script file.

3. **Make the Script Executable:**
   Before you can run the script, you need to make it executable using the `chmod` command:

   ```bash
   chmod +x install_wordpress.sh
   ```

4. **Run the Bash Script:**
   You can run the script using the following command:

   ```bash
   ./install_wordpress.sh
   ```

   Replace `install_wordpress.sh` with the actual name of your script.

5. **Follow the Script Execution:**
   The script will start running, and you'll see the output of the commands it executes. Make sure to monitor it for any errors or prompts that require your input.

Remember that running scripts with root privileges (using `sudo`) may be necessary for some tasks, especially if the script needs to install packages or make system-level changes. Be cautious when running scripts from untrusted sources and ensure you understand what the script does before executing it.￼Enter
