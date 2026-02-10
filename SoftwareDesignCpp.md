
## C++ Software Design

### Chapter 1 : The Art of Software Design

#### Guideline 1: Understand the Importance of Software Design
- Treat software design as an essential part of writing software.
- Focus less on C++ language details and more on software design.
- Avoid unnecessary coupling and dependencies to make software more adaptable to frequent changes.
- Understand software design as the art of managing dependencies and abstractions.
- Consider the boundary between software design and software architecture as fluid.

#### Guideline 2: Design for Change
- Expect change in software.
- Design for easy change and make software more adaptable.
- Avoid combining unrelated, orthogonal aspects to prevent coupling.
- Understand that coupling increases the likelihood for change and makes changes harder.
- Adhere to the Single-Responsibility Principle (SRP) to separate concerns.
- Follow the Don’t Repeat Yourself (DRY) principle to minimize duplication.
- Avoid premature abstraction if you are not sure about the next change.

#### Guideline 3: Separate Interfaces to Avoid Artificial Coupling 
- Be aware that coupling also affects interfaces.
- Adhere to the Interface Segregation Principle (ISP) to separate concerns in interfaces.
- Consider the ISP as a special case of the Single-Responsibility Principle (SRP).
- Understand that the ISP helps for both inheritance hierarchies and templates.

#### Guideline 4: Design for Testability
- Understand that tests are your protection layer against accidentally breaking things.
- Keep in mind that tests are essential, and so is testability.
- Separate concerns for the sake of testability.
- Consider private member functions that need testing to be misplaced.
- Prefer nonmember non-friend functions to member functions.

#### Guideline 5: Design for Extension
- Favor design that makes it easy to extend code.
- Adhere to the Open-Closed Principle (OCP) to keep code open for extension but closed for modification.
- Design for code additions by means of base classes, templates, function overloading, or template specialization.
- Avoid premature abstraction if you are not sure about the next addition.
