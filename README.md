So this is a small backdoor I have been working on that is something of a work in progress. It essentially disguises itself as a program that prints out ascii art from files, but also creates a powershell script and a scheduled task for that script, and that script creates a backdoor that also has a scheduled task. It is kind of dumb, but I wanted something to work on, so sue me.

****DO NOT RUN THIS ON YOUR MACHINE****

If you want to try this out yourself, you will need to generate your own powershell backdoor with msfvenom and then paste the contents into $ascii3 in the code. Make sure to cancel out of the $ special character in your string with a backtick.
