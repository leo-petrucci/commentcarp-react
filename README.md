# Commentcarp React

Commentcarp React is a simple hook implementation of the [Commentcarp](https://commentcarp.com/) script.

## About Commentcarp

Commentcarp is an easy and privacy-oriented comment system for your website. It's a simple, easy-to-use, and secure way to add comments to any site.

## How to use

```
yarn add commentcarp-react
```

or

```
npm install commentcarp-react
```

Then, wherever you want Commentcarp to display its editor:

```jsx
import { useCommentcarp } from 'commentcarp-react';

const Commentcarp = () => {
  const _cc = useCommentcarp('your Commentcarp API key');
  return <div id="commentcarp" />;
};
```

Commentcarp will load on any page that uses the `useCommentcarp` hook and that contains a `#commentcarp` element.
