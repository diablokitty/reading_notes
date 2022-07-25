# Reading notes for day 11 of 201

### Reading Video and Audio Content

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.

We have the bandwidth, computing power and memory now that we didn't have back then. Plus we needed plug-ins because HTML had no way to handle video. Oh and there were security issues with the plug-ins.

- Describe the use of the src and controls attributes in the <video> element.

src for video is the same as it is for images, it points the browser to where the actual asset is stored. the control command allows the browser to assign the client computers native controls to the playback functions of the video.

- Why is it important to have fallback content inside the <video> element?

Because sometimes older browsers don't support the video function in HTML5. Using fallback content allows users an alternative way to access the video.

- Write a very short story where <audio> and <video> are characters.

"I'm using all the bandwidth," <audio> said with a cheeky grin.
"Doesn' matter, I'm moving to YouTube anyway." <video> gave a cheery wave. "Enjoy all your performance issues!" And left an empty codec for <audio> to trip over.

### Read A Complete Guide To Grid

- How does Grid layout differ from Flex?

Grid is two dimensional, Flexbox is one dimensional. You can use them together.

- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please  describe these terms in a few sentences.

Grid container is the parent on which the grid property is applied. Like how flex is applied to the parent of the items you are manipulating.

Grid item is one on of the items in the grid container.

Grid lines are the lines that make up the structure of the grid. 


### Responsive Images

- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Because it aids in accessibility.


- Define the following <img> attributes srcset and sizes. Write an example of how they are used.

srcset defines the set of images we will allow the browser to choose between, and what size each image is.
sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose under each condition.

- How is srcset more helpful for responsive images than CSS or JavaScript?

CSS and Javascript load later than native HTML. Controlling how images are presented with the native HTML preserves resources and keeps the page looking a bit better from the first render.

### Bookmark and Review Images in HTML (This article is review from Class 05.), Other Embedding Technologies

## Things I want to know more about

I really want to know how line animations that move around a page work. I totally want to but a random crawly thing Easter Egg on every site I build. 

[back to Table of Contents](./README.md)