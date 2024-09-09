# Message Session Relay Protocol
The Message Session Relay Protocol (MSRP, see RFC 4975) can be used in applications to receive and send text messages from callers and call takers. It may also be used to send messages containing binary content such as images or to send private messages between members of a conference.

The SipLib.Msrp namespace contains classes for working with calls that have MSRP media. The main class is called [MsrpConnection](~/api/SipLib.Msrp.MsrpConnection.yml). This class can be used to send and receive text messages as text/plain or message/cpim. This class also supports sending and receiving binary content.

The [Samples/MSRP](https://github.com/PhrSite/SipLib/tree/master/Samples/MSRP) directory of the SipLib GitHub repository contains two sample applications that demonstrate how to work with MSRP media for SIP calls.


