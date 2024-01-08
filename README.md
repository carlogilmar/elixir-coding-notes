# PR Guidelines

Include

- 📍 Business descripcion and diagrams
- 📍 Especify what feedback are you waiting
- 📍 Functions + Tests + Dialyzer + Credo
- 📍 Code readability feedback will come from your teammates

## Code guidelines 

`Function naming`
- 📍 Organize funcions in order by alphabet.
- 📍 Add `@doc` detached an important piece of logic.
- 📍 For functions to raise errors put ! in the function name.
- 📍 Instead of use `maybe` use `ensure`.

`Logic considerations`
- 📍 Repo operations should use with statement.
- 📍 Instead of case, use pattern matching.
- 📍 Resolve names in specs.
- 📍 Always give a off-ramp to handle error values in functions.

`Unit tests`
- 📍 Use present tense in test descriptions.
- 📍 Unit test: Arrange, act and assert.
- 📍 Don't assert before act in unit tests.


