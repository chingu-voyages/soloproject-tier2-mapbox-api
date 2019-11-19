# Chingu Voyage Pre-work Project (Tier 2): Mapbox API

![Tier2 Mapbox API](./assets/Tier2_mapbox_api.gif)

## Overview
This project helps you gain experience in using API's to enhance the value
your applications provide to their users. Your objective with this project is 
to build a web application using the Mapbox API to build a map of a city of 
your choice.

## Instructions

General instructions for all Solo Projects are located in the 
[Chingu Library](https://voyage.docs.chingu.io/prework/howwork). For detailed 
requirements checkout the following requirements.

### Requirements

*Structure*
- [ ] Read over the Mapbox API documentation

      Things to look for in the [Mapbox API](https://docs.mapbox.com/api/) documentation:
      - [ ] API endpoint
      - [ ] Setting up an API token
      - [ ] Setting up a request aka limits to the returned result, etc
      - [ ] How to query only for the exact info you need.

- Setup your parent component containing at least the following:
  - [ ] Navigation (or a button to toggle the sidebar)
  - [ ] Sidebar
  - [ ] Map
- Create a sidebar with the following elements:
  - [ ] Search input field
  - [ ] A list of search results (should match the markers on the map)
  - [ ] A button to toggle the display/hide of the sidebar
- Create a map component to contain the map of your city and location markers

*Style*
- [ ] You may use any style you choose. However, it should be consistent (e.g.
font, font size, color scheme, layout, etc.).

*Functionality*
- Sidebar behaviors:
  - [ ] By default all all available markers should be displayed
  - [ ] Markers update in search results and on the map while the user is 
  typing intp the search input field
  - [ ] User should be able to click a button to toggle the sidebar visibility
- The map component displays:
  - [ ] The map of your city using the Mapbox API
  - [ ] At least five markers for five unique locations or attractions in your city

*Other*
- [ ] Your repo needs to have a robust `README.md`
- [ ] Make sure that there are no errors in the developer console before submitting
- [ ] Anticipate and handle any edge cases
  - [ ] Does entering random data, such as a mix of alphbetic, numeric, and
  special characters in the search input result in an error?
  - [ ] What is displayed if the search location is not found?
- [ ] The app should be responsive across multiple devices (e.g. phone, tablet, 
laptop, and desktop computers)

**Extras (Not Required)**

- [ ] Use as FEW external packages and libraries as possible to reduce the 
number of dependencies.
- [ ] Include tests cases using tools like Jest, Enzyme, etc.
- [ ] Use Accessibility techniques (i.e. a11ly) to improve your site for users 
with impairments 
- [ ] Add a `CONTRIBUTING.md` file with instructions on how to contribute to
your project
- [ ] Implement service workers to improve performance by relying on cached data
