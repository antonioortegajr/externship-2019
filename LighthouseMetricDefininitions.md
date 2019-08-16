# Lighthouse Metric Definitions
## Performance
### 1. First Contentful Paint  
  - FCP reports the time when the browser first rendered any text, Image (including background images), non-white canvas or SVG. Excluding any content of iframes, but including text with pending webfont.  
  - **This is the first time users can start consuming content**  
  - Time starts immediately after loading Navigation  
  - [First Contentful Paint source documentation](https://w3c.github.io/paint-timing/#first-contentful-paint)
    
  ### 2. First Meaningful Paint  
  - **Primary metric for user-percieved loading experience**  
  - *meaningful* is a subjective definition  
  - First meaningful paint = Paint that follows the biggest layout change  
  - Layous when the page is longer than screen height are demoted.  layout significance = number of layout objects added / max(1, page height / screen height)  
  - Webfonts laid out with more than 200 characters may block first meaningful paint  
  - **Not** suitable for "layout stabilized" metric  
  - Page height heuristic makes this metric depend on screen size  
  - [First Meaningful Paint - A layout approach](https://docs.google.com/document/d/1BR94tJdZLsin5poeet0XoTW60M0SjvOJQttKT-JK8HI/view)
    
### 3. Speed index  
  - Useful for comparing experiences of pages against each other (before and after optimizing or My site vs a competetor site)   - **Not** a good indicator of end user expererience  
  - [Speed Index Source document](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)
### 4. First CPU Idle 
  - **All metrics for CPU Idle are subjective and still being debated**
  - The First CPU Idle metric measures when a page is minimally interactive  
    - Most but maybe not all UI elements are active
  - **First Interactive**  
    - The first moment when a website is minimally interactive: enough (but maybe not all) UI components shown on the screen are interactive, and the page responds to user input in a reasonable time on average
  - **Consistently Interactive**
    - The first moment when a website is completely and delightfully interactive - not only everything shown on the page is interactive, but the page strictly meets the I guideline of RAIL  
    - [First CPU Idle source document](https://docs.google.com/document/d/1GGiI9-7KeY3TPqS3YT271upUVimo-XiL5mwWorDUD4c/edit)
### 5. Estimated input Latency  
  - Input responsiveness is a key factor in how users perceive the performance of your app. Apps have 100ms to respond to user input. Any longer than that, and the user perceives the app as laggy  
  - Lighthouse uses a proxy metric to measure how well your app responds to user input: Lighthouse assumes that your app needs 50ms to completely respond to the user's input. If your main thread is unavailable for 50ms or more, that does not leave enough time for your app to complete the response.  
  - [Lighthouse Input Latency Source](https://developers.google.com/web/tools/lighthouse/audits/estimated-input-latency?utm_source=lighthouse&utm_medium=devtools)
## Accessibilty
### 1.  What is Accessibility
  - The site's content is available, and its functionality can be operated, by literally anyone  
  - POUR (Acrnym of what makes a website accessible)  
    - Perceivable: Can users perceive the content? This helps us keep in mind that just because something is perceivable with one sense, such as sight, that doesn't mean that all users can perceive it.
    - Operable: Can users use UI components and navigate the content? For example, something that requires a hover interaction cannot be operated by someone who can't use a mouse or touch screen.
    - Understandable: Can users understand the content? Can users understand the interface and is it consistent enough to avoid confusion?
    - Robust: Can the content be consumed by a wide variety of user agents (browsers)? Does it work with assistive technology?  
    - [Accessibility guidlines source](https://developers.google.com/web/fundamentals/accessibility/?utm_source=lighthouse&utm_medium=devtools)
## Best Practices  
  -Score is based on 15 known best practices for web development, as defined by google. These best practices focus on Speed, user experience, and security. 
## SEO  
  -SEO or Search Engine Optimization is the practice of optimizing your web pages to make them reach a high position in the search results of Google or other search engines. This allows your website to be more easily found in searches.  Many of the techniques used for SEO will also help accessibility of the site. 
## Progressive Web App
