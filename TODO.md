# TODO:

**`A`**

- [x] `😌` Increase / fix font-size
  - [x] Body
  - [x] H5, H6
  - [x] Menu & theme select
- [x] `🤓` Fix bullet threading for embed blocks
- [x] `🧐` Border left bug for inline elements
- ~~Re-add border-left fix for compatibility<0.5.9~~
  - <sup>_Due to breaking changes in logseq's releases → not possible to add version specific CSS to support versions\<0.5.9 using one only one branch with one release version._</sup>

---

**`B`**

- [x] `😌` Add rounded borders to codeblocks, quotes etc. for style consistency
- [x] `😌` Fix light theme colors
  - [x] PDF annotations page - heading color
  - [x] PDF toolbar button colors
  - [x] Bullet fold hovers
  - [x] Secondary-text-color
  - [x] Code color using single backticks \` \`
- [x] `😌` Align codeblock lang
- [x] `😌` PDF preview
- [x] `😌` Other visual hint then strike for finished todos
- [x] Update `README.md`
  - [x] Add how to change color scheme
  - [x] Info to disable bullet threading plugin as it can conflict with integrated bt
- [ ] `🧐` Cleanup, sort & refactor CSS!
  - [ ] Add table of contents & better comments
- [x] `😌` Button color for dark mode in delete dialog

---

**`C`**

- ~~Update style in TODOs lists for style consistency~~
- [ ] `🤓` Update icon

---

`Unsorted`

- [x] Fix & improve spacing after inferences in last update
- [x] Better contrast / visual hint for links
- [x] Improve bullet threading on inline blocks
- [x] Horizontal line color
- [x] Light theme menu button color
- [x] Improve spacing on level one elements
  - _E.g. making some quick notes using only level-one items without further formatting and indenting, the spacing between items is too large._

---

**Keys:**<br />
Priorities: `A` → `B` → `C`<br />
Estimated difficulty / time required: Low `😌` | Medium `🤓` | High `🧐`

<!-- Alternative: Low `🤙` | Medium `👌` | High `🤞` -->

---

## Plugin Support

- [ ] ~~Background color in marketplace previews<sup>(\*)</sup>~~
- [x] Tabs<sup>(\*)</sup>
  - [x] Style
  - [ ] Release cross theme compatible fork
  - [ ] Move margin-top for main content from theme.css to tabs-plugin so it'll be added conditionally when the plugin is used
- [ ] Tag-Search<sup>(\*)</sup>
- [x] TOC Generator Plugin
  - [x] Light theme background

<sub>_(\*)Marketplace previews and many plugins are implemented as iframe. Due to this the plugins miss implementation of Logseq's `styles.css`. Which makes it hardly possible to style those plugins inside it's iframe directly with the themes CSS._</sub>

---

## Info

_Most likely there are many more improvements to make.<br />_
_Admittedly I'm currently not using Loegseq as my main PKM tool. I'll probably start doing so for the specific purpose of technical or study knowledge management in the near future.<br />_
_Therefore not being exposed to it regularly at the moment, I'm missing out on spotting those possible improvements.
So feel free to open an issue and let me know when you see something that can be improved._
