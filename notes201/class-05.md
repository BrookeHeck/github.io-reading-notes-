# Images, Color, Text

## Summary
Websites would not be nearly as exciting and good looking without images, videos, audio, and other media that isn't text. The first reading walked me through how to include all these multimedia forms into a webpage. Another important article talked about tools to help make images responsive on different screen sizes. This is really important since websites need to be viewable on both tiny smartphones and huge monitors. This also ties in with using the right image type depending on what the image is and what it will be used for.
\
There are so many CSS styling and coloring properties that I'm sure I will never need them all. It is still very important to learn the common ones and be able to find some of the more unusual ones should I need them. This reading built on my knowledge of CSS by explaining how to style and color fonts and elements using CSS.

## HTML Media
1. What is a real world use case for the alt attribute being used in a website?
- A slow internet connection might not load the image.
- A description would help a visually impaired person using a screen reader.
- Search engines match search queries with alt text.
- The browser might not support the image type being used.
- A user may have turned off images.

2. How can you improve accessibility of images in an HTML document?
- Give images alt text or a title.
- Use an image editor to correct the aspect ratio.
- Use the correct image type and CSS styling to make the image responsive to different screen sizes.

3. Provide an example of when the figure element would be useful in an HTML document.
- Using the figure and figcaption semantic elements is better when you have an image with a caption. It can be used to link the correct figure with the correct caption. This is a useful feature if you have many figures with captions.

4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
- GIF is a good choice for simple images and animations.
- This is vector image format and better for displaying something at different sizes.

5. What image type would you use to display a screenshot on your website and why?
- Lossless WebP format is the best for screenshots because the image will be clearer when compressed. 

## CSS Color and Styling
1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
- The foreground color property applies color the actual content within the HTML tag. So if a paragraph element had text, only the color of the text would change.
- The background-color property applies color to the background of the element. So the space around that paragraph element would have the specified color.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
- There are plenty of ways to use color in a website, but common ones include foreground and background color, colored borders, emphasizing text with color.
- Good coloring techniques can also help touch up his blog. Using a color palette can help the website look more put together. Contrast created by applying different colors could draw the user's eye to important sections of the website.

3. What should you consider when choosing fonts for an HTML document?
- Consider the font style. Font style definitely adds to the text of website, but make sure it is clear and easy to read. Also, check that the font is combatable with the major browsers. Consider using third-part fonts, like Google fonts, which can be linked to an HTML page and will work on any browswer.
- Consider font layout styles. This would be properties that affect spacing and positioning. Changing the font layout can add design, contrast, and emphasis to text in the website, but make sure it is not to busy or hard to read.

4. What do font-size, font-weight, and font-style do to HTML text elements?
- The font-size property will make text bigger or smaller. Common units are px, em, and rem.
- The font-weight makes text  bold or lighter. This is done on a numeric scale from 100 - 900 with the higher numbers darker and the smaller numbers lighter.
- The font-style is used to make text italic or normal.

5. Describe two ways you could add spacing around the characters displayed in an h1 element.
- The letter-spacing property sets the amount of spacing between each indiviual letter.
- The word-spacing property sets the amount of spacing between each word.
```
 h1 {
  letter-spacing: 5px;
  word-spacing: 5px;
 }
```

## Things I want to learn more about
- SVG is becoming a popular way to display images because there are many different screen sizes from smart smartphones to large TV monitors. I would like to learn how to make my own SVG images.

### Links
[Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)
\
[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
\
[Image file type and format guide](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
\
[Applying color with CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
\
[Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)