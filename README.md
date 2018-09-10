
# react-gantt-timeline
[![npm](https://img.shields.io/npm/v/react-gantt-timeline.svg?style=flat-square)](http://npm.im/react-gantt-timeline)
[![MIT License](https://img.shields.io/npm/l/react-list.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Travis](https://travis-ci.org/guiqui/react-timeline.svg?branch=master)](https://travis-ci.org/guiqui/react-timeline)
[![codecov](https://codecov.io/gh/guiqui/react-timeline/branch/master/graph/badge.svg)](https://codecov.io/gh/guiqui/react-timeline)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/9149e301e65b44cebf2e7b49316aee10)](https://www.codacy.com/app/gquiman/react-timeline?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=guiqui/react-timeline&amp;utm_campaign=Badge_Grade)

## Intro
An awesome blazing fast timeline component.
- Super fast. 😛
- Infinite scrolling.
- Made to be use with Redux.
- Support paging.
- Can render more than a 100k records.
- Implemented with virtual rendering.

## Road Map
- Full Test coverage.
- Hierachical data.
- Day and week view.
- Gantt lines and constrains.

## Installation
```javascript
npm install react-gantt-timeline
```
## Defining Timeline Data
The timeline data can be set with the data property of the time line.
The data needs to be an array of object.
Each item of the array needs to contain the following elements.

| Property      | value   | Descriptions                        |
| ------------- |:-------:| -----------------------------------:|
| start         | date    | The start date of the task          |
| end           | date    | The end date of the task            |
| name          | string  | The name of the task to be diplayed |

## Demo
Check out a working demo [here](https://guiqui.github.io/react-timeline/index.html)




## Some Demo Code
- [![Edit n09l7m400j](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/n09l7m400j) Simple Demo.
