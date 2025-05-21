# Reflection

## 2.1 Original code of broadcast chat.

### Observations
Here is one server(top-left) and 3 other clients launched:
![2.1 Observations](images/2.1.png)


### Explanations

- Server (Top-Left) : It listens on port 2000. As shown in the output, three clients have successfully connected from 127.0.0.1 (localhost) but with different port numbers. Then, all messages received from clients are printed in the terminal, with their source client.

- Clients : Then, I sent 'Hello', 'Can you hear me', 'Yes I can" with the clients 1,2 and 3 respectively. Each time a message was sent with a client, the server notified all clients that he received a message, with its content.
