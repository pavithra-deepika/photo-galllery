
<h1 align="center"> Flexbox Photo Gallery  </h1>

## Getting Started

- It is a HTML project for exploring the deep basic understanding of HTML and CSS

## Tech stack:
- browser
- Code Editor (like Visula Studio Code/ notepad)

## Application shots
![image1](https://github.com/pavithra-deepika/photo-galllery/blob/master/image/image1.png)


## Learnt
 - The img tag is used to embed an image in an HTML page.
        The img tag has two required attributes:
        <br />src - Specifies the path to the image<br />
        alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed.
- The div tag defines a division or a section in an HTML document.
- The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.
    - Block, for sections in a webpage
    - Inline, for text
    - Table, for two-dimensional table data
   -  Positioned, for explicit position of an element
- The text-transform property controls the capitalization of text.
    - Transform used to text all characters to uppercase, lowercase or the first character of each word to uppercase.
- The flex container becomes flexible by setting the display property to flex.
- The flex container properties are:
    - <strong>flex-direction</strong>
        - The flex-direction property defines in which direction the container wants to stack the flex items.
    - <strong>flex-wrap</strong>
        - The flex-wrap property specifies whether the flex items should wrap or not.The 12 flex items, to better demonstrate the flex-wrap property.
        (flex-wrap: wrap;)
        -   The wrap value specifies that the flex items will wrap if necessary:<br />
        ( display: flex;
          flex-wrap: nowrap;)
    - <strong>flex-flow</strong>
       - The flex-flow property is a shorthand property for setting both the flex-direction and flex-wrap properties.<br />
       ( display: flex;
         flex-flow: row wrap)
    - <strong>justify-content</strong>
       - The center value aligns the flex items at the center of the container:
       <br />( justify-content: center;)
       - The flex-start value aligns the flex items at the beginning of the container (this is default):
      <br /> (justify-content: flex-start)
      - The flex-end value aligns the flex items at the end of the container:
      <br /> (justify-content: flex-end;)
      - The space-around value displays the flex items with space before, between, and after the lines<br /> (  justify-content: space-around;)
      - The space-between value displays the flex items with space between the lines:<br />
      (  justify-content: space-between;)
    - <strong>align-items</strong>
        - The align-items property is used to align the flex items.Vertically aligns the flex items when the items do not use all available space on the cross-axis
        <br />
            - center: value aligns the flex items in the middle of the container.

        - The flex-start value aligns the flex items at the top of the container.<br />
        - The flex-end value aligns the flex items at the bottom of the container.<br />
        - The stretch value stretches the flex items to fill the container.<br />
        - The baseline value aligns the flex items such as their baselines aligns.<br />
       syntax = .flex-container {
  <br /> display: flex;
  <br />height: 200px;
  <br />align-items: baseline;
}
    - <strong>align-content</strong>
       - The align-content property is used to align the flex lines.
       Modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex items, it aligns flex lines.
       - <strong> Space-between : </strong>The space-between value displays the flex lines with equal space between them.
       - <strong>Space-around : </strong>The space-around value displays the flex lines with space before, between, and after them.
       - <strong> stretch : </strong>The stretch value stretches the flex lines to take up the remaining space (this is default).
       - <strong> center : </strong>The center value displays the flex lines in the middle of the container.
       - <strong> flex-start : </strong>The flex-start value displays the flex lines at the start of the container.
       - <strong> flex-end : </strong>The flex-end value displays the flex lines at the end of the container.
       <br>
       <strong> syntax = .flex-container {
  <br /> display: flex;
  <br />height: 600px;
  <br />flex-wrap: wrap;
  <br /> align-content: flex-end;
}</strong>
    - <strong>display </strong>
    	- Specifies the type of box used for an HTML element

    - <strong> object-fit </strong>
      - The CSS object-fit property is used to specify how an img or video should be resized to fit its container.
      -  <strong> fill</strong> - This is default. The image is resized to fill the given dimension. If necessary, the image will be stretched or squished to fit
      - <strong> contain </strong> - The image keeps its aspect ratio, but is resized to fit within the given dimension
      - <strong>cover </strong>- The image keeps its aspect ratio and fills the given dimension. The image will be clipped to fit
      -  <strong> none  </strong>- The image is not resized
    scale-down - the image is scaled down to the smallest version of none or contain.

        



## Deploy on Vercel
https://photo-galllery-lttkza79o-pavithra-deepika.vercel.app/
## Built by

👤 **Bavithra**








