---
UID: NF:uiautomationclient.IUIAutomation6.AddEventHandlerGroup
title: IUIAutomation6::AddEventHandlerGroup (uiautomationclient.h)
description: Registers a collection of event handler methods specified with the CreateEventHandlerGroup.
old-location: winauto\uiauto_IUIAutomation6_AddEventHandlerGroup.htm
tech.root: WinAuto
ms.assetid: 8F131A7C-BC03-4967-9ED8-624086DEA112
ms.date: 12/05/2018
ms.keywords: AddEventHandlerGroup, AddEventHandlerGroup method [Windows Accessibility], AddEventHandlerGroup method [Windows Accessibility],IUIAutomation6 interface, IUIAutomation6 interface [Windows Accessibility],AddEventHandlerGroup method, IUIAutomation6.AddEventHandlerGroup, IUIAutomation6::AddEventHandlerGroup, uiautomationclient/IUIAutomation6::AddEventHandlerGroup, winauto.uiauto_IUIAutomation6_AddEventHandlerGroup
ms.topic: method
f1_keywords:
- uiautomationclient/IUIAutomation6.AddEventHandlerGroup
dev_langs:
- c++
req.header: uiautomationclient.h
req.include-header: UIAutomation.h
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1809 [desktop apps only]
req.target-min-winversvr: Windows Server, version 1709 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: UIAutomationClient.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- UIAutomationClient.h
api_name:
- IUIAutomation6.AddEventHandlerGroup
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: RS5, 19H1
---

# IUIAutomation6::AddEventHandlerGroup


## -description


Registers a collection of event handler methods specified with the <a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nf-uiautomationclient-iuiautomation6-createeventhandlergroup">CreateEventHandlerGroup</a>.
<div class="alert"><b>Important</b>  Microsoft UI Automation clients should use the handler group methods to register event listeners instead of individual event registration methods defined in the various <a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nn-uiautomationclient-iuiautomation">IUIAutomation</a> namespaces.</div><div> </div>

## -parameters




### -param element [in]

A pointer to the UI Automation element associated with the event handler group.


### -param handlerGroup

A collection of UI Automation event listeners.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



Before implementing an event handler, you should be familiar with the threading issues described in <a href="https://docs.microsoft.com/windows/desktop/WinAuto/uiauto-threading">Understanding Threading Issues</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nn-uiautomationclient-iuiautomation6">IUIAutomation6</a>



<a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nf-uiautomationclient-iuiautomation6-removeeventhandlergroup">RemoveEventHandlerGroup</a>
 

 

