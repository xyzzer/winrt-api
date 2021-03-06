---
-api-id: P:Windows.UI.Notifications.ScheduledToastNotification.SnoozeInterval
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.IReference<Windows.Foundation.TimeSpan> SnoozeInterval { get; }
-->

# Windows.UI.Notifications.ScheduledToastNotification.SnoozeInterval

## -description
Gets the amount of time between occurrences of the notification.

## -property-value
The time between occurrences of the notification. This value will be between 60 seconds and 60 minutes, inclusive.

## -remarks
This value is set when the [ScheduledToastNotification](scheduledtoastnotification.md) object is created.

## -examples

## -see-also
[Scheduled notifications sample](http://go.microsoft.com/fwlink/p/?linkid=241614), [Toast schema](XREF:TODO:toast.Schema_Root), [Guidelines and checklist for scheduled notifications](XREF:TODO:m_ui_tiles.guidelines_for_scheduled_notifications)