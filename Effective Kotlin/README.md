# Effective Kotlin

- [책 링크](https://leanpub.com/effectivekotlin)

## Part 1: Good Code

| Chapter 1: Safety                                                         |
| ------------------------------------------------------------------------- |
| [Item 1: Limit Mutability](./01.md)                                       |
| [Item 2: Minimize the scope of variables](./02.md)                        |
| [Item 3: Eliminate platform types as soon as possible](./03.md)           |
| Item 4: Do not expose inferred types                                      |
| Item 5: Specify your expectations on arguments and state                  |
| Item 6: Prefer standard errors to custom ones                             |
| Item 7: Prefer null or Failure result when the lack of result is possible |
| Item 8: Handle nulls properly                                             |
| Item 9: Close resources with use                                          |
| Item 10: Write unit tests                                                 |

| Chapter 2: Readability                                                |
| --------------------------------------------------------------------- |
| Item 11: Design for readability                                       |
| Item 12: Operator meaning should be consistent with its function name |
| Item 13: Avoid returning or operating on Unit?                        |
| Item 14: Specify the variable type when it is not clear               |
| Item 15: Consider referencing receivers explicitly                    |
| Item 16: Properties should represent state, not behavior              |
| Item 17: Consider naming arguments                                    |
| Item 18: Respect coding conventions                                   |

## Part 2: Code Design

| Chapter 3: Reusability                                                  |
| ----------------------------------------------------------------------- |
| Item 19: Donot repeat knowledge                                         |
| Item 20: Do not repeat common algorithms                                |
| Item 21: Use property delegation to extract common property patterns    |
| Item 22: Use generic when implementing common algorithms                |
| Item 23: Avoid shadowing type parameters                                |
| Item 24: Consider variance for generic types                            |
| Item 25: Reuse between different platforms by extracting common modules |

| Chapter 4: Abstraction design                                                      |
| ---------------------------------------------------------------------------------- |
| Item 26: Each function should be written in terms of a single level of abstraction |
| Item 27: Use abstraction to protect code against changes                           |
| Item 28: Specify API stability                                                     |
| Item 29: Consider wrapping external API                                            |
| Item 30: Minimize elements visibility                                              |
| Item 31: Define contract with documentation                                        |
| Item 32: Respect abstraction contracts                                             |

| Chapter 5: Object creation                                            |
| --------------------------------------------------------------------- |
| Item 33: Consider factory functions instead of constructors           |
| Item 34: Consider a primary constructor with named optional arguments |
| Item 35: Consider defining a DSL for complex object creation          |

| Chapter 6: Class Design                                                          |
| -------------------------------------------------------------------------------- |
| Item 36: Prefer composition over inheritance                                     |
| Item 37: Use the data modifier to represent a bundle of data                     |
| Item 38: Use function types instead of interfaces to pass operations and actions |
| Item 39: Prefer class hierarchies to tagged classes                              |
| Item 40: Respect the contract of equals                                          |
| Item 41: Respect the contract of hashCode                                        |
| Item 42: Respect the contract of compareTo                                       |
| Item 43: Consider extracting non-essential parts of your API into extensions     |
| Item 44: Avoid member extensions                                                 |

## Part 3: Efficiency

| Chapter 7: Make it cheap                                                       |
| ------------------------------------------------------------------------------ |
| Item 45: Avoid unnecessary object creation                                     |
| Item 46: Use inline modifier for functions with parameters of functional types |
| Item 47: Consider using inline classes                                         |
| Item 48: Eliminate obsolete object references                                  |

| Chapter 8: Efficient collection processing                                      |
| ------------------------------------------------------------------------------- |
| Item 49: Prefer Sequence for big collections with more than one processing step |
| Item 50: Limit the number of operations                                         |
| Item 51: Consider Arrays with primitives for performance-critical processing    |
| Item 52: Consider using mutable collections                                     |
