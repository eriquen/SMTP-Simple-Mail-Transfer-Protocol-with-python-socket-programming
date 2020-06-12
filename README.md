# SMTP-Simple-Mail-Transfer-Protocol-with-python-socket-programming
This client code can be used to interact with simple SMTP servers. This code use TCP protocol using socket programming.server.

### Requirement 
Python 2.7<br>

### Run Server
Open commmand prompt/terminal  and run:

```
E:\SMTP>python2 server.py
Server starting
Connection Establish
```

### Run client
Open commmand prompt/terminal  and run:

```
E:\SMTP>python2 client.py
220 Connection accepted from Eriquen-DESKTOP
250 Hello Eriquen-DESKTOP. Pleased to meet you.
From: eriquen@mail.com
250 OK
To: husni@mail.com
250 OK
354 Start mail input; end with <CRLF>.<CRLF>
Subject: Report Status
Message: Hi husni, what is our current report status?.
.
```

To end **Message** user need to send **"."*** to the the server

