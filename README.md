# Google Books UI

## MVP

1. Create a page that allows users to search for books.
2. Page should include the following:
    - Header section introducing the page
    - Form containing a text input and a submit / search button
    - A grid of books that are returned from the search

## Instructions

- When the submit button is clicked you need the request books from the Google books API using the input value as your query string parameter.
- The books that you receive should be rendered in the books grid.
- Each book in the grid should have an image, author, title and description of the book.
- The grid should be responsive on different screen sizes and devices.
- You should use async / await for your request code, NOT .then

## Styling (required)

- This application should look good, take some time to pick a palette and plan out your design. You can use tools like Figma or wireframe pro to plan what your application is going to look like.
- Styling must use BEM, and each block should have its own SCSS file for styling.
- Your palette should use variables for colors.

## Application Design (required)

- You should separate DOM functions and non-DOM functions in different modules Example: <https://github.com/chillcaw/el-salvador-code-alongs/tree/master/js-modules>
- Write as many non-DOM functions as you can
- Functions should do 1 thing, and should be as pure and reusable as possible (no side effects)
- Always use iterators over loops
- Always parametrize and abstract large pieces of duplicate code.

## Bonus (optional, but highly recommended)

- Give feedback to the user when no book results can be found for the query.
- When a user clicks a book in the grid, a modal should appear with more book information, think about release, publish date, country, languages, etc.

## Resources

- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [Using JavaScript Fetch API to get data](https://developers.google.com/books/docs/v1/reference/volumes/list)
- [Google Books Documentation](https://developers.google.com/books/docs/v1/reference/volumes/list)
- [Async / Await Requests Example |TODO|](https://github.com/nology-tech/curriculum-documentation/blob/main/js/projects/google-books)
- [Fetch documentation](https://www.w3schools.com/js/js_api_fetch.asp)
