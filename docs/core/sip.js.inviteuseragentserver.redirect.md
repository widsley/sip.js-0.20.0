<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [InviteUserAgentServer](./sip.js.inviteuseragentserver.md) &gt; [redirect](./sip.js.inviteuseragentserver.redirect.md)

## InviteUserAgentServer.redirect() method

13.3.1.2 The INVITE is Redirected If the UAS decides to redirect the call, a 3xx response is sent. A 300 (Multiple Choices), 301 (Moved Permanently) or 302 (Moved Temporarily) response SHOULD contain a Contact header field containing one or more URIs of new addresses to be tried. The response is passed to the INVITE server transaction, which will deal with its retransmissions. https://tools.ietf.org/html/rfc3261\#section-13.3.1.2

<b>Signature:</b>

```typescript
redirect(contacts: Array<URI>, options?: ResponseOptions): OutgoingResponse;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contacts | <code>Array&lt;URI&gt;</code> | Contacts to redirect to. |
|  options | <code>ResponseOptions</code> | Redirect options bucket. |

<b>Returns:</b>

`OutgoingResponse`
