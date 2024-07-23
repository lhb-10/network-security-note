# 7. Application Layer

## Application Layer Protocol in Computer Network


1. TELNET
2. FTP
3. TFTP
4. NFS
5. SMTP
6. LPD
7. X window
8. SNMP
9. DNS
10. DHCP
11. HTTP/HTTPS
12. POP
13. IRC
14. MIME
15. ...

## HTTP
## FTP
## SMTP, POP3, IMAP
> https://www.geeksforgeeks.org/simple-mail-transfer-protocol-smtp/


| S.No.  | Keywor  | Command form   | Description   | Usage   |
| --- |  --- |  --- |  --- |  --- |
| 1. | HELO | HELO<SP><domain><CRLF> | It provides the identification of the sender i.e. the host name. | Mandatory |
| --- |  --- |  --- |  --- |  --- |
| 2. | MAIL | MAIL<SP>FROM : <reverse-path><CRLF> | It specifies the originator of the mail. | Mandatory |
| 3. | RCPT | RCPT<SP>TO : <forward-path><CRLF> | It specifies the recipient of mail. | Mandatory |
| 4. | DATA | DATA<CRLF> | It specifies the beginning of the mail. | Mandatory |
| 5. | QUIT | QUIT<CRLF> | It closes the TCP connection. | Mandatory |
| 6. | RSET | RSET<CRLF> | It aborts the current mail transaction but the TCP connection remains open. | Highly recommended |
| 7. | VRFY | VRFY<SP><string><CRLF> | It is use to confirm or verify the user name. | Highly recommended |
| 8. | NOOP | NOOP<CRLF> | No operation | Highly recommended |
| 9. | TURN | TURN<CRLF> | It reverses the role of sender and receiver. | Seldom used |
| 10. | EXPN | EXPN<SP><string><CRLF> | It specifies the mailing list to be expanded. | Seldom used |
| 11. | HELP | HELP<SP><string><CRLF> | It send some specific documentation to the system. | Seldom used |
| 12. | SEND | SEND<SP>FROM : <reverse-path><CRLF> | It send mail to the terminal. | Seldom used |
| 13. | SOML | SOML<SP>FROM : <reverse-path><CRLF> | It send mail to the terminal if possible; otherwise to mailbox. | Seldom used |
| 14. | SAML | SAML<SP>FROM : <reverse-path><CRLF> | It send mail to the terminal and mailbox. | Seldom used |

| SMTP | POP | IMAP |
| --- |  --- |  --- |
| Stands for Simple mail transfer protocol | Stands for [Post Office Protocol.](https://www.geeksforgeeks.org/pop-full-form/) | Stands for [Internet Message Access Protocol.](https://www.geeksforgeeks.org/internet-message-access-protocol-imap/) |
| --- |  --- |  --- |
| Used for sending mail. | Used for retrieving mail. | Used for retrieving mail. |
| it is push [protocol](https://www.geeksforgeeks.org/network-protocols/). | it is pull protocol. | it is pull protocol. |
| It work between sender's mail server to receiver's mail server and sender and sender's mail server. | It work between receiver and receiver's mail server. | It works between receiver and receiver's mail server. |
| It does not store mail on server it just send the mail. | It download all the mail when it connected to internet. | It store all mail on server and download when it get request to download. |
| Works on TCP port number 25. | Works on TCP port number 110. | Works on TCP port number 143. |
| Connection oriented protocol. | Connection oriented protocol. | Connection oriented protocol. |
| It has persistence TCP connection. | It has persistence TCP connection. | It has persistence TCP connection. |
| [Stateless](https://www.geeksforgeeks.org/difference-between-stateless-and-stateful-protocol/) protocol. | Stateful protocol. | Stateful protocol. |
| It is in band protocol. | It is in band protocol. | It is in band protocol. |
| Not used at receiver side. | Used at receiver side. | Used at receiver side. |

## DNS
> https://www.geeksforgeeks.org/domain-name-system-dns-in-application-layer/


## DHCP
## TELNET

## Question 
> What are some common protocols found in application layer?
> > HTTP, FTP, SMTP, DNS, POP, SNMP, LDS etc.
## References
* [ ] https://www.geeksforgeeks.org/protocols-application-layer/