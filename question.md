<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [Interview Questions by Topic](#interview-questions-by-topic)
- [Table of Contents](#table-of-contents)
   * [Personal/General Questions](#personalgeneral-questions)
   * [iOS Development](#ios-development)
      + [Swift Basics](#swift-basics)
      + [Advanced Swift](#advanced-swift)
      + [Swift Advanced Concepts](#swift-advanced-concepts)
   * [iOS Tools and Trends](#ios-tools-and-trends)
   * [Android Development](#android-development)
      + [Basics](#basics)
      + [Intermediate](#intermediate)
      + [Advanced](#advanced)
   * [Android Unit Testing](#android-unit-testing)
   * [OOP (Object-Oriented Programming)](#oop-object-oriented-programming)
      + [Basics](#basics-1)
      + [Intermediate](#intermediate-1)
   * [Testing](#testing)
   * [General Programming](#general-programming)
      + [Basics](#basics-2)
      + [Intermediate](#intermediate-2)
   * [APIs](#apis)
   * [Git](#git)
   * [Kotlin](#kotlin)
      + [Basics](#basics-3)
      + [Intermediate](#intermediate-3)
      + [Advanced](#advanced-1)

<!-- TOC end -->

<!-- TOC --><a name="interview-questions-by-topic"></a>
# Interview Questions by Topic
<!-- TOC --><a name="table-of-contents"></a>
# Table of Contents


Advanced
<!-- TOC --><a name="personalgeneral-questions"></a>
## Personal/General Questions
- What is your current notice period, and when would you be available to start?
- Could you bring your own Mac and iPhone, or should beno provide that for you?
- What is your current role, and would you consider yourself a senior or junior in your position?
- Could you please provide your expected salary range for this position, including your minimum and maximum expectations?
- Why are you leaving your current job to interview at beno.com?
- What is your favorite programming language, and why?
- What is your favorite IDE, and why?
- What is your idea of a good workday?
- Describe a difficult task you had at work and how you finished it.
- What makes code "clean code"?

<!-- TOC --><a name="ios-development"></a>
## iOS Development

<!-- TOC --><a name="swift-basics"></a>
### Swift Basics
- Explain the difference between `let` and `var` in Swift.
- How would you explain the concept of optionals in Swift to a beginner?
- What are the several methods for unwrapping an optional in Swift?
- When would you use the `guard` keyword in Swift?
- Why is it dangerous to fetch API requests on the main thread? What are the solutions?
- What is threading, and why is it important in iOS development?
- What benefits does SwiftUI offer for iOS development?
- Describe the concept of lazy initialization in Swift.
- How do you debug a Swift app?
- Do you think SwiftUI will kill Storyboards one day?
- What does the `@State` property wrapper do?
- Does the order of SwiftUI modifiers matter?
- Can you give some examples of where singletons might be a good idea?
- How do Xcode Previews improve the speed of iOS development, and what are they used for?

<!-- TOC --><a name="advanced-swift"></a>
### Advanced Swift
- Why is immutability important?
- Why does SwiftUI use structs for views?
- How would you explain delegates to a new Swift developer?
- Can you explain MVVM, and how it might be used on Apple's platforms?
- How would you explain dependency injection to a junior developer?
- What experience do you have with functional programming? OOP vs. functional?
- What process do you take to perform code review?
- What is an efficient way to cache data in memory?
- How would you explain protocols to a new Swift developer?
- What are property observers?
- What does the `@Published` property wrapper do?
- When would you use `@StateObject` versus `@ObservedObject`?
- What is the difference between structures (value types) and classes (reference types)?
- When is the usage of a set more preferable than an array in iOS Swift?
- If you could have Apple add or improve one API, what would it be?

<!-- TOC --><a name="swift-advanced-concepts"></a>
### Swift Advanced Concepts
- What is the difference between an extension and a protocol extension?
- How has Swift changed since it was first released in 2014?
- How would you identify and resolve a retain cycle?
- How would you explain ARC to a new iOS developer?
- What is reference counting, and how does it work in iOS?
- What is a strong reference and a weak reference in iOS?

<!-- TOC --><a name="ios-tools-and-trends"></a>
## iOS Tools and Trends
- What are the latest versions of iPhone, iOS, macOS, and Xcode?
- How do you stay up to date with changes in Swift?
- Do you have any favorite Swift newsletters or websites you read often?

<!-- TOC --><a name="android-development"></a>
## Android Development

<!-- TOC --><a name="basics"></a>
### Basics
- What is the Application class?
- What is `AndroidManifest.xml`?
- What is the project structure of an Android Application?
- How is the XML file linked with Java code?
- How to ask for permissions?
- How is data sent between activities?
- Difference between `View.GONE` and `View.INVISIBLE`?
- What is an Activity, and what are its lifecycle methods?
- What is the difference between `onCreate()` and `onStart()`?
- What is the Activity/Fragment lifecycle?
- How to translate in Android?

<!-- TOC --><a name="intermediate"></a>
### Intermediate
- Why is `AsyncTask` bad, and what are the alternatives?
- How to perform heavy operations in Android?
- Why does an Android app crash if you perform tasks on the main thread?
- What is a thread?
- What is a coroutine?
- Tell me about `ConstraintLayout` over other layouts.
- What is the difference between `ListView` and `RecyclerView`?
- How does `RecyclerView` work internally?
- What is a Fragment, and what are its lifecycle methods?
- When should you use a Fragment rather than an Activity?
- What are Intents and Broadcasting?
- How to persist data in an Android app?
- What is `commit()` and `apply()` in `SharedPreferences`?
- What is RoomDB?
- What is Android Jetpack, and why use it?
- What is LiveData in Android?
- What is a ViewModel?
- What is a View in Android?
- What is Android Data Binding?

<!-- TOC --><a name="advanced"></a>
### Advanced
- What is the difference between adding/replacing a fragment in the backstack?
- How would you communicate between two Fragments?
- What is the difference between `Serializable` and `Parcelable`? Which is the best approach in Android?
- Differentiate Activities from Services.
- What is a JobScheduler?
- What DI frameworks do you use?
- What is the function of an `IntentFilter`?
- What is an `Intent`? What is an Implicit Intent? What is an Explicit Intent?
- What is `onSavedInstanceState()` and `onRestoreInstanceState()` in an Activity?
- How can you keep data after a configuration change?
- Tell me all the Android application components.
- What are "launch modes"?
- What is Context? How is it used?
- What are memory leaks?
- Where are Firebase messages received?
- Can you create a custom view? How?
- What is the ViewHolder pattern? Why should we use it?
- Service vs. IntentService.
- What is ANR? How can ANR be prevented?
- Why should you avoid running non-UI code on the main thread?
- What is the difference between `setValue` and `postValue` in LiveData?
- What are Android Architecture Components?
- Explain OkHttp Interceptor.
- What does Gradle do?
- What does ProGuard do?

<!-- TOC --><a name="android-unit-testing"></a>
## Android Unit Testing
- What is Espresso?
- What is Robolectric?
- What are the disadvantages of using Robolectric?
- What is UI-Automator?
- Explain unit tests.
- Explain instrumented tests.
- Have you done unit testing or automatic testing?
- Why is Mockito used?
- Describe JUnit tests.
- Describe code coverage.

<!-- TOC --><a name="oop-object-oriented-programming"></a>
## OOP (Object-Oriented Programming)

<!-- TOC --><a name="basics-1"></a>
### Basics
- What is inheritance?
- What is a superclass?
- What is a subclass?
- What is the `final`/`readOnly`/`val` keyword?
- How to protect your class from inheritance?
- How to protect your method from being overridden?
- How to protect your variable from changes?
- What is the default value of local variables? (Must be initialized; IDEs will tell you.)
- What is a package/namespace, and why are they used?
- What is the difference between a static method and a normal method?
- What is the difference between a static variable and a normal variable?
- How can we call the base method without creating an instance? (By using static.)
- How to use static methods/variables?
- What is method overloading?
- What is method overriding?

<!-- TOC --><a name="intermediate-1"></a>
### Intermediate
- What are the OOP principles?
  - Inheritance: Reusing code by creating a parent-child relationship.
  - Encapsulation: Variable control should be done by the class; setters and getters prevent users from changing values arbitrarily.
  - Polymorphism: Same type, different behavior.
  - Data Abstraction: Displaying only important information and hiding implementation details.
- What is the difference between `String` and `StringBuilder`?
- If a class has three static variables, when are these variables pushed to memory, and when are they cleaned up?
- Can you declare an overridden method to be static if the original method is not static? (No, static methods cannot be overridden.)
- What is the difference between `HashMap` (dictionary) and `HashSet`?
- What are the functions of the `hashCode()` method?
- Why do I need to override the `equals` and `hashCode` methods?
- What is the difference between a `LinkedList` and an `ArrayList`?
- What are mutable/immutable variables?
- What is the difference between asynchronous and synchronous code?
- What are design patterns?
- Explain the difference between an inner class and a nested static class.
- What is boxing type? (Wrapper classes in Java, e.g., `Integer`, `Long`. )
- Why doesn’t Java/C# support multiple inheritance?
- Does Java allow default arguments? (No, but you can achieve the same behavior by overloading methods.)
- What are memory leaks?
- Explain Factory and Builder design patterns.
- What is UTC date?
- Why is it recommended to close database connections?
- Why are stored procedures faster than direct queries?

<!-- TOC --><a name="testing"></a>
## Testing
- What is unit testing?
- What is integration testing?
- What is the difference between unit tests and instrumented tests?
- What is code coverage?
- Why is testing important in software development?

<!-- TOC --><a name="general-programming"></a>
## General Programming

<!-- TOC --><a name="basics-2"></a>
### Basics
- Explain `public static void main(String args[])` in Java.
- What is the difference between abstract classes and interfaces?
- Can you create an instance of an abstract class/interface?
- What is a constructor?
- What is the difference between a local variable (in a method) and an instance variable (in a class)?
- Differentiate between `this()` and `super()` in Java.
- Name all of the data types.
- What is the difference between `ArrayList` and `Array`? (Array is fixed size.)

<!-- TOC --><a name="intermediate-2"></a>
### Intermediate
- What is the base class of all classes? (In Java/C#: `Object`; in Kotlin: `Any`.)
- What is the difference between `==` and `equals()`? (`==` checks memory reference; `equals()` checks object content.)
- What is Garbage Collection (GC)?
- What is JSON?
- What is an enumeration?
- What are the methods of the `Object` class? (`toString`, `hashCode`, `equals.`)
- What are visibility modifiers?
- What are the different types of arguments (ref/value)?
- What is a singleton, why is it used, and how is it implemented?
- What are the file extensions for Java/C#?

<!-- TOC --><a name="apis"></a>
## APIs
- What is the difference between REST and SOAP?
- What are the REST actions?
- What are the REST status codes?
- What is a token?
- What are the advantages of JSON over XML?
- What is serialization?

<!-- TOC --><a name="git"></a>
## Git
- Explain push, commit, pull, and PR.
- What is a Git conflict?
- What is the difference between fetch and pull?
- What is the difference between soft, hard, and mixed resets?
- What is the difference between merge, rebase, squash, and fast-forward?

<!-- TOC --><a name="kotlin"></a>
## Kotlin

<!-- TOC --><a name="basics-3"></a>
### Basics
- What is new in Kotlin that Java doesn’t have? Why should you switch to Kotlin from Java?
- What is the difference between `var` and `val`?
- What is a data class in Kotlin?
- Can we use primitive types such as `int`, `double`, and `float` in Kotlin?
- What are visibility modifiers in Kotlin? What’s the default visibility modifier?
- What are companion objects in Kotlin?
- Does Kotlin have the static keyword? How to create static methods in Kotlin?
- What is a property?
- What is the default return type in Kotlin, and what is its equivalent in Java?
- What is the equivalent of Java’s switch statement in Kotlin?

<!-- TOC --><a name="intermediate-3"></a>
### Intermediate
- What are default arguments in Kotlin?
- How to call top-level functions/variables from Java?
- How to create singleton classes in Kotlin?
- What are named arguments used for?
- What are varargs in Kotlin?
- How many varargs can be placed in a parameter list?
- What is a spread operator? (It is used to pass an array as the vararg parameter.)
- What does ‘Null Safety’ mean in Kotlin?
- What is the difference between safe calls (`?.`) and null checks (`!!`)?
- Do we have a ternary operator in Kotlin, just like in Java?
- What is the Elvis operator (`?:`) in Kotlin?
- Is there any difference between `==` and `===` operators?
- What is the difference between `lateinit` and `lazy` in Kotlin?
- What is the equivalent of Java static methods in Kotlin?
- What are init blocks in Kotlin?
- What are the types of constructors in Kotlin?
- Is there any relationship between primary and secondary constructors? (Yes, when using a secondary constructor, you need to call the primary constructor explicitly.)
- What are coroutines in Kotlin?
- What is a suspend function in Kotlin coroutines?
- What is the difference between launch and async in Kotlin coroutines?
- What is the `open` keyword in Kotlin used for?
- What are extension functions in Kotlin?
- What is `as throws`?

<!-- TOC --><a name="advanced-1"></a>
### Advanced
- Is Kotlin statically or dynamically typed?
- When is a backing field for a property not generated?
- What is the difference between `val` and `const`?
- How does Kotlin work on Android?
- What is the use of `@JvmStatic`, `@JvmOverloads`, `@JvmName`, and `@JvmField` in Kotlin?
- What are higher-order functions in Kotlin?
- What is an infix function in Kotlin?
- What are the benefits of using a sealed class over an enum?
- What are the `out` and `in` keywords?
- What are lambda labels used for?
- What are inline functions/classes?
- Does Kotlin have checked exceptions?
- What is a safe cast (`as?`)?
- What is the lambda syntax in Kotlin?
- What is it in lambda?
- What are Kotlin sequences?
- How to define custom getters and setters?
- When you declare a class inside another, will it be static or inner? Why?
- What is the difference between variables declared in the constructor or body of a data class?
- What is the difference between `let`, `run`, `with`, `apply`, and `also`?
- What is a platform type?
- What is the `Nothing` type?
- What is the default `val/var` for function parameters?
- What is the difference between constructor parameters with/without `val`?
