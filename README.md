# python-app-development2
# cli commands used to create the new version package bundle

1. Install zip (if not already installed)
   * Open WSL terminal
   * Type sudo apt-get update ==> to update the package list
   * Type sudo apt-get install zip ==> to install the zip utility

2. Navigate to the directory containing the files that want to be zip
   * Use cd command to navigate to the desired directory. For example: cd /path/to/files

3. Use the unzip command.
   * unzip python.zip

4. modify file application.py ==> Change the required text

5. Use zip command ==> to zip the modified file and other file and the hidden directory
   zip -r python.py .ebextensions application.py cron.yaml


