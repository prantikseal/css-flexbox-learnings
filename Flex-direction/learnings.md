# Working with Flexbox flex-direction

Flex direction is used to control the direction of the flex items.
- The default direction is `row`, which means the flex items are laid out horizontally.

- When the flexdirection is `row`, the flex items are laid out `horizontally`.
- When the flexdirection is `column`, the flex items are laid out `vertically`.

The basic syntax is: `flex-direction: row/column`.

When we consider flex-direction we consider two axis:
- The main axis is the axis that the flex items are laid out on.

<a href="https://i.ibb.co/6s3rCsG/image.png"><img src="https://i.ibb.co/6s3rCsG/image.png" alt="image" border="0"></a>

- The cross axis is the axis that the flex items are laid out on.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/qy0fsdm/image.png" alt="image" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />

Now when flex-direction is `row`:
- the main axis is the horizontal axis.
- The cross axis is the vertical axis.

And when flex-direction is `column`:
- the main axis is the vertical axis.
- The cross axis is the horizontal axis.

There is another set of flex-direction:
- `row-reverse`: The flex items are laid out horizontally, but the direction of the flex items is reversed.
- `column-reverse`: The flex items are laid out vertically, but the direction of the flex items is reversed.
