# Audio, Video, Images

## Summary
The first article explained how video and audio tags are used to embed these types of media into a webpage. This is a really cool feature that allows external media to show right on a webpage instead of a link that the user would have to navigate. Creating these elements is very simple, by just using video and audio tags, but it is important to include the src of the video and callback controls for the user.
\
Grid was explained in the second article. This is another tool that can be used to structure a website. Grid has the advantage over flexbox because it is a two dimensional strucure using horizontal and vertical lines. This seems very helpful because when I was using flexbox I found I had to create a lot of sections and set the display depending on what direction I wanted that content to flow.
\
Lastly, I learned how to make responsive images. This is super important now that there a ton of screen sizes that are used to view webpages. The srcset and size tags are used to do this.

## Video and Audio Content
1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
- Before HTML5, there was no native support for any type of video and audio. Before the 2000s, this was not much of problem because bandwith was not fast enough to support this contet.
- In the the 2000s, developers started adding video and audio using third party technologies, but this had a number of problems. This included problems working with HTML/CSS, security issues, and accessibility issues. Today these technologies are not used anymore.
- HTML5 now supports video and audio with elements for both and also a JS API for controlling them.

2. Describe the use of the src and controls attributes in the video element.
- The src works the same as it does for the img tag and contains the path to the video
- the controls allow the user to control the video or audio and at a minimum include start, stop, and adjust volume

3. Why is it important to have fallback content inside the video element?
- If a browser doesn't support the video, then the fallback content is displayed. This could be a link to the video so that the user can still see it even if it is on a different website.

## A Complete Guide to Grid
1. How does Grid layout differ from Flex?
- Flexbox is a great layout tool, but only works in one dimension, row or column. The grid layout allows a developer to work with the layout in both directions.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
- Grid container: The grid container is the direct parents of all the items
- Grid item: The children of the grid container
- Grid Line: The horizontal and vertical lines that make up the structure of grid and strucutre the items on the page

## Responsive Images
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
- Many differnt devices can access the internet and they have varying screen sizes. Images should be responsive so that they aren't distorted on large or small screens.

2. Define the following img attributes srcset and sizes. Write an example of how they are used.
- srcset defines the set of images the browser can choose between
- size defines media conditions, usually screen widths, and what size the image should be set to when the media conditions are true
3. How is srcset more helpful for responsive images than CSS or JavaScript?
- Browsers preload images before the main parser starts in order to reduce load times. This means that images are already loaded before JS and CSS can dynamically change the size and this should be done in the HTML instead.

## Things I want to learn more about
- I skimmed through the grid article, but definitely would like to give it a try in an actual project

### Links
[VIdeo and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
\
[A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
\
[Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
\
[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
\
[Other embedding technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)