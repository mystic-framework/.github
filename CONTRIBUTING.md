# Contributing

Thank you very much for your interest in contributing to the framework! We welcome contributions from everyone, whether you're a seasoned
developer or just getting started. This guide will help you understand how to contribute effectively and become a part of our community.

Before you start contributing, we expect you to read and understand our [Code of Conduct](https://mystic-framework.github.io/docs/code-of-conduct).
This helps us maintain a welcoming and inclusive environment for all contributors.


## Want to Contribute?

There are many ways to contribute to the framework, including:
- Reporting bugs and issues
- Suggesting new features or improvements
- Contributing code or fixing bugs

In order to do these effectively, you can follow these guidelines documented here.


## Reporting Bugs and Issues

If you encounter a bug or issue while using the framework, please report it on the specific module's GitHub repository. When reporting a
bug, please provide as much detail as possible, including:
- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior vs. actual behavior
- Screenshots or code snippets, if applicable
- Your environment details (e.g., operating system, framework version)

While writing title we expect you to tag it with `[BUG]` prefix for bugs and `[ISSUE]` prefix for issues. This helps us quickly identify and
prioritize the reports.

Bugs mean that the framework is not working as intended, while issues can be anything from performance bottlenecks to unexpected failures.
Please make sure to check the existing issues before reporting a new one, as someone else may have already reported it.

A good example of a bug report:
````
[BUG] Invalid results when using the `Calculate()` function with negative numbers

The bug occurs when calling the `Calculate()` function with negative numbers. The expected behavior is that the function should return the
correct result, but instead, it returns an error.

Expected behavior:
  Returns the correct result for negative numbers.
Actual behavior:
  Returns an error when negative numbers are passed to the `Calculate()` function.

Code snippet:
```cpp
  int result = Calculate(-5, -10); // this should return -15, but it returns an error
```

Environment:
  - Operating System: Windows 10
  - Framework Version: 1.2.3
````


## Suggesting New Features or Improvements

If you have an idea for a new feature or improvement, we encourage you to submit a feature request on the specific module's GitHub
repository. When submitting a feature request, please provide as much detail as possible, including:
- A clear and descriptive title
- A detailed description of the feature or improvement
- The problem it solves or the benefit it provides
- Any relevant examples or use cases

When writing title we expect you to tag it with `[FEAT]` prefix for new features and `[IMPROV]` prefix for improvements.

A good example of a feature request:
````
[FEAT] Add support for multi-threading in the `ProcessData()` function

The `ProcessData()` function currently processes data sequentially, which can be slow for large datasets. Adding support for multi-threading
would allow the function to process data in parallel, improving performance and reducing processing time.

Use case:
  A user has a large dataset that needs to be processed quickly. With multi-threading support, the `ProcessData()` function can process the
  data in parallel, significantly reducing the time it takes to complete the operation.

```cpp
  auto result = ProcessData(largeDataset); // this should process the data in parallel, improving performance
```
````

Before submitting a new feature request, please check the existing requests to see if someone else has already suggested it.
If so, you can add your support or provide additional details to help us understand the request better. If a feature does not
align with the framework's goals or is not feasible, we may not be able to implement it. However, we appreciate all suggestions and feedback.

> [!NOTE]
> Feature requests closed with `Rejected` status are not implemented and will not be implemented in the future. Please do not submit a new feature
> request for the same feature if it has been rejected. Instead, you can provide additional details or examples to help us understand the request
> better.


## Contributing Code or Fixing Bugs

If you would like to contribute code or fix bugs, we welcome your contributions! Please first follow these prerequisites to ensure a
smooth contribution process:
- Check the existing issues, feature requests, and pull requests to see if someone else is already working on it. If so, you can add your support or provide insights.
- Read and follow the [Style Guide](https://mystic-framework.github.io/docs/style-guide) to ensure your code adheres to the framework's coding standards.
- Ensure that your changes are limited in scope, meaning it only does one thing and does it perfectly.

Now that you have completed the prerequisites, you can follow these steps to contribute code or fix bugs:
- Fork the specific module's GitHub repository to your own account.
- Clone the forked repository to your local machine.
- Create a new branch for your changes. Use a descriptive name for the branch, such as `fix-bug-calculate-function` or `add-multithreading-support`.
- Make your changes or fixes in the codebase. Ensure that your code adheres to the framework's coding standards and passes all tests.
- Commit your changes with a clear and descriptive commit message.
- Push your changes to your forked repository on GitHub.
- Submit a pull request to the original repository.

When submitting a pull request, please provide a clear and descriptive title and description of your changes. Include any relevant information,
such as the issue number or feature request that your changes address. This helps us understand the purpose of your changes and review them
effectively. You may also add a brief summary of the changes you made and any additional context that may be helpful for the reviewers.

Few tips for submitting a successful pull request:
- Ensure that your code passes all tests and does not introduce any new issues.
- Be clear and concise in your pull request description, highlighting the key changes and their impact.
- Be responsive to feedback and make any necessary changes requested by the reviewers.
- Be patient and understanding during the review process. We appreciate your contributions but everyone is a volunteer and has other commitments too.
- Be respectful and professional in your communication with the reviewers and other contributors.

> [!NOTE]
> You don't need to manually squash your commits before submitting a pull request. We will squash the commits during the merge process to
> keep the commit history clean and organized. There is also no need to update CHANGELOG.md file, we will take care of it. 


## Note for Reviewers

Anyone can review a pull request, but we request them to follow these guidelines to ensure a smooth and effective review process:
- Review the code changes thoroughly and provide constructive feedback.
- Check for adherence to the framework's coding standards and style guide.
- Test the changes to ensure they work as intended and do not introduce any new issues.
- Be respectful and professional in your communication with the contributors and other reviewers.

---

That's it! We hope this guide helps you contribute effectively to the framework and become a part of our community. Thank you for your contributions!
