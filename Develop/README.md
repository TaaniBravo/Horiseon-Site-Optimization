# Horiseon Social Solutions

**Version 1.1.0**

This repository is for the work of the company Horiseon. They are a social solutions company helping other companies reach out to people that may be interested in their product/apps/etc using search optimization and social media. This project was caused by Horiseon needing to update their codebase to follow accessibility standards. As well having their site being optimized for their own SEO.

I worked on the code of both html and css. The source code will be provide so that what was improved on and also reworked can be seen side by side with the original text. The original code was quite disorganized which you will see in the Changes Section

#Changes and Additions
HTML
    <ul>
        <li>All blocks were labeled nonsemantically as div so I gave them proper block labels.</li>
        <li>The title was left as document so that the SEO of the site was poor. Switched the title to "Horiseon Social Solutions" being the name of the company.</li>
        <li>Spacing of the code was a bit messy so I made sure that everything was nicely spaced when editing is needed.</li>
        <li>Images needed alt attributes for better Search Engine results. These were added to all images to help.</li>
        <li>Search Engine Optimization link was not working so that needed to fixed.</li>
        <li>Considering the articles in the code all had their own IDs already I didn't feel they need their own classes as well. These were removed. The CSS was updated to reflect the IDs rather than classes. I tried having them sit all in one class that I edit the basic effects but it made the page really wonky. This resulted me in switching the selector to the article block.
    </ul>
CSS
    <ul>
        <li>Add comments to all working code so that it is clear what is being done by each element.</li>
        <li>There was elements that were used multiple times so these were consolidated by the corresponding classes that matched with each other so that the CSS file could be shrunken down. </li>
        <li>Some of the classes were named after the element in CSS that was applied to them so I gave them more uniquely semantic names so in the future if they are changed they won't being improperly labeled.</li>
        <li>Flexboxes were add to the nav and most of the main blocks because of weird bugs that would occur when the page was shrunk down. This is technically a week 2 topic but felt it helped with the overall aesthetic of the page.
    </ul>

## Credits

All code for this project was edited by myself. Source was provided by Horiseon.
Basic knowledge of HTML semantics was learned at w3schools.com (schools.com/html/html5_semantic_elements.asp)

## License and Copyright

&copy; Taanileka Maama, UW Coding Bootcamp