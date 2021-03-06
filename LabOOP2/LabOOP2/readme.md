# OOP Principles

**Author**: Andres Ibarra
**Version**: 1.0

## Overview
The following application was built utilizing the four principles of OOP.
- Inheritance
- Abstraction
- Polymorphism
- Encapsulation

## Requirements to run the Application
- [Visual Studio 2017 Community with .NET Core 2.0 SDK](https://www.microsoft.com/net/core#windowscmd)
- [GitBash / Terminal](https://git-scm.com/downloads) or [GitHub Extension for Visual Studio](https://visualstudio.github.com)

## Getting Started
1. Clone the repository to your local machine.
2. Cd into the application directory where the `AppName.sln` exist.
3. Open the application using `Open/Start AppName.sln`.

## Take outs from this exercise
- `abstract` classes can NOT be instantiated
- `override` keyword is used on methods that are already declared abstract in abstract classes; overriding methods means implementing them
- `sealed` keyword can be used on overridden methods to make them final from being re-overridden
- `:` next to the class name indicates inheritance from the class on the right side of the colon
- Access modifiers are `public` `private` `internal` `protected` `protected internal`, they have to be used correctly and in accordance to keep consistency
- Main class is called `base` indicating `parent`
- Inherited class is called `derived` indicating `child`

## Architecture
- C# Console Core application
- Base/Parent class is CodeFellows, People and Courses are the first two derived Classes