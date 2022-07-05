# Flutter Interview Questions

This repository is about common Flutter interview questions and their answers.

***🚀 If you find this repository useful, kindly give it a star ⭐***

<br />
<hr />

| Sl.No|  Questions       |
|------|------------------|
| 01 |[What is Flutter?](#q1-what-is-flutter)|
| 02 |[What is Dart and Why does Flutter use it?](#q2-what-is-dart-and-why-does-flutter-use-it)|
| 03 |[What is `pubspec.yaml` file and what does it do?](#q3-what-is-pubspecyaml-file-and-what-does-it-do)|
| 04 |[What is the difference between `main()` and `runApp()` functions in Flutter?](#q4-what-is-the-difference-between-main-and-runapp-functions-in-flutter)|
| 05 |[Differentiate between named parameters and positional parameters in Flutter.](#q5-differentiate-between-named-parameters-and-positional-parameters-in-flutter)|

<br />
<hr />

## Q1. What is Flutter?

Flutter is an open-source UI software development kit created by Google. It is used to develop cross platform applications for Android, iOS, Linux, macOS, Windows, and the web from a single codebase. Flutter was released in May 2017. Developers consider it as the fastest and most expressive way to create native apps. Flutter will have a significant impact on the development of high-quality, feature-packed mobile applications in the near future due to its simplicity, high performance as a result of its development, and rich user interface.

<div align="right">
    <b><a href="#">⮬ back to top</a></b>
</div>

## Q2. What is Dart and Why does Flutter use it?

Dart is a programming language designed for client development, such as for the web and mobile apps. It is developed by Google and can also be used to build server and desktop applications. It is an object-oriented, class-based, garbage-collected language with C-style syntax.

* Dart allows Flutter to avoid the need for a separate declarative layout language like JSX or XML, or separate visual interface builders, because Dart's declarative, programmatic layout is easy to read and visualize.
* Dart uses the Just In Time compilation. This drastically reduces the time of development and responds faster.

<div align="right">
    <b><a href="#">⮬ back to top</a></b>
</div>

## Q3. What is `pubspec.yaml` file and what does it do?

Every Flutter project includes a `pubspec.yaml` file, which is generated while creating a new Flutter project. It’s located at the top of the project tree and contains metadata about the project that the Dart and Flutter tooling needs to know.

The pubspec file specifies dependencies that the project requires, such as particular packages (and their versions), fonts, or image files. It also specifies other requirements, such as dependencies on developer packages (like testing or mocking packages), or particular constraints on the version of the Flutter SDK.

<div align="right">
    <b><a href="#">⮬ back to top</a></b>
</div>

## Q4. What is the difference between `main()` and `runApp()` functions in Flutter?

The `main()` function tells Dart where the program starts, and it must be in the file that is considered the "entry point" for the program. By convention, this will be in a file called `main.dart`. This main function can execute any code within it's code block.

The `runApp()` function should return widget that would be attached to the screen as a root of the widget tree that will be rendered.

<div align="right">
    <b><a href="#">⮬ back to top</a></b>
</div>

## Q5. Differentiate between named parameters and positional parameters in Flutter.

A `Positional Parameter` is linked by its position. Positional parameters must be specified in the order in which they appear. `Named Parameters` are referenced by name, which means that they can be used during the function invocation in an order different from the function declaration.

To declare a positional optional parameter, we use square brackets `[ ]`, whereas to declare a named optional parameters we use curly braces `{ }`.
```dart
doSomething(String name, [String greeting = 'Hello']); // Positional Optional Parameter
doSomething({String? name, String greeting = 'Hello'}); // Named Optional Parameter
```

<div align="right">
    <b><a href="#">⮬ back to top</a></b>
</div>
