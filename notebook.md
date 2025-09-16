# My Coding Notebook
Click here to learn more → [About Me](about.md)

## Note 1
## Flutter Notes

### What is Flutter?
- Definition:
Flutter is an open-sourse UI software development kit, utilizing Dart as it's main language. It's developed by Google LLC, and is used for both web and app development.
  
- Why is it useful?
Flutter allows us to easily develop highly interactive UI apps, compared to say HTML or plain old Java.

---
### Key Terms and Definitions
| Term | Definition | Example / Notes |
|--|--|--|
| Widget | A "design" feature, like Text or Image.network. | The universal building blocks. |
| MaterialApp | Core of a Flutter app. | Just the core. |
| Scaffold | Expands to fill the available space. | Automatically resizes for keyboards. |
| StatelessWidget | Does not redraw itself every value update. | The opposite of Stateful. |
| StatefulWidget | Redraws itself every value update. | The opposite of Stateless. |
| Navigator | Navigates between Routes. | Absoluetly nessasry for naviagation. |
| AppBar | Contains common actions at the top or bottom. | Otherwise known as a toolbar. |
| Column | Aligns many Wigets in a vertical row. | Useful for lists and the likes. |
| Row | Aligns many Wigets in a row. | It's just a row. |
| Container | Boxes. From HTML, basically. | The Boxer Model? |
| Text | Letters displayed on a screen. | Text('Hello, World!') |
| Image.network | Displays an image. | Image.network('source_URL') |
| Padding | Adds space around the text. | Functionally similar to HTML padding. |
| Center | Aligns the text to the center of the screen. | Functionally similar to HTML centering. |
---

### Layout and Design Widgets
- How do you center a widget?
  Center
  
- How do you align something to the left or right?
  Alignment
  
- What widget adds space around content?
  Padding
  
## Note 2
## Coding Notes

---
### Key Terms and Definitions
| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|--|--|--|--|--|
| Variable | A named container used to store a value that may change. | `var x = 5;` | A container for stuff. |  |
| Constant | A fixed value that cannot change once set. | `const PI = 3.14;` | A Constant in a science expariment. |  |
| Data Type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | A container that holds only one type of data.. |  |
| String | A sequence of characters used to represent words or text. | `"Hello World"` | A text message. |  |
| Integer | Whole number values. | `int age = 16;` | Basic math. |  |
| Double | Number values with decimals. | `double age = 16.2;` | Hard math. |  |
| Boolean | A value that can be true or false. | `bool isLoggedIn = false;` | A yes or no question. |  |
| List | A collection of values in a specific order. | `List<String> names = [];` | A list of questions, in an ordered test. |  |
| Null | A special value that means “nothing.” | `String? name = null;` | The funny number, used to break games sometimes. Baically void-lite. |  |
| Function | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` | A machine that does one thing. |  |
| Paramater | The information passed into a function to change how it works. | `greet(String name)` | The inputs for a machine. |  |
| Return | The result a function gives back. | `return total;` | An intern who returns expariment data. |  |
| Scope | Where a variable or function can be used. | (No set syntax — concept-based) | Where to put a specalized machine in a production line. |  |
| Class | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | The structure of something. |  |
| Object | A specific version of a class. | `Dog myDog = Dog();` | A specific structure of something. |  |
| Property | A variable that belongs to a class/object. | `String name;` | The substance of a coffee, or the amount of coffee in a cup. |  |
| Method | A function that belongs to a class. | `void bark() {}` | A studet making notes. |  |
| Constructor | A special function used to set up a class when it’s created. | `Dog(this.name);` | When you enroll, you need to create a new student account. |  |
| Abstraction | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) | The engine under a hood of a car. |  |
| Override | Changing how a built-in or inherited function behaves. | `@override` | An override switch for a water pump. |  |
| Void | A function that does not return a value. | `void printMessage() {}` | T H E  V O I D . (A black hole. A vanishing point. A one way portal.) |  | 
---

## Note 3
## Coding Notes

---
### Key Terms and Definitions
## Flutter Definitions
| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|--|--|--|--|--|
|  | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
|  | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |
|  | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |  |
|  | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|  | A widget that shows things side-by-side. | `Row(...)` |  |  |
|  | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|  | A widget to display text on the screen. | `Text('Hello')` |  |  |
|  | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|  | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|  | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|  | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|  | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|  | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|  | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
|  | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
|  | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|  | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|  | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
|  | Required in every widget class to describe what to show. | `build` |  |  |
|  | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|  | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|  | A keyword that means the value won't change and is set once. | `const` |  |  |
---

## Personal Note 1
## BendGameStudios file system.

### Key Terms and Definitions
| Term | Definiton | Conversion Rate | Other Notes |
|--|--|--|--|
