# git-ecommit

A simple utility for adding emojis to commit messages.

## Installation

```bash
pip3 install --user git+https://github.com/johannfr/git-ecommit.git
```

## Usage

Takes the `--emoji` argument and prepends it to commit messages. Passes all other arguments on to `git commit`

### Example
```bash
$ git ecommit --emoji bug -m "The thing was buggy"
[main (root-commit) 0022758] 🐛 The thing was buggy
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 foobar
```

### List of emojis
For a full list of supported emojis, specify a non-existing keyword, such as `help`:
```bash
git ecommit --emoji help
```

♿ access: Improving accessibility<br />
📈 ana: Adding analytics or tracking code<br />
🤖 android: Fixing Android specific functionality<br />
🏗 arch: Making architectural changes<br />
🍱 assets: Adding or updating assets<br />
📦 bin: Updating compiled files or packages<br />
💥 break: Introducing breaking changes<br />
🐛 bug: Fixing a bug<br />
👷 ciadd: Adding continuous integration CI build system<br />
💚 cifix: Fixing continuous integration CI build<br />
🔧 conf: Changing configuration files<br />
👥 contrib: Adding contributor<br />
🗃 db: Performing database related changes<br />
➕ depadd: Adding a dependency<br />
⬇️ depdown: Downgrading dependencies<br />
🚀 deploy: Deploying stuff<br />
➖ deprm: Removing a dependency<br />
⬆️ depup: Upgrading dependencies<br />
📝 doc: Writing documentation<br />
🐳 docker: Docker functionality<br />
💡 docsrc: Documenting source code<br />
🍻 drunk: Writing code drunkenly<br />
🥚 easteregg: Adding an Easter egg<br />
⚗ experiment: Experimenting with new things<br />
👽 extapi: Updating code due to external API changes<br />
🎨 format: Improving structure or format of code<br />
🙈 gitignore: Adding or updating .gitignore<br />
🚑 hotfix: Critical hotfix<br />
🌐 i18n: Internationalization and localization<br />
🎉 init: Initial commit<br />
🍏 ios: Fixing iOS specific functionality<br />
☸️ kubernetes: Kubernetes functionality<br />
📄 lic: Adding or updating license<br />
🚨 linter: Removing linter warnings<br />
🐧 linux: Fixing Linux specific functionality<br />
🔊 logadd: Adding logs<br />
🔇 logrm: Removing logs<br />
🍎 macos: Fixing macOS specific functionality<br />
🔀 merge: Merging branches<br />
🤡 mock: Mocking things<br />
🚚 mv: Moving or renaming files<br />
✨ new: Introducing new features<br />
⚡️ perf: Improving performance<br />
📌 pin: Pinning dependencies to specific versions<br />
🚧 progress: Work in progress<br />
♻️ refactor: Refactoring code<br />
📱 responsive: Working on responsive design<br />
⏪ revert: Reverting changes<br />
👌 review: Updating code due to code review changes<br />
🔥 rm: Removing code or files<br />
🔒 sec: Fixing security issues<br />
🔍 seo: Improving search engine optimization SEO<br />
💩 shit: Writing bad code that needs to be improved<br />
📸 snapshot: Adding or updating snapshots<br />
🔖 tag: Release or version tags<br />
✅ tests: Updating tests<br />
💬 text: Updating text and literals<br />
🏷️ types: Adding or updating types<br />
✏️ typo: Fixing typos<br />
💄 ui: Updating user interface UI and style files<br />
🚸 ux: Improving user experience UX usability<br />
🏁 win: Fixing Windows specific functionality<br />
