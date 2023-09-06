---
title: "Stateless And Stateful Widgets Just Like The States And Capital"
datePublished: Mon Sep 06 2021 19:00:00 GMT+0000 (Coordinated Universal Time)
cuid: clm7zny7a000d0amr5f7pavsq
slug: stateless-and-stateful-widgets-just-like-the-states-and-capital
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1694019728500/903f690e-82a0-4f9b-8ca8-ecc6934e360c.png
tags: flutter, android, flutter-widgets

---

<mark>Some context: This Article is written to appeal to the African tech Ecosystem.</mark>

I remember reciting the Nigerian States and its capital when I was much younger in primary school around Grade 4. The weird thing about that experience was that it was a criterion to *go for a break* - (have lunch and play with your friends before coming back to the class).

Not to brag too much, but I still have my A-game on and ready to run through 5 out of the 36 states under 5 seconds. You heard me right!

That said, how do we link this to stateless and stateful widgets in Flutter?

No vex! (*don’t be annoyed*). There's no way to link the states and capital to stateless and stateful widgets in Flutter.

However, if you followed through up to this point it means you have a great attention span to finish up to the end of this piece and also have heard of Flutter and how efficient it is in building cross-platform applications.

I have included in this article, two $1 tips each and hope you find it useful. So let’s dive in!

All the UI components in Flutter are known as widgets. A widget that contains all the code for a single screen of an application is either stateful or stateless. But how are they different?

## Stateful Widgets

If a widget can change for example when a user interacts with it, it’s stateful. It’s that simple but if you *get a coconut head like* me and love to learn the hard way, here’s a narrative: Stateful widgets have a mutable state, i.e., they are mutable and can be drawn multiple times within the application is in action- during its lifetime.

These are widgets that can change their state multiple times and can be redrawn on to the screen any number of times while the application is in action.

Here’s a typical structure of a stateful widget I believe you must have seen before

![carbon (2).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1610459881358/_K6FiN2Gh.png align="left")

The name of the widget in the structure above is “FavoriteWidget”, but now it overrides the “createState” method, instead of the “build” method, which returns the instance of the class “\_FavoriteWidgetState”.

The class “\_FavoriteWidgetState” extends from State&lt;&gt; which takes “FavoriteWidget” as a template input.

Now, this “\_FavoriteWidgetState” overrides the “build” method and returns a widget. This is where you can define the UI of the app, which is Stateful. With it being a Stateful widget, you can call the build method any number of times, which will redraw the widgets on the screen.

### $1 TIP

Stateful Widgets can be quickly built-in VS Code or Android Studio by using the “stf” shortcut.

### Examples of Stateful Widgets

Checkbox, Radio, Slider, InkWell, Form, and TextField are examples of stateful widgets.

## Stateless Widgets

As opposed to stateful widgets, a stateless widget never changes. Meaning that they do not require a mutable state, i.e., it is immutable. Stateless widgets unlike stateful widgets cannot change their state, particularly during the application runtime. This implies that the widgets cannot be redrawn while the application is in action.

Here’s the basic structure of a Stateless Widget:

![carbon (3).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1610459894113/YlPL6zJP_.png align="left")

The name of this Stateless Widget from the code snippet is “FavoriteStatelessWidget”, inside which we have to override the “build” method. The build in the method takes in a “BuildContext” as the parameter and returns a widget. That’s why the return type of the build method is a widget. And this is where the UI of this app screen can be designed, which is Stateless.

Just a heads up right here, In a Stateless widget, the “build” method can only be called ONCE while the app is in action, which is responsible for drawing the widgets onto the device screen.

### $1 TIP

Stateless Widgets can be quickly built in VS Code or Android Studio by using the “stless” shortcut.

## Conclusion

Stateful and Stateless widgets both have their use cases. However, a Stateless widget comes in handy when the part of the user interface being described does not depend on anything other than the configuration information and the BuildContext whereas a Stateful widget is useful when the part of the user interface changes dynamically. This concludes this article, and I hope you all have now understood the basic idea of Stateful and Stateless widgets. These concepts would be clearer if you do some projects on your own and get the feel of how the application handles the state.

If you are looking to get started learning Flutter, you can check out the course by Angela Yu. Also, my motivation for this article comes from my #2Weeks1Article challenge with the whole idea centered on starting small and staying consistent.

## References

https://flutter.dev/docs/development/ui/interactive

https://malshikay.medium.com/stateless-and-stateful-widgets-in-flutter-1b64617c25e2

https://stackoverflow.com/questions/56222962/how-to-change-from-stateless-widget-to-stateful-widget

https://medium.com/flutter-community/flutter-stateful-vs-stateless-db325309deae#:~:text=Stateful%20widgets%20have%20a%20mutable,the%20app%20is%20in%20action.

https://medium.com/flutter-community/flutter-stateful-vs-stateless-db325309deae

https://medium.com/@arpitgupta1250/stateless-and-stateful-widget-in-flutter-f082092f4179