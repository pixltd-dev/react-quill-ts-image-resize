# React Quill Image Resize module 

As I noticed that any of the current image resize modules are not working in latest quill in react ts, so here is solution for those fighting the same battle.

Made it as easy as possible, just download the [typescript module file](ImageResize.ts), put it in your project, and use like this:

```
Quill.register('modules/imageResize', ImageResize);

const modules = {
  ...
  imageResize: {},
  ...
};
```

Hope it helps ✨
