---
-api-type: winrt method
---
 You cannot access a valid [Parent](../windows.ui.xaml/frameworkelement_parent.md) property value from an override of [OnNavigated](page_onnavigatedto.md). If you need to access the [Parent](../windows.ui.xaml/frameworkelement_parent.md) property, do so in a [Loaded](../windows.ui.xaml/frameworkelement_loaded.md) event handler.
 You cannot use [OnNavigatedTo](page_onnavigatedto.md) for element manipulation or state change of controls on the destination page. Instead, attach a [Loaded](../windows.ui.xaml/frameworkelement_loaded.md) event handler at the root of the newly loaded page's content, and perform any element manipulations, state changes, event wiring and so on in the [Loaded](../windows.ui.xaml/frameworkelement_loaded.md) event handler.