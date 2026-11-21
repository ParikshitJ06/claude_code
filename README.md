# claude_code
This is repo made for customising claude code cli for free
you need to create a config.ymal file (to store the litellm configurations and models details), a setting-local.json file(it is file used by claude code for model, env, api details) , a notepad profile file to create a command (mentioned as profile.txt).

after completing all 3 file , add NVIDIA_API_KEY to a .env file.
then run  the following commands

pip install "litellm[proxy]"

##To run litellm server on Terminal 1 : 
litellm-up 

##To run claude-code on Terminal 2 :
claude 
