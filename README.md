# AdminBoss

> A dashboard for all of your administration needs.

## [Live Demo on Netlify](https://adminboss.netlify.app/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/3a62c955-4da0-4f05-aaf0-c7a824096e9e/deploy-status)](https://app.netlify.com/sites/adminme/deploys)

<img src="https://github.com/alexisintech/adminme/blob/main/public/assets/dashboard.jpg" width="100%" />


### Global
- Light and dark mode for accessibility
- Collapsible side bar for increasing view width
- Search bar (non-functional)

### Dashboard
- Metrics, analytics, charts, and other data all viewable in one place (mock data was used)

### Data (Manage Team, Contacts Information, and Invoice Balances)
- 3 tables with sort-by functionality use Data Grid to display mock data

### Pages
- Profile Form built with Formik and validated with Yup (submitting the button will console log the form data)
- Calendar has a fully interactive and functional calendar with drag+schedule functionality built with FullCalendar (refreshing the page will lose any data entered)
- FAQ Page features Accordion elements provided by MUI components

### Charts (Bar, Pie, Line, Geography)
- 4 different chart types were customly modified using Nivo documentation

<!-- BUILT WITH -->

## 🛠️ Built With

- React.js, React Router, React Pro Sidebar
- Vite, Node.js
- MUI, MUI X Data Grid
- FullCalendar
- Formik, Yup
- Nivo
- HTML5/CSS3, Javascript ES6
- ESbuild, ESlint, Stylelint


## Customizations

- [X] Utilize Material UI for consistent, reusable components
- [X] Light/Dark mode for accessibility
- [ ] Mobile-first responsiveness

<!-- Lessons Learned -->

## Lessons Learned
This project was one of the best learning experiences I have had so far. Some of the things I learned:
- Tailwind Shades will take a color that you have (say you have a hex code) and it will create an array of shades for that color. In this project, Tailwind Shades was used to create the MUI theme of the application.
- Increased MUI skills
  - Explored how to create a custom theme globally to use throughout the app.
  - Learned how to pass a mode to the theme so that light and dark mode can be triggered (used the useContext hook for setting up the light/dark mode logic so that it can be accessed anywhere in the app)
  - useMediaQuery for writing styling logic in components
 - Data Grid provides easily customizable tables with a VAST amount of functionality
 - FullCalendar. The documentation is detailed and understandable.
 - Nivo charts - You can customize the charts right in the documentation and copy and paste the code into your project.
 - Formik + Yup : these tools were easier to use than React Hook.
