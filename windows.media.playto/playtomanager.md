---
-api-id: T:Windows.Media.PlayTo.PlayToManager
-api-type: winrt class
---

<!-- Class syntax.
public class PlayToManager : Windows.Media.PlayTo.IPlayToManager
-->

# Windows.Media.PlayTo.PlayToManager

## -description
Provides access to Play To capabilities.

## -remarks
<!--{annotation author="v-shawja" time="1/26/2012 5:39:32 PM"}In the first sentence of the following paragraph, note that MSTP generally prefers "destination" over "target". Please make that change if it would be accurate. Or "target" can simply be deleted if it's unnecessary.-->
If your application includes audio, video, or image elements, users can stream the media source for those elements to a Play To target device. You can use the [PlayToManager](playtomanager.md) class to customize the Play To experience for users. You can disable the default behavior by using the [DefaultSourceSelection](playtomanager_defaultsourceselection.md) property.You can select which media is streamed by using the [SourceRequested](playtomanager_sourcerequested.md) event. And you can display the Play To UI in place of the **Devices** charm by using the [ShowPlayToUI](playtomanager_showplaytoui.md) method.

In Play To, video starts from the current position. If you want to start the video from the beginning, simply seek to the beginning of the video as soon as the Play To connection is established.

PlayTo apps will not be suspended as long as video or music is playing on the Play To receiver or images are continuously sent to the Play To receiver. Apps have approximately 10 seconds to send a new image after the current one is displayed and approximately 10 seconds to send the next audio or video after the current one has ended.

For an example of how to use Play To in an application, see [Quickstart: Using Play To in applications (JavaScript)](XREF:TODO:m_playto.using_playto_in_applications) or [PlayReady DRM](http://msdn.microsoft.com/library/dd8ffa8c-dff0-41e3-8f7a-345c5a248fc2).

## -examples


> [!div class="tabbedCodeSnippets"][!code-cs[SourceRequested](../windows.media.playto/code/PlayTo_Reference/csharp/MainPage.xaml.cs#SnippetSourceRequested)][!code-js[SourceRequested](../windows.media.playto/code/PlayTo_Reference/javascript/default.js#SnippetSourceRequested)][!code-vb[SourceRequested](../windows.media.playto/code/PlayTo_Reference/vbnet/MainPage.xaml.vb#SnippetSourceRequested)]

## -see-also
[Play To sample](http://go.microsoft.com/fwlink/p/?linkid=245166), [PlayToReceiver sample](http://go.microsoft.com/fwlink/p/?linkid=245167), [Media Server sample](http://go.microsoft.com/fwlink/p/?linkid=245168)
