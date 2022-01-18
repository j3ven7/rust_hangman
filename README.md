# rust_hangman
Teaching myself rust by making a multi-threaded web server for hangman.

Goal is to have players send requests to indicate that they want someone to guess their word. The server
then pairs the "initiator" with a "challenger" who will guess the word. 

The "initiator" and "challenger"
will subscribe to a "notifications" endpoint (using a websocket most likely) and 
will receive updates as the "challenger" guesses letters.
