---
-api-id: P:Windows.UI.Notifications.ScheduledTileNotification.DeliveryTime
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.DateTime DeliveryTime { get; }
-->

# Windows.UI.Notifications.ScheduledTileNotification.DeliveryTime

## -description
Gets the time at which the tile is scheduled to be updated.

## -property-value
The date and time that the notification will be updated.

## -remarks
This value is set when the [ScheduledTileNotification](scheduledtilenotification.md) is created. For the tile to be updated at the specified time, the notification must be added to the schedule through the [TileUpdater.addToSchedule](tileupdater_addtoschedule.md) method.

## -examples

## -see-also
[Scheduled notifications sample](http://go.microsoft.com/fwlink/p/?linkid=241614), [Guidelines and checklist for scheduled notifications](http://msdn.microsoft.com/library/ca9e9121-d1b1-461f-9c7e-b25225d917ca)