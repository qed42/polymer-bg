# **polymer-bg** Element

A polymer element to evenly distribute the photos across rows or columns, making the most of the space provided.

## Using **polymer-bg** Element in your Project

Install this using bower

```
$ bower install polymer-bg --save-dev
```

Add the element element using html imports

```
<link rel="import" href="../polymer-bg.html">
```

And you can now use the tag as follows,
```

<polymer-bg bg-background="http://placekitten.com/335/283" ideal-width="300" bg-orientation="vertical">
  <img src="http://placekitten.com/335/283" />
  <img src="http://placekitten.com/325/596" />
  <img src="http://placekitten.com/580/365" />
  <img src="http://placekitten.com/282/581" />
  <img src="http://placekitten.com/503/319" />
  <img src="http://placekitten.com/549/577" />
  <img src="http://placekitten.com/355/493" />
  <img src="http://placekitten.com/500/150" />
  <img src="http://placekitten.com/360/529" />
  <img src="http://placekitten.com/589/361" />
  <img src="http://placekitten.com/452/462" />
  <img src="http://placekitten.com/550/304" />
  <img src="http://placekitten.com/352/204" />
  <img src="http://placekitten.com/400/220" />
</polymer-bg>
```
### Available attributes

1. **auto-resize** - re-partition and resize the images when the window size changes
2. **bg-background** - the css properties of the gallery's containing element
3. **ideal-height** - only used for horizontal galleries, defaults to half the containing element's height
4. **ideal-width** - only used for vertical galleries, defaults to 1/4 of the containing element's width
5. **maintain-order** - keeps images in their original order, setting to 'false' can create a slightly better balance between rows
6. **bg-orientation** - 'horizontal' galleries are made of rows and scroll vertically; 'vertical' galleries are made of columns and scroll horizontally
7. **bg-padding** - Space in pixels between images


## Contributing (Issue/PR)

For contributing feel free to create an issue or raise a PR.


## MIT LICENSE

Copyright 2016

Saket Kumar  saki007ster@gmail.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
