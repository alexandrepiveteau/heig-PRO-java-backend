# HTTP Error codes
For this project, there is a certain number of request that can be sent from the android client to the backend. Here is a list of certain http response codes that can be received in certain cases :

| Code | Detail(s) |
|:----:|--------------|
|200   | The request is correct and the response was sent |
|400   | Bad request, can happen when a client enters a wrong emoji code for exemple |
|403   | Forbidden action, the request was correct but given with the wrong token value |
|404   | The requested resource could not be found but may be available in the future. For exemple, the client requests the question 4 from poll 1 of moderator 1, and said question does not exist **yet** |
|405   | Method not allowed, can happen if the client tries to connect to a session without a token |
