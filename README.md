# Terminal-Commands
Some additional terminal commands I've written (OSX- El Capitan)

###CSUS
I did this on a Mac, if you're using Linux change "Users" to "home" <br>
First, navigate to your home directory by typing <br><code>cd</code><br>
Then, make a directory called bin by typing:<br><code>mkdir bin</code>
<br>Then navigate to that directory by typing:<br><code>cd bin</code> 
<br>Now, in this directory, <code>vim csus</code> and paste the csus file on the directory, changing vedv to your username. Save and close.
<br>Now, we have to export this file to our PATH. To do this, first type:
<br><code>chmod +x csus</code><br>
Now, navigate to your <code>.bash_profile</code> by typing:
<br><code>cd && vim .bash_profile</code><br>
Now type in the following, and save and close:
<br><code>PATH=$PATH:$HOME/bin</code><br>
That's it! You should now be able to type <code>csus</code> on your command line and get the prompt to login.

