# CSS Projects
## CodePen [Sasha Tran](https://blog.prototypr.io/how-i-started-drawing-css-images-3fd878675c89#.aa6bq2aez)
### Swaying Faces
Taken from project [#codevember - 1](http://codepen.io/sashatran/pen/WGVGVx).
#### Reflections
The faces in the original were IDed by number ("one", "two", &c.), but I changed that to positional representation (e.g., "middle-face", "right-middle-face"). The thinking is that it would make it easier to see at-a-glance which div refers to which face. In retrospect, this might not have been a good idea, as it now restricts each face to its position. For example, what if I want to modify the project so that one or more faces moves positions? Then their IDs will no longer make sense.

In general, it might not be a good idea to ID elements by transient properties (like color or position) that are subject to change. Maybe a numbering scheme (which amounts to an arbitary name like "Bill" or "Cathy") is best after all&hellip;
