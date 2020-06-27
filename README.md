# AltHomeworkWk1
#Week One Homework Assignment:

#Refactor Code for efficiency, semantic logic and accessibility

##Consolidation of CSS Classes:
Removed <ul> and renamed to <nav>, as CSS attributes could apply to <a>. Consolidated .benefit-lead, .benefit-brand, .benefit-cost to .benefit-subsections as attribute values were identical.Consolidated corresponding img and h3 classes. Consolidated .search-engine-optimization, .online-reputation-management, .social-media-marketing to .content-subsections as attribute values were identical. Consolidated corresponding img and h2 classes. All class names were changed to corresponding elements in html. 

##Semantic Logic:
Added <header> tag around <h1> logo element, added <nav> tag within <header>; comments added to clearly identify elements. Added <main> tag around the .content class elements; comments added to clearly identify elements. Wrapped <article> around .content-subsections; comments added to clearly identify elements. Identified .content-subsections separately with <section> tags; comments added to clearly identify elements. Added <aside> tag to .benefits-subsections component; comments added to clearly identify elements. <Footer> tag added to footer area; comments added to clearly identify element.

##Accessibility:
Changed <title> to HoriSEOn-Marketing. SEO. Reputation Management.Added alt "S E O Plan Notepad" for "./assets/images/search-engine-optimization.jpg". Added alt "Reputation Management Laptop" for "./assets/images/online-reputation-management.jpg". Added alt "social media strategy meeting" for "./assets/images/social-media-marketing.jpg". Added alt "money machine" for "./assets/images/lead-generation.png". Added alt "branding ideas" for "./assets/images/brand-awareness.png". Added alt "cost efficient" for "./assets/images/cost-management.png"

##Discussion of "hero" img:
I decided to retain the background-image as a CSS element within a <div> for a couple of reasons. I was unable to replicate it while retaining some of its attributes as an <html> element, noteably it fading into the background under the <nav> elements when the viewport was reduced.In researching, more than one developer remarked that background images could remain background (no alt tags) if their function in the website is purely aesthetic, which this image appears to be. 

#References to developer discussion on alt tags and background images: 	
https://theme.co/forum/t/is-it-possible-to-add-an-alt-tag-to-a-background-image/48756/2
http://christianheilmann.com/2009/02/25/so-how-do-you-add-alternative-text-to-background-images/
https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html

#Personal remarks:
I really enjoyed this exercise. I have an itch for making things more efficient and this scratched it. I struggled with the background image piece described above for quite some time, but feel good about my decision after my research.
	 
	