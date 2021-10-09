# Student README

## Questions

1. The client and server have different sized buffers.  Why does it still work?
it is legal to use buffers with different length at client and server. Actually it must be legal because for example web browser has no information buffer size in web server and web server has no idea about client buffer.

2. What happens if the buffer size on the client is changed to a value smaller than the initial `message_length`?
    i think the new data is not accepted
3. What happens if you run the client when the server is not running? 
   silently dropped due to other network issues/congestion.
4. What happens if you run the server while the server is already running?
it  becomes busy 
   
5. What changes did you make to finish this assignment?
=> i made a global variable => and a function  => i imported thread 

6. What resources did you use to complete this assignemnt?  Make a Markdown list of web links below.

https://www.youtube.com/watch?v=DIPZoZheMTo
https://stackoverflow.com/questions/35289268/different-socket-buffer-size-for-client-and-server