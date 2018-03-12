# a4wExtensibility
Sage 300 Extensibility - Customization Framework for Sage 300 Desktop

Enabling extensibility is a framework for extending Sage 300 screens with additional controls and logic.

The framework allows customizations of the Sage 300 screen to be placed in a discreet Active X DLL.  Each screen can load multiple extensions, allowing layering of customizations.

The framework hosts the Sage 300 screen and they layered customizations with a custom container.  The container is called a4wContainerXP.Extensibility.exe and is hosted in the RUNTIME directory.

An icon to this EXE is created which will dynamically create the Sage 300 screen and then layer the customizations overtop of the screen.  As the Sage 300 screens are dynamically created, an extension can work across multiple versions of Sage 300.  

The a4wContainerXP.Extensibility can completely replace the main Sage 300 container (a4wContainerXP) to allow customization loading in any Sage 300 screen.  Aside from the obvious benefit of being able to automatically load customizations into any Sage 300 screen, there are drawbacks.  As at October 2017 the extensibility bootstrap application does not support title bar colours and does not support some third party modules.


