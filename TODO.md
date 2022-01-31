# TODO:

**`A`**

- [x] `😌` Increase / fix font-size
  - [x] Body
  - [x] H5, H6
  - [x] Menu & theme select
- [ ] `🤓` Bullet threading on block embed
- [x] `🧐` Border left bug for inline elements
- [ ] `😌` ~~Re-add border-left fix for compatibility<0.5.9~~
  - <small>Due to breaking Changes in program version → not possible to add version logseq version specific CSS to support other versions.</small>

**`B`**

- [x] `😌` Fix light theme colors
  - [x] secondary-text-color
  - [x] code color using single backticks \` \`
- [x] `😌` Align codeblock lang
- [ ] `😌` PDF preview
- [ ] `😌` Background color in marketplace previews
- [ ] `😌` Other visual hint then strike for finished todos
- [x] Update `README.md`
  - [x] Add how to change color scheme
  - [x] Info to disable bullet threading plugin as it can conflict with integrated bt
- [ ] `🧐` Cleanup, sort & refactor CSS!
  - [ ] Add table of contents & better comments
- [x] `😌` Button color for dark mode in delete dialog

**`C`**

- [ ] `🤓` Update icon

`Unsorted`

- [x] Fix & improve spacing after inferences in last update
- [x] Better contrast / visual hint for links
- [x] Improve bullet threading on inline blocks
- [x] Horizontal line color
- [x] Light theme menu button color
- [x] Improve spacing on level one elements
  - _E.g. making some quick notes using only level-one items without further formatting and children, spacing between items is too large._

---

**Keys:**<br />
Priorities: `A` → `B` → `C`<br />
Estimated difficulty / time required: Low `😌` | Medium `🤓` | High `🧐`

<!-- Alternative: Low `🤙` | Medium `👌` | High `🤞` -->

<small>_Mental note:
Make commits to `TODO.md` better comparable by not throwing them around - even though it can get unsorted and not that pretty.
→ Add new items and leave rest as it is._</small>

---

## Plugin Support

- [x] Tabs <small>(\*)</small>
  - [x] Styling
  - [ ] Release cross theme compatible fork
  - [ ] Move margin-top for main content from theme.css to tabs-plugin so it'll be added conditionally when the plugin is used
- [ ] Tag-Search <small>(\*)</small>
- [x] TOC Generator Plugin
  - [ ] Light theme background

<small>_(\*)Due to integration of many plugins as iframe and the plugins missing implementation of Logseq's `styles.css` and themes `custom.css`, it's hardly possible to style many plugins directly via theme css._</small>

---

## Info

_Most likely there are many more improvements to make.<br />_
_Admittedly I'm currently not using Loegseq as my main PKM tool. I'll probably start doing so for the specific purpose of technical or study knowledge management in the near future.<br />_
_Therefore not being exposed to it regularly at the moment, I'm missing out on spotting those possible improvements.
So feel free to open an issue and let me know when you see something that can be improved._
