In this task we have to login into a ssh server but they didn’t provide any password. So for this task I used brute force. As I didn’t have hydra I first installed hydra .
after installing hydra I searched for the format of using hydra command.
by the given format I got I the password. 
(the command-hydra -l simba -P /Users/nikshepguni/rockyou.txt -s 2222 4.213.89.50 ssh)
Then i connected to the ssh server using the username and password.
i found the flag in the home directory as mentioned in the description.
