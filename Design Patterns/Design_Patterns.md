# Design Principles
1. Rely on Interfaces not implementations
2. The Open/Close Principle
3. Principle of Least Knowledge
4. Dependency Inversion
5. Hollywood Principle

# Design Patterns

### Creational Patterns
> "How should objects be created"
* Factory
* Abstract Factory
* Singleton
* Builder
* Prototype
* Dependency Injection

### Behavioral Patterns
> "How should objects behave and interact with each other?"
*   <details>
    <summary>Strategy</summary>
    <ul>
    <li>Make it easy to vary the behavior of a class at runtime, and do so using composition rather than inheritance</li>
    <li>Composition="has-a", Inheritance="Is-a"</li>
    <li>For example, <b>passport.js</b> has local or google strategies and you can add more.<br>
    <i>Applications can choose which strategies to employ, without creating unnecessary dependencies.</i></li>
    <ul>
    </details>

* Template
* Iterator
* Command
* Chain of Responsibility
* Memento
* Visitor State
* Mediator
* Observer

### Structural Patterns
> "How should classes behave and interact with each other?"
*   <details>
    <summary>Decorator</summary>
    <ul>
    <li>When to use?
    <ul>
    <li>When a class is constantly being modified to implement new interfaces</li>
    </ul>
    </li>
    <li>Decorators should be independent of each other</li>
    <li>Use the decorator pattern when you have lots of objects each with a specific behavior independent of all others</li>
    <li>For example, use decorator to check specific user role before the end point method can be used</i></li>
    <ul>
    </details>
* Adapter
* Facade
* Composite
* Flyweight
* Bridge
* Proxy

### Concurrency Patterns
> "How should a specific situation be handled under multi-threading?"