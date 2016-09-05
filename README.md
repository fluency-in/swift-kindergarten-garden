# Swift: Kindergarten Garden

Write a program that, given a diagram, can tell you which plants each child in the kindergarten class is responsible for.

The kindergarten class is learning about growing plants. The teachers
thought it would be a good idea to give them actual seeds, plant them in
actual dirt, and grow actual plants.

They've chosen to grow grass, clover, radishes, and violets.

To this end, they've put little styrofoam cups along the window sills,
and planted one type of plant in each cup, choosing randomly from the
available types of seeds.

```plain
[window][window][window]
........................ # each dot represents a styrofoam cup
........................
```

There are 12 children in the class:

- Alice, Bob, Charlie, David,
- Eve, Fred, Ginny, Harriet,
- Ileana, Joseph, Kincaid, and Larry.

Each child gets 4 cups, two on each row. The children are assigned to
cups in alphabetical order.

The following diagram represents Alice's plants:

```plain
[window][window][window]
VR......................
RG......................
```

So in the row nearest the window, she has a violet and a radish; in the
row behind that, she has a radish and some grass.

Your program will be given the plants from left-to-right starting with
the row nearest the windows. From this, it should be able to determine
which plants belong to which students.

For example, if it's told that the garden looks like so:

```plain
[window][window][window]
VRCGVVRVCGGCCGVRGCVCGCGV
VRCCCGCRRGVCGCRVVCVGCGCV
```

Then if asked for Alice's plants, it should provide:

- Violets, radishes, violets, radishes

While asking for Bob's plants would yield:

- Clover, grass, clover, clover

In order to use Swift, you must be running Xcode version 7.3 or greater which is available at [Apple's developer center][appledev].

[appledev]: https://developer.apple.com/xcode/downloads/

The exercises use XCTest.

See [this guide][exercism-xcode-swift] for details about how to create the project in XCode and run the tests.

[exercism-xcode-swift]: https://github.com/exercism/xswift/blob/master/docs/TESTS.md

## Source

Random musings during airplane trip. [http://jumpstartlab.com](http://jumpstartlab.com)

This exercise is from the [Swift][swift] track on [Exercism][exercism]

[exercism]: http://exercism.io
[swift]: http://exercism.io/languages/swift



