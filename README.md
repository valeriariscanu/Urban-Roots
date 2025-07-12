Introduction

Building the Urban Roots platform as an html/css application without any backend integration allowed for a narrow-scope look at the front-end implementation and design of a web-app using the given strategic plan. This translation of the platform design into code was focused on the visual and organizational components without any dynamic functionality.

1.	Direct Visual Translation of Design Plan: The application demonstrates a direct and successful translation of the aesthetic and structural elements as outlined in the "Urban Roots" strategic plan. The utilisation of a green-centric colour palette, rounded corners, and clear sectioning (Home, Community, Groups, Marketplace, Events) directly reflects the intended user interface and branding. The inclusion of placeholder content, specifically crafted to resonate with the "Chloe, the Balcony Botanist" and "David, the Allotment Veteran" personas, effectively demonstrates how the platform would visually support a "two-sided knowledge market." For example, a "balcony botanist" query on the community feed and an "allotment veteran" offering surplus produce in the marketplace illustrate the diverse interactions envisioned.

2.	Robust Responsive Design: The use of Tailwind CSS has proven highly effective in establishing a fully responsive layout. The application adapts seamlessly across various screen sizes, from mobile phones to larger desktop displays. This mobile-first approach is critical for "Urban Roots," as urban gardeners are likely to access the platform on diverse devices while tending to their plants or on the go. The fluid grid system and responsive utility classes ensure that content remains legible and well-organised, preventing horizontal scrolling and maintaining a positive user experience regardless of the viewport.

3.	Clean and Maintainable Codebase: Focusing solely on HTML and CSS has resulted in a codebase that is clean, lightweight, and highly maintainable from a front-end perspective. There are no complex JavaScript frameworks or backend dependencies to manage, making it easy to understand and modify the visual presentation. This simplicity allows for rapid iteration on the design aspects and ensures fast loading times, contributing to a positive initial user impression.

4.	Ease of Deployment with Static Hosting: A significant advantage demonstrated by this implementation is the straightforward deployment process. The application, being purely static HTML and CSS, has been successfully added to a GitHub repository and deployed live using GitHub Pages. This highlights the cost-effectiveness and accessibility of deploying simple web solutions, aligning with the strategic plan's consideration of low-cost validation for an MVP. The ability to quickly get the site live on a widely accessible platform like GitHub Pages is a practical benefit for early-stage projects


Limitations and Areas for Improvement (in a real-world context)

1.	Absence of Dynamic Functionality: The primary and most obvious constraint is that this application is a static representation of what an urban community platform could look like. Although this prototype includes the visual elements/forms and interactive components (such as “Post”, “Join Group”, “RSVP” buttons), they lack any underlying logic to actually function. The key value proposition of “Urban Roots” – a “fully functioning, dynamic online/mobile platform or service” for urban communities to connect and generate user content is not actualised beyond static page elements and visual graphics. It is crucial to note the absence of dynamic features like user authentication (registration/login), content submission/retrieval (posts, groups, listings, events), and real-time updates/synchronisation across the platform. The static site fails to offer a true two-sided marketplace for user interactions and content generation.

2.	No Backend Integration or Data Persistence: Since there is no backend or data storage mechanism, the application currently lacks any data persistence. It means that even if a user “submits” some content via the available forms, there is no functionality to store this data. A page refresh would result in the immediate disappearance of this information. This is a critical roadblock to realising a community platform like “Urban Roots”, where the persistence of user profiles, content submissions (posts, groups, listings, events), and other related information is a must. Furthermore, it stands in direct conflict with the strategic plan’s vision of empowering users to generate and curate content and creating a two-sided knowledge market.

3.	Scalability and Content Management Challenges: As a static HTML/CSS prototype, the site is not equipped to manage, let alone scale, user-generated content. Every new post, group, listing, or event would have to be manually added to the HTML file – an untenable solution for any growing community platform. The strategic plan’s recommendation of using WordPress (or a custom-built platform) coupled with plugins like BuddyPress and Rank Math envisions the need for a Content Management System (CMS) and underlying dynamic functionality for SEO and content management.













Conclusion
The created HTML/CSS app, so far, appears to nicely accomplish the visual look and layout goals of the "Urban Roots" platform, at least for a static app, and is in line with the discussed strategic plan. It is a good representation of what is needed in front-end presentation design, and it seems to generally do well for a responsive web design solution (obviously without the functionality part). The part about using GitHub Pages is also interesting, as it really drives home the point of a good, static web hosting service for simple web apps, as well as how quickly and easily a web presence can be put online. Obviously it is not a "fully functioning, dynamic" service and, at the same time, it also serves to illustrate the point that HTML and CSS alone (i.e. a "look and feel" front-end) is only half of the equation, and what is required for a fully interactive and data-driven community platform, as discussed in the original strategic plan, are more advanced/involved solutions (likely involving JavaScript and a more complete backend) to get it to the more involved functionality described there.
