# BroadBar
Broad Bar is a thin notification bar that appears at the top of a website. It is used to show announcements, blog posts, notices, events, news, or other regular updates. The content is dynamic and can be managed through an admin dashboard or API.

Sample 1 : <img width="666" height="61" alt="Screenshot 2025-09-25 at 10 28 59" src="https://github.com/user-attachments/assets/9261913f-8500-4347-b0ac-1d4584286d25" />

Sample 2 : <img width="1003" height="68" alt="Screenshot 2025-09-25 at 10 26 46" src="https://github.com/user-attachments/assets/53186d53-663b-444d-8acc-ec95fa44d69a" />

Broad Bar

This project provides a simple and reusable Broad Bar component that can be added to the top of any website. A Broad Bar is a thin notification bar that remains visible at the top of the page and is commonly used to share blog posts, highlight important announcements, display notices, promote events, show recent news, or communicate other updates to visitors. The component is built to be dynamic, meaning the content does not need to be hardcoded. Instead, it can be linked to an API or a content management system (CMS), making it easy for administrators to update without modifying code.


The Broad Bar works by fetching the latest content from an API endpoint that returns the most recent announcement or notice. Developers can create a simple endpoint in the backend or connect the component to a headless CMS such as Strapi, Sanity, or Directus. An admin dashboard can be used to manage the announcements, where administrators add or update entries. Once published, the Broad Bar automatically displays the latest item to visitors, keeping the content fresh and relevant. The bar can link directly to blog posts, news articles, or event pages, ensuring that users are quickly directed to more detailed information when they click on the message.

The component is lightweight and easy to customize. Developers can adjust its color, typography, and layout to match the website’s branding. It can be made sticky so it stays visible while users scroll, or it can be configured to appear only on specific pages. A dismiss or close button can also be included to allow users to hide the bar once they have seen the message. These options make the Broad Bar flexible enough to work for a wide range of use cases, from promotional campaigns to official notices.

Setting up the Broad Bar involves creating the component in the frontend and defining an API endpoint that serves announcement data. The frontend component will fetch the message and link from the endpoint and display it at the top of the website. For example, a JSON response might include a message such as “New Blog Post: How Digital Tools Are Transforming Agriculture” along with a link to the corresponding blog page. This approach separates content from presentation, making it easier to maintain. With the admin dashboard in place, non-technical users can manage announcements, and the Broad Bar will update automatically without requiring developer intervention.

The Broad Bar is suitable for any modern web project, including those built with React, Next.js, or other JavaScript frameworks. Developers can expand the functionality by adding support for multiple rotating messages, scheduling announcements with start and end dates, or tracking user clicks for analytics. By integrating this feature, websites can improve communication with users, highlight key updates, and keep visitors engaged with the most relevant information.
