# Flutter Stateful Widget Lifecycle

Stateful Widget create state using State Class.

State class has lifecycle methods.

-> initState() - To initialize the state, It gets called only once when the widget is created.
 
->didUpdateWidget(Widget oldWidget) - to compare the old widget which got changed because the parent configuration got changed with the current widget. It gets called of the parent widget setState() called and it changes it's state.

->build() - To build or create the widget.

->dispose() - To clear any observable or IO operations. It gets called when the widget is getting removed from the widget tree.

Here is the [Video Link](https://youtu.be/gksFK1zitls)

Previous [video](https://youtu.be/cPole6aF_2c) of what Stateless widget and what is Stateful widget.


## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).
