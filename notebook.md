# My Coding Notebook
Click here to learn more → [About Me](about.md)

## Note 1
### Flutter Notes

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
### Coding Notes

---
### Key Terms and Definitions
| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|--|--|--|--|--|
| Variable | A named container used to store a value that may change. | `var x = 5;` | A container for stuff. | In main.dart, title: 'TSA Portfoilo' |
| Constant | A fixed value that cannot change once set. | `const PI = 3.14;` | A Constant in a science expariment. | In main.dart, const MyPortfolioApp({super.key)} |
| Data Type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | A container that holds only one type of data. | In main.dart, bool, debugShowCheckedModeBanner: false, |
| String | A sequence of characters used to represent words or text. | `"Hello World"` | A text message. | In home.dart, const Text('HI EVERYONE,\nWelcome to my', style: TextStyle( |
| Integer | Whole number values. | `int age = 16;` | Basic math. | N/A |
| Double | Number values with decimals. | `double age = 16.2;` | Hard math. | N/A |
| Boolean | A value that can be true or false. | `bool isLoggedIn = false;` | A yes or no question. | In main.dart, debugShowCheckedModeBanner: false, |
| List | A collection of values in a specific order. | `List<String> names = [];` | A list of questions, in an ordered test. | In showcase.dart, final List<String> puppyUrls = ['https://placedog.net/640/482?random', 'https://placedog.net/640/481?random', |
| Null | A special value that means “nothing.” | `String? name = null;` | The funny number, used to break games sometimes. Baically void-lite. | N/A |
| Function | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` | A machine that does one thing. | N/A |
| Paramater | The information passed into a function to change how it works. | `greet(String name)` | The inputs for a machine. | N/A |
| Return | The result a function gives back. | `return total;` | An intern who returns expariment data. | In alt_design_screen.dart, return Scaffold(body: ListView( |
| Scope | Where a variable or function can be used. | (No set syntax — concept-based) | Where to put a specalized machine in a production line. | Can't really show a concept unless I show the whole program... |
| Class | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | The structure of something. | in alt_design_screen.dart, class AltDesignScreen extends StatelessWidget {const AltDesignScreen({super.key}); |
| Object | A specific version of a class. | `Dog myDog = Dog();` | A specific structure of something. | N/A |
| Property | A variable that belongs to a class/object. | `String name;` | The substance of a coffee, or the amount of coffee in a cup. | N/A |
| Method | A function that belongs to a class. | `void bark() {}` | A studet making notes. | (?) In alt_design_screen.dart, class AltDesignScreen extends StatelessWidget { |
| Constructor | A special function used to set up a class when it’s created. | `Dog(this.name);` | When you enroll, you need to create a new student account. | N/A, unknown. |
| Abstraction | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) | The engine under a hood of a car. | Us looking in Flutter. |
| Override | Changing how a built-in or inherited function behaves. | `@override` | An override switch for a water pump. | @override Widget build(BuildContext context) { |
| Void | A function that does not return a value. | `void printMessage() {}` | A black hole. A vanishing point. A one way portal. | In main.dart, void main() => runApp(MyPortfolioApp()); | 
---

## Note 3
### Coding Notes

---
### Key Terms and Definitions
## Flutter Definitions
| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|--|--|--|--|--|
| main() | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` | The alternator when the engine starts. | In main.dart, void main() => runApp(MyPortfolioApp()); |
| MaterialApp | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` | A painter and naviagtor in one. | return MateruakAoo(debugShowCheckedModeBanner: false, title: 'TSA Portfolio' and more. |
| Scaffold | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` | A framework of a building. | In showcase.dart, return Scaffold(body: Column(mainAxisAlignment: mainAxisAlignment.start, children: [ |
| Column | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` | A pillar of text. | In showcase.dart, child: Column(children: [const Padding( |
| Row | A widget that shows things side-by-side. | `Row(...)` | A line of text. | In info_card.dart, child: Row(children: [ClipRRect( |
| Container | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` | HTML's boxer model. | In info_card.dart, return Container(margin: const EdgeInsets.symmetric(vertical: 8, horizontal: 16), |
| Text | A widget to display text on the screen. | `Text('Hello')` | Text. | in showcase.dart, text: "HERE'S A SHOWCASE\nOF ", style: TextStyle(color: Colors.white), |
| Image.network | A widget to show an image using a link from the internet. | `Image.network('https://...')` | A network of pictures, like on google. | In showcase.dart, child: Image.network(url, width: 100, height: 100, fit: BoxFit.cover), |
| ElevatedButton | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` | A button. | In showcase.dart, ElevatedButton(onPressed: () => Navigator.pushNamed(context, '/alt'), |
| onPressed | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` | A button's output. | In showcase.dart, onPressed: () => Navigator.pushNamed(context, '/alt'), |
| StatelessWidget | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` | A still rock, that never moves. | In showcase.dart, class ShowcaseScreen extends StatelessWidget {const ShowcaseScreen({super.key}); |
| StatefulWidget | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` | Flowing water, can and will change. | N/A |
| Naviagtor | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` | A skilled hiking guide. | In showcase.dart, onPressed: () => Navigator.pushNamed(context, '/alt'), child: const Text('Alternate Design'), |
| Padding | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` | A space around an ad on a billboard. | In showcase.dart, Padding(padding: const EdgeInsets.only(left: 100.0), child: Column( |
| Center | Aligns content in the center of the screen or container. | `Center(child: ...)` | Centering a sight. | In showcase.dart, textAlign: TextAlign.center, |
| Wrap | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` | A space-saver who crams as much as possible into one box. | In showcase.dart, Wrap(alignment: WrapAlignment.center, children: puppyUrls.map((url) => puppyImage(url)).toList()), ElevatedButton( |
| @override | This marks a method as one that’s replacing a method in a parent class. | `@override` | An override switch in a factory. | @override Widget build(BuildContext context) {final List<String> puppyUrls = [ |
| build() | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` | A painter. | In info_card.dart, Widget build(buildContext context) { return Container( |
| BuildContext | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` | A schedule. | In info_card.dart, Widget build(buildContext context) { return Container( |
| super.key | A keyword used to pass a value to the parent widget. | `super.key` | Someone who passes a unique number to someone. | In showcase.dart, const ShowcaseScreen({super.key}) |
| const | A keyword that means the value won't change and is set once. | `const` | A set value. | In showcase.dart, const ShowcaseScreen({super.key}) |
---

## Personal Note 1
### BendGameStudios file system.

### Key Terms and Definitions
| Term | Definiton | Conversion Rate | Other Notes |
|--|--|--|--|

## Other
At the top, begin a table of contents, Ex.:
## Table of Contents
- [Day 1](#day-1)
  - [Notes](#notes)
  - [Practice](#practice)
- [Day 2](#day-2)

[Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

Text Formatting:

Highlight important ideas or add emphasis.
Use bold for key terms or definitions.
Use italic for emphasis or side comments.
Use inline code for keywords, functions, or commands.

 

Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

Code Blocks:

When to use: Anytime you write multiple lines of code.
Inline code for short snippets.
Fenced code blocks with language for full examples.

Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

Lists:

When to use: Organize steps, notes, or key points.
Numbered lists for sequences or steps.
Bulleted lists for unordered ideas.

Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

Checklists
When to use: Track progress on assignments or tasks.

Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

Blockquotes:

When to use: Call out notes, reminders, or teacher comments.

Example:

> Remember: Loops repeat code until a condition is false.

 

Tables:

When to use: Compare values, track progress, or organize data neatly.

Example:

---
| Tasks | Status | Notes |
|--|--|--|
| Homework 1 | Done | Submitted |
| Homework 2 | Pending | Needs review |
---
 

Links & Images:

When to use: Add references, resources, or visuals.

Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

Collapsible Sections:

When to use: Hide solutions, extended notes, or extra details.

Example:

<details>
  <summary>Click to reveal solution</summary>
System.out.println("Answer: 42");
</details>

Footnotes:

When to use: Add references or side notes without cluttering the page.

Example:

This concept is related to object-oriented programming.[^1]
[^1]: See "Objects and Classes" in your textbook.

Style Rules:

Consistency matters more than creativity.
Always use headings to structure your notes.
Always use code blocks for multi-line code.
Clarity first.
Bold key terms.
Use lists instead of long sentences when outlining steps.
Professional tone.
Don’t mix casual notes with formal work in the same section.
Use blockquotes for reflections or teacher feedback.
Track your learning.
Use checklists to mark what’s done.
Use collapsible sections if you want to hide answers until review time. 

Bottom Line:

Headings = Structure
Bold/Italic = Emphasis
Code blocks = Code
Lists = Steps/Ideas
Tables = Organization
Checklists = Progress
Blockquotes = Notes/Tips
Collapsible = Hide/Show detail
Keep it simple, consistent, and clear.
