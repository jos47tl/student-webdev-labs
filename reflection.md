# Reflection Document

## HTML

I was able to complete exercises 1-3 on my own, but exercise 4 had me referencing the video to help me finish. I also needed the video for exercise one to fix a warning thrown up by the W3C Markup Validation tool. This is because I was nesting an unordered list in an ordered list. I fixed this by following the video and nesting the unordered list under a list element. Other than that, all the material required to do the first three exercises were covered in the slides/lectures. However, exercise four required the use of fieldset elements which are not in the slides. The spacing of the elements on the page was also hard to nail down. After creating all the elements of the pages I spent a good chunk of time trying to align everything to match the examples. I should ask about the differences between using the div and br tags to separate elements into separate lines. The solution videos seem to mix and match div and br tags to create space.

## Accessibility

I was able to complete this exercise on my own because we had gone over it in class and there was a similar exercise in the previous week's lab. This was helpful in reinforcing some old lessons in accessibility. I made sure that the name and input fields had associated labels with placeholder values. I also grouped the radio buttons together in a fieldset and made the text a legend. Finally, I made sure that each radio button was properly labelled so the label could be clicked to select the option. Pretty easy overall but it's good practice.

## CSS

### Selectors

This exercise was pretty simple. I was originally matching by checking equality but when I watched the video I realized that I should get more practice with the other types of matching. I threw in substring and suffix matching to cover multiple items and then matched "cat" and "parrot" individually, like shown in the video. I needed to refer back to the slides for the child and descendant selectors but I managed to complete it without the video.

### Pseudo

I completed this exercise pretty quickly. A similar example was shown in the slides and covered in class.

### Specificity

The topic of specificity was demonstrated in class with a handful of slides showing different examples. This made it relatively easy to calculate the specificity because I memorized that X-Y-Z represented id, class/attribute, and element respectively.

### Layout

I looked at the CSS and saw that the two blocks covered 75% and 25% which should add up to 100%. My first thought was that there might be some kind of margin or padding. I deleted the line with margin and saw that the spacing improved. However, I could not figure out how to get the boxes perfectly aligned until I saw the video. Swapping the content-box with border-box completed the exercise. I was not familiar with how the box-sizing property affected the layout.

### Position

A lot of trial and error was required to get everything into the right position. This was my first time trying to change the layout with CSS. I got a lot of it on my own but I had to watch the video to match the pixel counts exactly. I wasn't aware that negative values could be used for the position, which was required for the relative box.

### Media Queries

I was able to get the background color to change depending on the window size. It was mostly review from the slides in class. The hard part was matching the navbar style exactly to the screenshot. I ended up following a lot of the instructions from the video. It seems like fine tuning a page's layout takes a lot of trial and error.

## Flexbox

The flexbox examples required a lot of trial and error to nail down the layout. Many of the attributes required me to just see what happened when I applied them. I ended up skimming through the video to with my answers. Most of it was very similar with a few changes to certain numbers. The part that took the longest was container 5 because there were 3 different heights that had to be set for the flex items.

## CSS Grid

The first exercise was very simple and straightforward. The lecture and slides provided enough context for me to quickly create the column and row templates. The fractional unit "fr" made it very easy to guess what the units should be from just looking at the examples. For the second exercise, I needed to watch the video to remember to setup grid areas for each HTML class. Once that was done, however, it became a simple matter of using media queries and copy-pasting the grid container attributes and modifying them to match the screenshots.

## Bootstrap

### Cards

The most helpful resource for this exercise was the Bootstrap documentation. I looked for examples on the page that matched what I needed and followed their examples. There were some differences between my work and the example video so I made some small changes to match it. One example of this is getting rid of inline styles. I forgot that inline styling is usually frowned upon so I copied the video. I also keep forgetting which kind of button is preferred so I used the video example for that as well.

### Grid 1/2

This exercise was very easy to do because the lecture and slides cover everything needed. Unlike most exercises, there was no trial and error on my part. I got the layout correct on the first try because it is a relatively simple layout and Bootstrap has an easy-to-use 12 column system.

### Grid 2/2

This exercise was similar to the last grid exercise but it took a tiny bit longer. I still relied on the same Bootstrap documentation page as the last exercise but I needed to play around with the different column sizes and breakpoints to match the screenshots. It took me a couple extra minutes but I was able to recreate the layout with minimal trial and error.

### Modal

This exercise took the longest out of all the Bootstrap exercises because there were many elements of the modal dialog box that I needed to look up in the documentation. I was able to do most of it without the video but I forgot to add the little "X" to close the modal dialog bopx. My implementation was slightly different than the one shown in the video but the overall layout is the same.

## JavaScript

### Replace

I had to refer to the documentation to see how to format regular expressions. There is a table in the middle of the page that shows the different flags that can be used. I used the 'gi' flags to match all instances and make the search case-insensitive.

### Format

I was complete most of the function without looking anything up. I remembered arrow functions and the .join method being covered in class so I immediately used those. The only thing I did not remember was the map() method to apply a function to each element in an array.

### Objects

I originally tried to use the dot notation to insert and access keys in the object. After some reading through the documentation I realized that dot notation is for accessing static keys that are known beforehand. The key being passed into the functions is evaluated at runtime so I needed to use bracket notation. Apart from that minor hiccup, most of the exercise was simple to complete.

### DOM

I am completely new to JavaScript and there was a lot of material covered over mutliple lectures so I had to have my memory refreshed before doing this exercise. Watching the lecture and example video gave me a good start but I still needed to refer back to the example video when the input button wasn't doing what I wanted. It took me a while to notice that there was a small error in the video for the first part because an id selector was used instead of a class selector.

### Destructuring

This exercise tripped me up a little because I did not provide the full path for the mother and father attributes (I forgot the "allegiance" property before the "parents"). I also accidentally used single quotes instead of backticks so I was creating a string instead of a template literal. Other than that, I was able to complete this exercise without much trouble.

### Fetch

I closely followed the video for this exercise. There were many things that I had never used in practice before like the .then and .finally methods. I also forgot that I needed to append elements to the DOM after I created them. The process of creating and adding elements was tricky for me. This exercise took me the longest out of all the JavaScript exercises so far.

### Functional

I completed the map and filter functions with only the slides for reference. They were relatively intuitive to create. The third function took much longer as I tried to wrap my head around reducers and accumulators. I had to read the documentation and watch the example video to get an idea of what to do. The video showed the usage of the ternary operator. It has the same formatting as C ternary operators and I have used ternary operators in Python as well so it was a pleasant surprise to see them show up in JavaScript as well.
