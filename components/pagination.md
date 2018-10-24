---
layout: component-detail
group: components
permalink: /components/pagination.html

title: Pagination
description: Pagination is used for splitting up content or data into several pages, with a control for navigating to the next or previous page.

variations:
- title: Overview
  pattern: pagination/pagination.html
  storybook: https://react-bootstrap-table.github.io/react-bootstrap-table2/storybook/index.html?selectedKind=Row%20Selection&selectedStory=Single%20Selection&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybook%2Factions%2Factions-panel
---

## Usage

Generally, Pagination is used if there are more than 25 items displayed in one view. The default number displayed will vary depending on the context.

## Best practices

### Identify the current page

Clearly identify which page the user is on my displaying the current page number. By providing context into how many pages there are in total (eg. 1 of 4 pages), you can help provide clarity around the data displayed.