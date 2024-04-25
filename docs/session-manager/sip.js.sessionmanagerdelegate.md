<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [SessionManagerDelegate](./sip.js.sessionmanagerdelegate.md)

## SessionManagerDelegate interface

Delegate for [SessionManager](./sip.js.sessionmanager.md)<!-- -->.

<b>Signature:</b>

```typescript
export interface SessionManagerDelegate 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [onCallAnswered(session)](./sip.js.sessionmanagerdelegate.oncallanswered.md) | Called when a call is answered. |
|  [onCallCreated(session)](./sip.js.sessionmanagerdelegate.oncallcreated.md) | Called when a call is created. |
|  [onCallDTMFReceived(session, tone, duration)](./sip.js.sessionmanagerdelegate.oncalldtmfreceived.md) | Called when a call receives an incoming DTMF tone. |
|  [onCallHangup(session)](./sip.js.sessionmanagerdelegate.oncallhangup.md) | Called when a call is hung up. |
|  [onCallHold(session, held)](./sip.js.sessionmanagerdelegate.oncallhold.md) | Called when a call is put on hold or taken off hold. |
|  [onCallReceived(session)](./sip.js.sessionmanagerdelegate.oncallreceived.md) | Called when a call is received. |
|  [onMessageReceived(message)](./sip.js.sessionmanagerdelegate.onmessagereceived.md) | Called upon receiving a message. |
|  [onNotificationReceived(notification)](./sip.js.sessionmanagerdelegate.onnotificationreceived.md) | Called upon receiving a notification. |
|  [onRegistered()](./sip.js.sessionmanagerdelegate.onregistered.md) | Called when user is registered to received calls. |
|  [onServerConnect()](./sip.js.sessionmanagerdelegate.onserverconnect.md) | Called when user is connected to server. |
|  [onServerDisconnect(error)](./sip.js.sessionmanagerdelegate.onserverdisconnect.md) | Called when user is no longer connected. |
|  [onUnregistered()](./sip.js.sessionmanagerdelegate.onunregistered.md) | Called when user is no longer registered to received calls. |
