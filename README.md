# Web Development Project 5 - Astro Dashboard

Submitted by: **Miracle Adeoye**

This web app provides an interactive Marvel character dashboard, allowing users to explore characters from the Marvel universe. Users can filter characters by comic and series appearances and search for characters by name.

Time spent: **7** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **The list displays a list of data fetched using an API call**
- [x] **Data uses the useEffect React hook and async/await syntax**
- [x] **The app dashboard includes at least three summary statistics about the data such as**
  - [x] Total number of characters displayed
  - [x] Average number of comics appearances per character
  - [x] Median number of series appearances
- [x] **A search bar allows the user to search for an item in the fetched data**
- [x] **Multiple different filters (2+) allow the user to filter items in the database by specified categories**

The following **optional** features are implemented:

- [ ] Multiple filters can be applied simultaneously
- [ ] Filters use different input types such as a text input, a selection, or a slider
- [ ] The user can enter specific bounds for filter values

The following **additional** features are implemented:

* [ ] (Place any additional features you implemented here)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<!-- Replace link to your GIF file below -->
![Video Walkthrough](https://imgur.com/a/6f9cGLQ.gif)

GIF created with LiceCap

## Notes

During the development of the Astro Dashboard, several challenges were encountered:

- **API Rate Limiting**: Initially, the application made too many requests to the Marvel API in a short period, hitting the rate limit. This was mitigated by implementing caching strategies and optimizing the number of calls made during user interaction.
  
- **Handling API Keys**: Ensuring the security of the Marvel API keys was crucial. To address this, environment variables were used during development, and a backend proxy was set up to handle requests to the Marvel API, so the private key was never exposed to the frontend.
  
- **Responsive Design**: Creating a design that was both attractive and functional across various devices presented some difficulties. Through the use of media queries and flexible CSS units, a responsive layout was achieved that adapts to the screen size of the user's device.

- **Filter Complexity**: Implementing the multiple filters feature and ensuring they worked together seamlessly took some effort. This was accomplished by using React state effectively and updating the list of characters whenever the filter values changed.

These challenges were valuable learning experiences that enhanced my understanding of React's capabilities, API interaction, and modern web development practices.


## License

Copyright (c) 2024 Miracle Adeoye

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
