# Contributor's guide

This guide is for everyone who want's to contribute to the development of NodeGui.

Please make sure you have read the [User's guides](https://docs.nodegui.org/#/) before reading this guide.

- [Setting up the NodeGui Contributor's Environment](/docs/development/setting-up.md)
  - [Setting up macOS](/docs/development/setting-up.md#macosx)
  - [Setting up Windows](/docs/development/setting-up.md#windows)
  - [Setting up Linux](/docs/development/setting-up.md#linux)
- [Getting started](/docs/development/getting-started.md)
  - [Code Structure](/docs/development/getting-started.md#Code-Structure)
  - [Wrapping a widget: TLDR version](/docs/development/getting-started.md#Wrapping-a-widget)
  - [Learning Materials](/docs/development/getting-started.md#Learning-Materials)
- [Styling](/docs/development/styling.md)
  - [Painting](/docs/development/styling.md#painting)
  - [Layout](/docs/development/styling.md#layout)
- [Signal and Event Handling](/docs/development/signal_and_event_handling.md)
- [Debugging](/docs/development/debugging.md)
- [Common Errors](/docs/development/common_errors.md)
- [Wrapping a Widget: Detailed](/docs/development/wrapping_widgets.md)
- [Getting Support](/docs/tutorial/support.md)


# Where to start or How can you help?

 You can follow the contributors guide above to get a gist.

 It is fairly straightforward to get started. I would start with a project of my own and start adding missing functionalities.
 
 Or simply put I would recommend you start by adding an unexported method to an existing widget.
 
 **For example:**
 
 You could add the corresponding Qt method to QProgressbar
 https://doc.qt.io/qt-5/qprogressbar.html#textVisible-prop to get a grip on it.

 This PR can be used as a guide
 
 https://github.com/nodegui/nodegui/issues/36
 
 https://github.com/nodegui/nodegui/pull/39

 You can also take a look at few bugs or the issue board here to know what you can pick up if you are out of ideas.
 
 https://github.com/nodegui/nodegui/projects/
 
 https://github.com/nodegui/react-nodegui/projects/
