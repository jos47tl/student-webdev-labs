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
