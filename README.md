# SpringBootChatApplication

In this Project, we will build the chat application with Spring Boot and WebSocket where anyone can communicate or chat with others. Just you need to type your name to login and start chatting with others.

Generally, the web application has developed in the model of request and response parameter, so whenever any request comes to the server then it returns the data as a response parameter, but if you noticed, the server never sends the data to the client on its own.

The server always waits for the client or browser request and accordingly sends the data in the form of JSON. In short, there is only one way of communication between the server and the client. The server always needs to be dependent on the client in order to send the data.

But with the help of the WebSocket Protocol, we can achieve the two-way communication between the server and the client, which means the server no need to wait for the client’s request to send the data.

![Screenshot (225)](https://user-images.githubusercontent.com/49764935/122663543-d0129b00-d1b8-11eb-982a-c35cfbcbbb52.png)
![Screenshot (226)](https://user-images.githubusercontent.com/49764935/122663545-d1dc5e80-d1b8-11eb-9a7a-c3515c562b0a.png)
![Screenshot (227)](https://user-images.githubusercontent.com/49764935/122663547-d274f500-d1b8-11eb-8b14-dc60c0e3321c.png)
