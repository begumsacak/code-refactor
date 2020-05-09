# homework-1
**Homework 1 Code Refractor**

Homework 1 Code Refractor

**List of Changes**

1. The title in HTML was changed to Horiseon Website instead of using the word website. 
2. In order to use the semantic HTML elements in this website, some div tags were replaced with semantic elements. Div elements were replaced with semantic elements such as navigation, figure, main, section, aside, and footer.
3. Alternative text was added to images. Since the images in this website are decorative images, I inserted null alternative text tags after referring to [Web Accessibility Tutorials Website] (https://www.w3.org/WAI/tutorials/images/decorative/). 
4. In the main content, some elements such as online reputation management section and social media marketing section, had both a class and id. I used classes only. I also removed the additional classes in HTML (float-left and right for these images and used search engine optimization img class instead (in CSS). I also grouped social media marketing image and search engine optimization image together in CSS since they use the same formatting. 
5. The links at the top of the page were fixed. 
6. h2 tag in the footer was changed to h4. I am not sure about this change, but thematically, the footer should have a smaller header than the side bar headers. 

**In CSSs**
1. I grouped together the CSS classes which have the same properties. 
2. seo, which is a part of the company's name, is a unique element on its own. I deleted the header h1 part that came before the word seo and defined seo as an id in CSS and HTML. I did the same with hero image (and changed its name to cover image).

**Note:** I could have combined different classes which have same properties and rename that (for instance if there are three classes with identical properties, I could have named them all the same and list the properties in CSS in that way). But I didn't do that since that would be a dramatic change to the overall coding convention, and I am not sure if making such major changes are fine. I am curious to learn more about that. 
