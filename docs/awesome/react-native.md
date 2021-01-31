---
title: React Native
---

<Alert type="info">
  欢迎 <a href="https://github.com/youngjuning/youngjuning.github.io/edit/main/docs//awesome/react-native.js">新增数据</a> 并提交 PR.
</Alert>

## 文章

```jsx
/**
 * inline: true
 */
import React from 'react';
import { artist } from './react-native';
import ArtistList from '../../components/List/ArtistList';

export default () => {
  return <ArtistList data={artist} />;
};
```