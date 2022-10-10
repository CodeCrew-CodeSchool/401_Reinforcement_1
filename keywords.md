
## Keywords in C#

Keywords are predefined, reserved identifiers that have special meanings to the compiler. They can't be used as identifiers in your program unless they include @ as a prefix. For example, @if is a valid identifier, but if isn't because if is a keyword. Keywords are **not** allowed to be used as variable names or objects. Doing this will result in a **compile-time error.**

Resources:
[Keywords in C#](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/).


1. Access Modifier Keywords

## What are they?
Access modifiers in C# are used to specify the scope of accessibility of a member of a class or type of the class itself. For example, a public class is accessible to everyone without any restrictions, while an internal class may be accessible to the assembly only.

## Why should we use them?
Access modifiers are an integral part of object-oriented programming. Access modifiers are used to implement encapsulation of OOP. Access modifiers allow you to define who does or who doesn't have access to certain features.

### Types of Access modifiers:

- public: Access isn't restricted.
- protected: Access is limited to the containing class or types derived from the containing class.
- private: Access is limited to within the class definition. This is the default access modifier type if none is formally specified

- internal: Access is limited to the current assembly.
