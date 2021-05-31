```
{
  // cx 기본
  "Print to cx" : {
    "scope": [
      "js"
    ],
    "prefix": "br,cx",
    "body": [
      "<br className={cx('$1')} />"
    ],
    "description": "cx snippet"
  },
  // cx 기본
  "Print to cx" : {
    "scope": [
      "js"
    ],
    "prefix": "cx",
    "body": [
      "{cx('$0')}"
    ],
    "description": "cx snippet"
  },
  // div cx1
  "div Class to cx1" : {
    "scope": [
      "js"
    ],
    "prefix": "div,cx",
    "body": [
      "<div className={cx('$1')}>${2}</div>"
    ],
    "description": "div cx snippet"
  },
  // div cx2
  "div Class to cx2" : {
    "scope": [
      "js"
    ],
    "prefix": ",cx",
    "body": [
      "<div className={cx('$1')}>${2}</div>"
    ],
    "description": "div cx snippet"
  },
  // section
  "section Class to cx" : {
    "scope": [
      "js"
    ],
    "prefix": "section,cx",
    "body": [
      "<section className={cx('$1')}>${2}</section>"
    ],
    "description": "section cx snippet"
  },
  // p cx
  "p Class to cx" : {
    "scope": [
      "js"
    ],
    "prefix": "p,cx",
    "body": [
      "<p className={cx('$1')}>${2}</p>"
    ],
    "description": "p cx snippet"
  },
  // span cx
  "span Class to cx" : {
    "scope": [
      "js"
    ],
    "prefix": "span,cx",
    "body": [
      "<span className={cx('$1')}>${2}</span>"
    ],
    "description": "span cx snippet"
  },
  // b cx
  "b Class to cx" : {
    "scope": [
      "js"
    ],
    "prefix": "b,cx",
    "body": [
      "<b className={cx('$1')}>${2}</b>"
    ],
    "description": "b cx snippet"
  },
  // template cx
  "cs template" : {
    "scope": [
      "js"
    ],
    "prefix": "cxt",
    "body": [
      "import React from 'react';",
      "import classNames from 'classnames/bind';",
      "import style from './${1:style}.scss';",
      "",
      "const cx = classNames.bind(style)",
      "",
      "const ${2:component} = () => {",
      "  return (",
      "    ${3}",
      "  )",
      "}",
      "export default ${2:component};"
    ],
    "description": "cx template auto"
  },
}
```
