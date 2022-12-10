# Reading

Video and Audio Content

Explain how the ability to use video and audio on the web has evolved since the early 2000s.

- used to use flash or silverlight, which are unsecured and now obsolete.

Describe the use of the src and controls attributes in the <video> element.

- src works the same was here as it does for images, controls gives the user a way to interact with the video content, pause play etc

Why is it important to have fallback content inside the <video> element?

- fallback accessibility in case the embedding fails.

Write a very short story where audio and video are characters.

- audio and video are students that attend Media Acadamey, video goes to only movie media classes, and audio only goes to music classes. They don't often understand each other.

## A Complete Guide To Grid

How does Grid layout differ from Flex?

- flex offers only one directional flow, grid offers precise multidirectional flow.

Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- grid container is where we put display: grid; and it is the parent of all the elements we will use grid to manipulate
- grid item direct descendant child of parent grid container
- grid line either vertical or horizontal line  on either a row or column.

## Responsive Images

Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- so the site makes sense across all access types, accessibility, and usability when users are using multiscreens.

Define the following img attributes srcset and sizes. Write an example of how they are used.

- srcset defines the set of images the browser can use, and what size each image is.
- from mdn: An image filename (elva-fairy-480w.jpg)
A space
The image's intrinsic width in pixels (480w) — note that this uses the w unit, not px as you might expect. An image's intrinsic size is its real size, which can be found by inspecting the image file on your computer (for example, on a Mac you can select the image in Finder and press Cmd + I to bring up the info screen).

- from mdn: A media condition describes a possible state that the screen can be in. In this case, we are saying "when the viewport width is 600 pixels or less".
A space
The width of the slot the image will fill when the media condition is true (480px)

How is srcset more helpful for responsive images than CSS or JavaScript?

- because it can use implicit data to come up with dynamic imaging , instead of having to manually set values for every contingency.
