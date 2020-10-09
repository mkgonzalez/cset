**The tools and techniques for web development have changed a lot over the years. How will you personally try to keep up with those changes and where can you look to find them?**

To keep up with the changing tools and techniques, I will try to find websites that let me know about them.

**The lecture and readings discussed the limitations of using floats for layout. What are some of these limitations? Provide an example.**

Floats were not intented to be used in the way they were actually used for. They were primarily meant to create an element which something could flow around. People used them in hacky ways to do interesting things. However, using flexbox is much simpler and less hacky. In flexbox, you can vertically align things, which I do not think is possible with just floats. 

**Flexbox is built to be language agnostic, so it uses generic terminology like the "Main" or "Cross" axis. Choose a flex property that affects one of these axes on a flex container and explain how it is used. Show how the result can change based on different flex directions and different writing modes.**

A property that affects the main axis is `justify-content`. It allows the content in the container to be moved. The options are `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`. Each option moves the content differently. The direction of the axes depends on if the container is a column or row. When it is a row, the main axis goes from left to right. With a column, the container is practically rotated 90 degrees and the main axis becomes up and down. It is the opposite for the cross axis. 
