# Booki Project  
This project is about Integrating the model of a website.  

## Functional Specifications  
Users can search for accommodation in the city of
their choice. The search field is an input field, and the text
must therefore be able to be edited by the user. We must include this
field in a form so that the latter is valid with the
W3C. The research part should not be functional.
- Each accommodation or activity card must be clickable (not just the title). For now, the links are empty. You can use a `href=" #"` attribute to simulate the presence of a link.
- Filters should change appearance on hover. I leave it to you to decide on the appropriate effect. On the other hand, they should not be functional.
- The "Accommodations" and "Activities" texts, located in the header, are links. They must lead respectively to the section
"Accommodation in Marseille" and "Activities in Marseille".  

## Technical Specifications  
Two models were created: one desktop and the other mobile. the
site must also be adapted to tablet formats. For the
tablets, we are free to make the necessary adaptations. It
is important that no element is cut and that the text has sufficient size.
- Regarding breakpoints, we agreed with the UI designer
to use 992 px and 768 px.
992 px for computer screens and 768 px for tablets, and
anything below 768 for cellphones.
- You must first carry out the integration for the computers (otherwise
say, desktop first), then tablets and finally phones. Media Queries will allow us to realize integration for different media.
- Multiple image formats and sizes have been exported. You will have to choose
the most suitable format concerning the resolution and the loading time.
- Icons are from the Font Awesome library. We
We can go through a CDN to facilitate the loading of icons.
- Chart colors are blue (#0065FC), a lighter version
clear of this blue (#DEEBFF) and gray for the background (#F2F2F2).
- The site font is Raleway. We can go through Google Fonts
to easily import this font into the code:
https://fonts.google.com/specimen/Raleway.
- It is important to use pixels and percentages rather than
REM and EM.
- It is important to use Flexbox rather than Grid because it is techno
that the team masters best.
- No CSS framework (BootStrap or Tailwind CSS type) or
CSS preprocessor (Sass or Less type) should only be used.
- It is important to use semantic tags (type `main`,
`header`, `nav`, etc.).
- The code must be valid for W3C HTML and CSS validators.
- The model must be compatible with the latest versions of
Google Chrome and Mozilla Firefox. The prototype will have to be tested on these two browsers.
