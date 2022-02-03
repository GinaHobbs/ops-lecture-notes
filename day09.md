# Email

## Inbound Protocols

POP3 = Post Office Protocol 3.
	Allows downloading of messages from a mail server, the mail is then deleted off the server. These messages can be viewed offline.

IMAP = Internet Message Acces Protocol.
	An inbound configuration that will allow you to manage a mailbox from multiple devices and synchronize with the mail server, which keeps a copy of all received emails.

MAPI =
	Protocol used by Microsoft Exhange Servers that communicate with their clients, Microsoft Outlook. Uses RPC encryption. Dynamically assigned port numbers.

## Outbound Protocols

SMTP = Simple Mail Transfer Protocol

## Email File Extensions

.eml
.emlx
.msg
.mbx

## Email Contents

Address, Subject, Attachment, Body (Raw Text or HTML)

## mxtoolbox.com

Shows everything you can possibly imagine about an email.

## How does an email get from one pc to another on different networks?

The email is generated on a client pc and is sent to the mail server on SMTP port 25. It is then sent out from the mail server through SMTP port 25 to a router on the internet. It then hops along multiple routers on the internet until it is delivered to the mail server with the matching domain from the client pc. It is then sent to the client pc with the mathich IP address.
