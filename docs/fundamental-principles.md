---
title: Fundamental Principles
description: Style-Guide Created & Designed for Luau projects @ Latte Softworks
---

There are some fundamental principles we'd like to keep with this style-guide, including *why* certain rules and principles are how they are. Our main goal is to provide maintainers **and** contributers an easy way to add, modify, or fix parts of code in a way that's as simple as possible for everyone without causing conflict or issue.

- The point of a style-guide like this is to **avoid** arguments, not cause them.

    - There is no perfect way to write, style, or format code, but consistency and stability is **extremely** important. Even if this guide may not suit everyone's "taste" or preferred coding style, we choose to follow and accept it. It creates a sort-of arbitrary standard in a way, and allows us to all focus more on collaboration and functionality, instead of arguments over minor design disagreements or conflicts.

    - If we weren't to follow a set style-guide, we would be constantly facing annoying and unnecessary arguments and code conflicts, and makes for a very unpleasent collaborative environment for both developers and contributors alike. A style-guide simply allows for there to be an easy and non-argumentative collaborative environment so the more importantant parts of a project can be focused on, like functionality or security.

- Write and optimize your code for reading, **not** writing.

    - You will only write your code once. Other people will need to read the code you wrote or any changes made to it. From reviewers/maintainers, other contributers, and possibly even you months later.. You need anyone to be capable of reading the code you create; not only for consistency, but general readbility as-well.

    - While writing everything the most "optimal" way in a scenerio *may* be more quick relatively, more likely than not either Luau automatically optimizes the operation at hand, or it's not harming preformance much to get more readability out of your code.

    - Think about and consider what the code diffs of your changes may look like. It's easier to read and review a diff that isn't a mess of moving everything around, and makes your changes more likely to be implemented sooner. If reviewers cant review your changes, how can you expect them to be merged?

- Treat more powerful/experimental features with care.
    - While more powerful Lua/Luau features like *Metatables* might be really nice to use and work with, they need to be handled with caution, and care. While these features may not necessarily be un-stable or bad to use, they need to be used with complete caution and awareness. It's best practiced to actually *use* these features as little as possible, and when needed make a library that handles that extra dirty work for you. That way, if an issue or error comes along later down the line, the problem can usually be easily spotted and fixed.

- Aim to be consistent with the natural flow and style of Luau; there's not much reason to go out of your way to avoid being idiomatic with Luau as intended. This guide simply helps direct the style of code to be somewhat standard.
