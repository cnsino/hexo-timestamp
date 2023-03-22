# hexo-timestamp
针对https://github.com/hluglk/hexo-number-title，做了一些修改
### INSTALL
```bash
# npm
npm install hexo-timestamp --save
# yarn 
yarn add hexo-timestamp
```

### COMMAND
```
$ hexo new test    
INFO  Created: ~/newblog/source/_posts/test.md

$ hexo number-title -h
Usage: hexo number-title 

Description:
hexo-number-title plugin, For all didn't set the permalink post

Options:
  -f, --force  overwrite permalink
```

### EXAMPLE

`hexo number-title`
```
# before
---
title: test
---

# after
---
title: test
idc: 1500846110
---
```

-----------------------

`hexo number-title -f`
```
# before
---
title: test
idc: has-been-set-value
---

# after
---
title: test
idc: 1500846112
---
```
---------------
`hexo new test`
```
---
title: test
idc: 1500846112
---
```
