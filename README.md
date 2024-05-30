## Chat application in Rust
This is a simple chat application in Rust. The application has two parts: 1. Client, 2.Server. 
You can type something on the client side and the server will receive it.

## How to Run it

- To run this program you need to open 2 terminals. One for the client and one for the server. 
- In the server run `cargo run`. 
- Then do the same for your client. And this time you should see a message, write a message. 
- Type something and then you should see that in the server as well as the bytes received.
- For example if you typed "hello", you should see in the server side "hello" in bytes too. For longer messages, it will cut them off at 32 bytes.
- If you type `:quit` then the program will quit on the client and the server will say closing connection and the client name.

**Tutorial** [here](https://eleftheriabatsou.hashnode.dev/tutorial-chat-application-client-server-in-rust).
