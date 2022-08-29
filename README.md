# VSCode Spok

A VSCode extension providing language support and syntax highlighting for spokfiles, the declarative language used by the [spok] build system/task runner.

**Before:**
![plain](https://github.com/FollowTheProcess/vscode-spok/raw/main/images/plain.png)

**After:**
![highlighted](https://github.com/FollowTheProcess/vscode-spok/raw/main/images/highlighted.png)

## Features

Right now it's very barebones, just simple comments, strings and keywords, even this though results in quite a nice appearance 🙂

### Roadmap

- [x] Global variable declarations are highlighted as constants or variables
- [ ] Native understanding of functions (not just as keywords)
- [ ] Task names are highlighted as function names might be (including in args of other tasks)
- [ ] Task command lines are highlighted as actual shell syntax
- [ ] Snippets!
- [ ] Potentially some more advanced functionality like autocomplete, task running etc.

## Release Notes

### 0.1.0

Initial barebones release 🎉

[spok]: https://github.com/FollowTheProcess/spok
