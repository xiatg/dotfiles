### Code Comments

Code comments must be very concise and describe only what the code does. Do not explain the reasoning behind it or how pieces of code work together internally.

### Coding Style

- Avoid inheritance unless it is absolutely necessary.
- Name every class and every function or method so it clearly says what it does, and give each one a concise comment that follows the Code Comments rule above.
- Avoid ambiguous names that carry no real meaning, such as `context`.
- Keep each class self-contained: its internal logic stays within the class.
- Avoid inline functions and classes.
- Avoid generic method names such as `add`, `flush` or `send` that look simple but have other side effects. Use them only when the class name makes the meaning obvious (for example, a set or list) and the method does only that simple thing. Otherwise, name the method after what it actually does.
