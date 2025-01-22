1. Overall Structure
I designed my portfolio to be clean, organized, and user-friendly. Each section (Home, About Me, Projects, Gallery, Contact) has its own page to keep the content structured and easy to navigate. The navigation bar is consistent across all pages, providing users with a seamless browsing experience.

2. Styling
Color Scheme: I used a simple color palette to maintain a professional look, ensuring text and background contrast for readability.
Typography: I selected clear, sans-serif fonts for readability and modern aesthetics.
Images: Images are displayed prominently, especially in the Gallery section, where they are the focal point. Hover effects were added to enhance interactivity.

3. Interactivity
Smooth scrolling was implemented for a polished navigation experience.
A CSS-only lightbox was used to display images in the Gallery section.
Buttons and links have hover effects for visual feedback.

Challenges Faced
1. Responsiveness
One of the main challenges was ensuring the site looked good on all screen sizes (mobile, tablet, and desktop). Elements like tables and images required special attention to avoid overflow issues on smaller screens.
Solution:
Used CSS media queries to adjust layouts for different screen sizes.
Converted tables to stacked blocks on smaller screens for better readability.
Ensured images were responsive using max-width: 100% and height: auto.

2. Navigation
Keeping the navigation bar responsive and functional was another challenge, especially for smaller screens.
Solution:
Used a simple CSS approach to stack navigation links vertically on smaller screens using flex-direction: column in media queries.


Approach to Responsiveness
1. Mobile-First Design
I started by designing for small screens and gradually added styles for larger devices using media queries. This approach ensured the site worked well on mobile devices, which are often the most challenging.


Lessons Learned
1. Planning Is Key
Taking time to plan the structure and design saved me from major changes later. Sketching out layouts helped me visualize how elements would adapt to different screen sizes.

2. Testing Responsiveness
Testing the site frequently at different screen sizes while working helped catch issues early.

3. CSS Power
This project demonstrated how much can be achieved with CSS alone. CSS pseudo-classes and animations can handle many tasks effectively.