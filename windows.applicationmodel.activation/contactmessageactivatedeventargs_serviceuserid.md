---
-api-id: P:Windows.ApplicationModel.Activation.ContactMessageActivatedEventArgs.ServiceUserId
-api-type: winrt property
---

<!-- Property syntax
public string ServiceUserId { get; }
-->

# Windows.ApplicationModel.Activation.ContactMessageActivatedEventArgs.ServiceUserId

## -description
Gets the user identifier of the service used for the message.

## -property-value
The user identifier of the service used for the message.

## -remarks
For standard text messaging, the ServiceUserId property is set to the mobile number for the contact. For web-based services, the ServiceUserId property is set to the contact’s user id for that particular service.

For info about how to handle app activation through contact actions, see [Quickstart: Handling contact actions ](https://docs.microsoft.com/previous-versions/windows/apps/dn518236(v=win.10)) and [Quickstart: Handling contact actions ](https://docs.microsoft.com/previous-versions/windows/apps/dn518338(v=win.10)).

## -examples

## -see-also
[Handling Contact Actions sample](https://go.microsoft.com/fwlink/p/?LinkID=320151)
