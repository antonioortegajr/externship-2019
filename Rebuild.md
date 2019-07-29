# Rebuilding the Site
## Why Does it need rebuilt
There are several reasons the website should be refreshed.  As we make a larger and larger recruitment drives to bring our student body back to previous levels, our website does not tell the story of our school.  It does not visually communicate creativity, innovation, or inclusiveness.  There are blocks of text that do speak to our message, but a lot of it gets lost in other large blocks of text.  It is not currently the effective recruitment tool that it could be.   

It was also designed and built prior to smart phones being the primary device our students and families view the website on.  Our website does not meet current UI / UX design standards and as such, it is very difficult to use on a cell phone.  There are also significant technological issues that have been found using Google's Lighthouse web developer tools. Those are outlined below. The effect of the technological issues and the UI / UX design issues is that we have a website that is slow, doesn't meet accessibility standards, does not work well on smart phones, and the content is difficult to engage with. 

### lighthouse metrics
#### What do the metrics mean and what issues are there.  
1. Performance  
    First contentful Paint -- How long until the very first content that loads   
    Speed index -- How quickly content loads  
    First meaningful paint -- How long until the primary (expected) content loads    
    First CPU idle -- The first time the page is idle enough to accept input
    Issues: Inconsistent, and usually extremely long load times.  
    First contentful paint and first meaningful paint are 6 seconds or longer, these being the two most Important metrics.  Google recommends less than 2 seconds and no more than 3. This negatively affects the user experience, and the likelihood that visitors will stay on the site long enough to find the information they want.  
    2. Accessibility  
    How well can the site be accessed by everyone, including people with disabilities? What are the legal requirements for the school's website?  
    issues: Low contrast, no Alt tags on images, links do not have discernable names, form elements do not have associated labels.  
    These issues lead to assistive devices not being able to read our website. As we strive for inclusiveness in the school, this limits our ability to reach populations of disabled students. As a government funded organization, it may also be illegal for us to not meet accessibility standards.   
    3. Best Practices  
    These are the practices recommended by google for a site to have the best performance in many different areas.  
    Issues: Does not use https, Does not use http/2, Multiple security issues that need resolved.  
    These issues negatively affect how google will analyze the site and there are currently multiple areas that are vulnerable to an online attack.  
    4. SEO (Search Engine Optimization)  
   This is the method by which a website is found and made searchable by various search engines.  
   Document does not have meta discription, links do not have discriptive text.  
   Issues: Without meta descriptions, descriptive text, and alt tags, seach engines cannot find information in images or links.  This makes our website harder to find, in addition to also affecting our accessiblity. 


## The Website's Story
