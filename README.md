# FrontEnd-Task-TaiyoAi



## Deployed Link 
   https://taiyo-ai.netlify.app/

# Contact Management App with Charts and Maps

This is a contact management app built with ReactJS, TailwindCSS, React Router v6 and React Query.

## Objective

This app serves two primary purposes:

1. Contact Management: It allows users to efficiently manage their contacts by adding, viewing, editing, and deleting them. The app uses Redux to store the contact data, and React Query to handle API calls and data management.

2. Charts and Maps Dashboard: The app displays a dashboard that displays a line graph of the fluctuations in COVID-19 cases, providing an overview of the pandemic situation. The app also uses React Leaflet to display a map with markers that show the country name, along with its corresponding total number of active, recovered cases, and deaths. This dashboard provides users with a comprehensive visual representation of the COVID-19 situation around the world.

## APIs Used

The following APIs were used to fetch data for the dashboard:

- Country-specific data of cases (Used in Map): https://disease.sh/v3/covid-19/countries
- Graph data for cases with date (Used in Line Chart): https://disease.sh/v3/covid-19/historical/all?lastdays=all


## Run Project
### first clone the project 
git clone  https://github.com/Sharvil24600/FrontEnd-Task-TaiyoAi.git
### install packages
    npm install
### run project
    npm start
### for creating build
    npm run build
