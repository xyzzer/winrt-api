---
-api-id: M:Windows.Networking.Proximity.PeerFinder.Stop
-api-type: winrt method
---

<!-- Method syntax
public void Stop()
-->

# Windows.Networking.Proximity.PeerFinder.Stop

## -description
Stops advertising for a peer connection.

## -remarks
You can call the [Stop](peerfinder_stop.md) method to stop the [PeerFinder](peerfinder.md) when you no longer want to advertise for or accept new triggered (tapped) or browsed connections. [Stop](peerfinder_stop.md) does not close an existing connection. However, the [Stop](peerfinder_stop.md) method will cancel outstanding calls to the [ConnectAsync](peerfinder_connectasync.md) method and triggered connection requests. The [Stop](peerfinder_stop.md) method does not wait for the cancellation to complete.

## -examples


[!code-js[FindPeers](../windows.networking.proximity/code/Proximity_FindAllPeersAsync1/js/default.js#SnippetFindPeers)]

> [!div class="tabbedCodeSnippets"][!code-cs[Connect_CS](../windows.networking.proximity/code/Proximity_FindAllPeersAsync1/csharp/BlankPage.xaml.cs#SnippetConnect_CS)][!code-vb[Connect_CS](../windows.networking.proximity/code/Proximity_FindAllPeersAsync1/vbnet/BlankPage.xaml.vb#SnippetConnect_CS)]

## -see-also
[Start](peerfinder_start.md), [Proximity and Tapping (JavaScript)](http://msdn.microsoft.com/library/84a30dcf-ef14-4a93-9e7c-7a3de867d46b), [Proximity and Tapping (C#/VB/C++)](http://msdn.microsoft.com/library/f25bb1df-1cfd-45cd-8c67-04eec73ebfbd), [Proximity sample](http://go.microsoft.com/fwlink/p/?linkid=245082)

## -capabilities
proximity, ID_CAP_PROXIMITY [Windows Phone], ID_CAP_NETWORKING [Windows Phone]
