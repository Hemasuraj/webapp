### ENTRYPOINT COMMAND
It is used to pass the commands. It is used to run the containers like CMD.
We can't override entrypoint, but we can overrirde CMD
If you use cmd and entrypoint and no command mentioned in terminal then cmd acts as argument provider to entrypoint
if user provide argument in terminal then it can be replaced