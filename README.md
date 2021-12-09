# Resume / CV static site

Utilizing react-static, typescript, tailwindcss...

Uses a slightly modified/enhanced version of JsonResume with custom parsing on-the-fly.


---


## Path Aliases for Absolute Imports

`react-static-typescript-plugin` supports path aliases [since v3.1](https://github.com/react-static/react-static/pull/963#issuecomment-455596728). It has been set up in this template.

```js
// tsconfig.json
{
  // ...
    "paths": {
      "@components/*": ["src/components/*"]
    },
  // ...
}

// this works in your React app
import FancyDiv from '@components/FancyDiv'
```
