Java uses "Properties" to subscribe to changes, following the Observer model. The premade properties are all subclasses of [javafx.beans.property](https://docs.oracle.com/javafx/2/api/javafx/beans/property/package-summary.html) and can be reviewed in the documentation linked.

I can create my own properties by implementing the [ObservableValue<T>](https://docs.oracle.com/javafx/2/api/javafx/beans/value/ObservableValue.html) interface.
