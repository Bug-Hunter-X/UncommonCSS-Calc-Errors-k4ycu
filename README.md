# Uncommon CSS `calc()` Errors

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS. The `calc()` function is a powerful tool for performing calculations directly within your stylesheets, but it's important to be aware of potential pitfalls.

## Common Issues:

* **Improper Nesting:** Incorrectly nested `calc()` expressions can lead to unexpected results. Make sure each nested `calc()` is properly enclosed in parentheses.
* **Missing Spaces:** Always include spaces around operators (+, -, *, /) within `calc()` expressions.
* **Unsupported Units:** Ensure that the units you are using within `calc()` are supported and consistent. Mixing different units without proper conversion can cause issues.
* **Parentheses Mismatch:** Ensure you have the same number of opening and closing parentheses.

## How to use this repo:

1. Clone the repository.
2. Open the `bug.css` file to see the examples of erroneous `calc()` usage.
3. Compare it with the fixed version in `bugSolution.css` to see the corrected code.
4. Experiment to see how different issues can arise.

## License

[MIT](https://opensource.org/licenses/MIT)