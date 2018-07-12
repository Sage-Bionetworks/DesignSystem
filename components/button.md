---
layout: component-detail
group: components

title: Buttons
description: Buttons express what action will occur when the user clicks or touches it. Buttons are used to initialize an action, either in the background or foreground of an experience.
status: Complete

variations:
- title: Button types
  description: Several predefined button styles, each serving its own semantic purpose, with a few extras thrown in for more control.
  pattern: buttons/button-types.html
- title: Tag variants
  description: The `.btn` classes are designed to be used with the `<button>` element. However, you can also use these classes on `<a>` or `<input>` elements (though some browsers may apply a slightly different rendering).
  pattern: buttons/button-tags.html
- title: Sizes
  description: Fancy larger or smaller buttons? Add `.btn-lg` or `.btn-sm` for additional sizes.
  pattern: buttons/button-sizes.html
---

## General guidelines

Buttons are used primarily on action items. Some examples include Add, Save, Delete, Sign up. Do not use Buttons as navigational elements. Instead, use Links because it takes the user to a new page and is not associated with an action. Each page may have one to two primary buttons. Any remaining calls-to-action are represented as secondary buttons.

## Usage

| Button type     | Purpose                                                                          |
| --------------- |----------------------------------------------------------------------------------|
| Primary         | For the principle call to action on the page.                                    |
| Secondary       | When an action does not require primary dominance on the page.                   |
| Danger          | When an action has harmful intentions to the users data (delete, remove, etc).   |
| Disabled button | Use when the user cannot proceed until an input is collected.                    |
| Small Button    | Use when there is not enough vertical space for a regular sized button.          |


## Labels

Button labels tell users what will happen when they click the button. Use verbs that describe the action, such as Add or Delete. Use sentence-style capitalization (only the first word in a phrase and any proper nouns capitalized) and no more than three words for button labels.

For Sets of Buttons, use specific labels, such as Save or Discard, instead of using OK and Cancel. This is particularly helpful when the user is confirming an action.

## Icon usage

* Use glyphs (16px) within buttons.
* Glyphs are distinguished by their solid shape and knocked-out details.
* Glyphs should always appear to the right of the text.
* Glyphs used in buttons must be directly related to the action that the user is taking.
* Glyphs must be the same color value as the text within a button.
* Ghost buttons require a glyph icon (cannot be stand alone text because of poor affordance).

## Other rules

1. Rule 1
2. Rule 2
3. Rule 3
4. Rule 4
