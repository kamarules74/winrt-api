---
-api-id: M:Windows.UI.Notifications.TileUpdater.StartPeriodicUpdate(Windows.Foundation.Uri,Windows.UI.Notifications.PeriodicUpdateRecurrence)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public void StartPeriodicUpdate(Windows.Foundation.Uri tileContent, Windows.UI.Notifications.PeriodicUpdateRecurrence requestedInterval)
-->

# Windows.UI.Notifications.TileUpdater.StartPeriodicUpdate

## -description
Begins a series of timed content changes for the tile that the updater is bound to, beginning immediately.

## -parameters
### -param tileContent
The Uniform Resource Identifier (URI) from which the XML content of the tile update will be retrieved.

### -param requestedInterval
The frequency with which the Uniform Resource Identifier (URI) is polled for new tile content, following the initial update at *startTime*.

## -remarks

## -examples

## -see-also
[StartPeriodicUpdate(Uri, DateTime, PeriodicUpdateRecurrence)](tileupdater_startperiodicupdate_1369986471.md), [How to set up periodic notifications for tiles](/previous-versions/windows/apps/hh761476(v=win.10)), [Guidelines and checklist for periodic notifications](/windows/uwp/controls-and-patterns/tiles-and-notifications-periodic-notification-overview), [App tiles and badges sample](https://github.com/microsoftarchive/msdn-code-gallery-microsoft/tree/master/Official%20Windows%20Platform%20Sample/Windows%208.1%20Store%20app%20samples/99866-Windows%208.1%20Store%20app%20samples/App%20tiles%20and%20badges%20sample), [Quickstart: Sending a tile update](/previous-versions/windows/apps/hh465439(v=win.10)), [Tile and tile notification overview](/previous-versions/windows/apps/hh779724(v=win.10)), [The tile template catalog](/previous-versions/windows/apps/hh761491(v=win.10)), [Guidelines and checklist for tiles](/windows/uwp/controls-and-patterns/tiles-and-notifications-creating-tiles), [How to schedule a tile notification](/previous-versions/windows/apps/hh761473(v=win.10)), [How to set up periodic notifications for tiles](/previous-versions/windows/apps/hh761476(v=win.10)), [Tiles XML schema](/uwp/schemas/tiles/tilesschema/schema-root)
