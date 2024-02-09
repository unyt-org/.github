# Contributing Guidelines
Welcome to [unyt.org](https://unyt.org)!

These guidelines are designed to ensure clarity and foster a positive environment for all contributors.
Your participation is invaluable in improving our project. 

Please adhere to these guidelines to maintain a welcoming and collaborative space.

*Pull requests, bug reports, and all other forms of contribution on our sub project such as [UIX](https://github.com/unyt-org/uix) and [DATEX](https://github.com/unyt-org/datex-core-js-legacy) are highly encouraged!* ❤️

### Contents

- [Code of Conduct](#book-code-of-conduct)
- [Asking Questions](#bulb-asking-questions)
- [Opening an Issue](#inbox_tray-opening-an-issue)
  - [Reporting Security Issues](#lock-reporting-security-issues)
  - [Bug Reports and Other Issues](#beetle-bug-reports-and-other-issues)
- [Feature Requests](#love_letter-feature-requests)
- [Submitting Pull Requests](#repeat-submitting-pull-requests)
- [Writing Commit Messages](#memo-writing-commit-messages)
- [Code Review](#white_check_mark-code-review)
- [Coding Style](#nail_care-coding-style)


## :book: Code of Conduct

Please review our [Code of Conduct](https://github.com/unyt-org/.github/blob/main/CODE_OF_CONDUCT.md). Any behavior violating this code will not be tolerated.

## :bulb: Asking Questions

If you have questions, please refer to our [Discord Support](https://unyt.org/discord). While GitHub issues are not for debugging individual projects, they are suitable for reporting bugs and suggesting features.
For legal inquiries to unyt.org e.V., media inquiries or any other business inquiries you can contact our team via support@unyt.org.

## :inbox_tray: Opening an Issue

Before [creating an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue), check if you are using the latest version and branch of the project.
If you are not up-to-date, see if updating fixes your issue first. Always include the project version number and local setup information in your issues.

### :lock: Reporting Security Issues

Please review our [Security Policy](https://github.com/unyt-org/.github/blob/main/SECURITY.md) and **do not** file a public issue for critical security vulnerabilities.
You can reach our security team via security@unyt.org. Download our PGP key [here](https://unyt.org/pgp).

* Report an [UIX](https://github.com/unyt-org/uix/security) security issue

### :beetle: Bug Reports and Other Issues

To contribute, submit a detailed issue when encountering a problem. Ensure it includes necessary information like steps to reproduce, stack traces, and screenshots.

* Review the [documentation](https://unyt.org) and our [blog](https://unyt.blog) before creating an issue.
* Avoid opening duplicate issues. Search existing ones and provide additional information if needed.
* Use reactions to express support for existing issues.
* Complete the provided issue template thoroughly, including relevant details.

## :love_letter: Feature Requests

We do really love and more than that - rely on your feature requests!
Please keep in mind that we cannot guarantee the acceptance of your feature request. Ensure your request aligns with the project scope, unyt.org vision and provide (technical) implementation details if possible.

- Avoid duplicating feature requests. Comment on existing ones if similar.
- Complete the provided feature request template.


## :repeat: Submitting Pull Requests

We **love** pull requests! Before [forking the repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests), it is the best to first open an issue to discuss the changes and needs.

- Start with smaller pull requests for easier review.
- Coordinate large changes with maintainers.
- Prioritize code clarity and follow existing conventions.
- Include tests, update documentation, and the CHANGELOG.
- Resolve merge conflicts and address CI failures promptly.

## :memo: Writing Commit Messages

Please follow these guidelines for good commit messages:

- Separate subject and body with a blank line.
- Limit subject line to 50 characters, using imperative mood.
- Explain "why" in the body, not "what" or "how."
- Wrap body at less than 100 characters.
- Mention relevant component name, username `(@maintainer)` and issues `(#42)`.


## :white_check_mark: Code Review

- Focus on code, not the author.
- Don't take critiques personally.
- Strive for quality and learn from mistakes.
- Note any guideline violations kindly.

## :nail_care: Coding Style

Consistency is the most important. Following the existing style, formatting, and naming conventions of the file you are modifying and of the overall project. Failure to do so will result in a prolonged review process that has to focus on updating the superficial aspects of your code, rather than improving its functionality and performance.

### TypeScript
* Constants shall be uppercase and seperated with underscore `_` (`const MY_CONST = 42`)
* Properties shall follow camel case naming convention (`myProp`)
* Method names shall follow camel case naming convention (`myFunction() {}`)



---

<sub>&copy; unyt 2024 • [unyt.org](https://unyt.org)</sub>
  
