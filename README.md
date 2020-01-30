# `contentEditable` specification

Creating a web-based text-editor requires a considerable amount of JavaScript because:

* Browsers differ in the manner they handle editing operations.
* Individual sites may have custom preferences for how they want to handle certain editing operations.
* Assumptions about how these legacy features were developed in web browsers don't always match how developers use them.

The `contentEditable` spec seeks to alleviate the problem by providing a simple way for web developers prevent all browser default handling of editing operations at different levels.
