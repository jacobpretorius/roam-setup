# Roam Setup
How I like my Roam. Tiny tweaks to the [Roam Research Dark by Daniel](https://github.com/vandermerwed/Roam-Research-Dark).

1. Install [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
2. [![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://raw.githubusercontent.com/vandermerwed/Roam-Research-Dark/master/roam-research-dark.user.css)
3. Make sure "Use theme" and "Use wide layout" are enabled in Stylus theme options
4. Apply the below in a code block (with language as CSS) to a Roam page called `roam/css`

```css
h1.rm-title-display > span
{
  color: #328fe0 !important;
}

.rm-page-ref-link-color {
  color: #3f87b3 !important;
}

/* hide bullets */
.simple-bullet-outer.cursor-pointer,
.rm-bullet .rm-bullet__inner{
  opacity: 0;
  color: white !important;
}

.simple-bullet-outer.cursor-pointer:hover {
  opacity: 1;
  background-color: #3f87b3;
}

.controls {
  flex: 0 0 23px;
}

/* layout stuff */
.roam-article > div:last-child {
  margin-top: 4em !important;
  border-top: 1px solid;
}

.roam-center > div#buffer {
  bottom: 5px !important;
  right: 5px !important;
}
```
