Instance runs initially then transitions to unhealthy, 
this is not because its failing, the main reason is that the get request is meant for the user to add input
if there is no input it is supposed to throw the error which is a 400x type error. That is what is being thrown to the monitoring metrics as attached in the screenshot

I have also attached a screenshot of the logs to show what the error is and that everything was succesfuly deployed and built

The application works as intended and can be furthermore tested on your local environment.
