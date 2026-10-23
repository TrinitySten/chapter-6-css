# Chapter 6 CSS Lab — Starter

Open `index.html` in a browser and edit `styles.css` in your editor. No textbook downloads, accounts, or external image links are required.

The supplied HTML contains a wrapper, header, nav, main, feature section, two cards, and footer. The landscape illustration is in `assets/landscape.svg`.

Create separate files named `practice-01.html` through `practice-08.html` by copying `index.html` as needed; each practice should have its own clearly labeled CSS rules or an accompanying stylesheet. You can keep practicing on one page, but save a snapshot for each numbered activity to document your progress.

Create `css-experiment.html` and `experiment.css` for the original final challenge. You may reuse the starter structure but customize the topic and content.

Upload the entire folder to GitHub, deploy it on Vercel, and submit the links and reflection in Canvas.

REFLECTION:
How do padding, border, and margin differ? Explain with an example from your own page.
    Padding creates extra space between the content (html) and the border. If an html element has no padding but has a border, it would be bound directly to the box surrounding the text. I added some side padding to the text n the two q&a cards at the bottom of the page because it sat too close to the sides of the border for my taste.

    Margin determines the spacing between an element and other elements surrounding it. Like the sample content, I used the margin to center my page.
    
    Borders are what they sound like. They configure borders or "outlines" to an element. I put a border outside my entire page wrapper to separate it the black box from the dark background.

What is the practical difference between width, min-width, and max-width?
    width configures the width of an element in a browser, regardless of form factor.
    min-width sets the minimum width of an element within a browser. Depending on the viewport, the content will stop shrinking past a certain defined point. I like to think this is good when configuring content for mobile devices
    max-width sets the maximum width of an element within a browser. The content will stop expanding past a certain point defined in the max-width property. This is good to keep in mind for browsers

Why might you choose an RGBA background color instead of using opacity on the whole element?
    Opacity affects both text and background, which may affect text legibility. Rgba can be applied to a single element and can configure transparency on just a text background element.

What did you observe when testing background-size: cover versus contain?
    Cover will maintain the original dimensions of an image and scale it to the smallest size that can fit both the width and height of a background.
    Contain will maintain the original dimensions of an image to the largest size that an image will fit within an area. The image will repeat unless set to "background-repeat: no-repeat".

What CSS adjustment made the biggest improvement in your design? Why?
    Adding side padding to the all my paragraph elements so they sat nicely in the page. I also used line-height to make the line spacing slightly wider. For my website, I didn't need to apply cover or contain elements since my backgrounds are tiled and intended to repeat near seamlessly. Shoutout to neocities.