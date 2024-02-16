# API Generator: A website where you can play with APIs

# Website:

<a href="https://api-generator-frontend.vercel.app/" target="_blank">Link</a>

# Screenshot:

<img width="1440" alt="Screenshot 2024-02-15 at 19 23 32" src="https://github.com/badri119/API-Generator/assets/90651004/c7d74d83-c016-40c5-bc9f-98fe6a46c58c">


# Technical Details:

- The Application was built using various tools including React, Redux, Express, ElephantSQL, TailwindCSS and SCSS
- Used OMDB API to fetch movies and shows
- Implemented redux for global state management for Entertainment Database
- Implemented useContext for global state management for Quote Generator
- Used Axios for API calls
- Quotes and HTTP data were obtained through a json file and parsed to PostgreSQL and then hosted via ElephantSQL
- Implemented Docker for containerizing ensuring consistent environments

# Key Features:

- Three Categories to choose from:
  - Quote Generator
  - HTTP Code Game
  - Entertainment Database using OMDB's API
- Mobile Responsive

# Future Improvements:

Upcoming features will include more API to play around with

# API endpoints:

| Endpoint | Method | Description        |
| -------- | ------ | ------------------ |
| /http    | GET    | Get all HTTP Codes |
| /quotes  | GET    | Get all quotes     |

# References

1. HTTP codes from: https://status.js.org/codes.json
2. Quotes data from: https://gist.github.com/nasrulhazim/54b659e43b1035215cd0ba1d4577ee80
3. Redux documentation: https://redux.js.org/
