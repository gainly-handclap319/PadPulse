# Contributing

Thanks for considering a contribution to PadPulse.

## Before you start

- Open an issue for large changes before spending a lot of time on implementation.
- Keep the project lightweight and browser first.
- Prefer changes that work without build tooling unless there is a strong reason to add complexity.

## Development setup

1. Fork the repository.
2. Clone your fork.
3. Run `node server.js`.
4. Open `http://localhost:4173`.

## Pull request guidelines

- Keep pull requests focused.
- Explain what changed and why.
- Include screenshots or a short video for UI changes when possible.
- Mention browser coverage if you changed Gamepad API logic.
- Do not add heavy dependencies without discussing them first.

## Code style

- Use readable, plain JavaScript.
- Keep the app static and easy to host.
- Preserve bilingual support when touching user-facing text.
- Prefer small, explicit functions over clever abstractions.

## Testing checklist

- Verify the page still loads on desktop and mobile widths.
- Verify the app still works without a connected controller.
- If possible, test with at least one PlayStation or Xbox controller.
- Run `node --check script.js` and `node --check server.js`.

## Community

By contributing, you agree to follow the [Code of Conduct](./CODE_OF_CONDUCT.md).
