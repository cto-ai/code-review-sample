# Code Review AI Feedback Examples

This repository contains a set of improvements to our basic sample application, presented as a series of Pull Requests with the patches being reviewed by our Code Review AI.

## Iterative Improvements

- [FEAT-1: Add weather app backend functionality to sample app](https://github.com/cto-ai/code-review-sample/pull/1)

  This Pull Request adds the basic backend functionality that enables the weather app functionality we're adding to the sample app. The files reviewed by the Code Review AI include the `index.js` file, as well as several dependent files used to implement the weather app functionality.

  This includes an [example of a file being re-reviewed](https://github.com/cto-ai/code-review-sample/pull/1#pullrequestreview-2021120785) by the Code Review AI after changes have been made to address the feedback from its initial review.

- [FEAT-2: Add weather app frontend functionality to sample app](https://github.com/cto-ai/code-review-sample/pull/2)

  This PR [begins](https://github.com/cto-ai/code-review-sample/pull/1#pullrequestreview-2021120785) by adding the corresponding frontend functionality to the sample app, including the template files for rendering the frontend.

  After the initial review, there are also changes added to [address the feedback](https://github.com/cto-ai/code-review-sample/pull/2#commits-pushed-51fe840) from the Code Review AI, including overarching changes proposed in the previous PR.

- [FIX-1: Slight refactor to make the error handling more robust](https://github.com/cto-ai/code-review-sample/pull/3)

  This PR demonstrates the sort of Code Review AI feedback you can expect for a refactor of an application that improves the error handling logic and makes the application more reliable in the face of unexpected errors.

- [FEAT-3: change direction labels to use 16-point compass rose directions](https://github.com/cto-ai/code-review-sample/pull/7)

  The feedback provided by the Code Review AI in this Pull Request isn't particularly helpful, but it does demonstrate how the AI can only provide feedback based on the context of the code provided in the Git patch. In this case, the feedback provided by the AI is missing some nuance about how numbers and rounding behave in JavaScript.

- [FIX-3: handle bad responses from remote APIs](https://github.com/cto-ai/code-review-sample/pull/8)

  There is another example of iterative improvement in this Pull Request, where the Code Review AI provides feedback on a fix to the weather app functionality that handles bad responses from remote APIs.

- [FEAT-4: Make error checking of anonymizeip.js more robust](https://github.com/cto-ai/code-review-sample/pull/9)

  A pair of small, incremental changes in this Pull Request demonstrate how the Code Review AI feedback changes as iterative improvements are made to the codebase.

- [REFACTOR-1: Improve flow and add explanatory comments](https://github.com/cto-ai/code-review-sample/pull/10)

  Finally, a small refactoring that makes little change to the application's functionality, but which make the structure of the code more clear and easier to understand.

## Other Examples

Also included in this repository are a few other Pull Requests which contain the same application changes as the above PRs, but with different groupings of commits, to demonstrate how the feedback from the Code Review AI changes based on the context of the patch it's reviewing.

- [APP-1: Add MVP of basic weather application features](https://github.com/cto-ai/code-review-sample/pull/4)
- [APP-1-FIXES: Make some fixes to our initial pass at new features](https://github.com/cto-ai/code-review-sample/pull/5)
- [FIX-2: correct minor errors based on Code Review AI feedback](https://github.com/cto-ai/code-review-sample/pull/6)
