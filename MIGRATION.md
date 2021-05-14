## Migration Guide

# 5.0.x -> 5.1.x
Before:
```js
import ViewPager from '@react-native-community/viewpager'
import  { ViewPagerOnPageScrollEventData,ViewPagerOnPageSelectedEventData } from '@react-native-community/viewpager';
```

After:
```js
import PagerView from 'react-native-pager-view';
import  { PagerViewOnPageScrollEventData, PagerViewOnPageSelectedEventData } from 'react-native-pager-view';
