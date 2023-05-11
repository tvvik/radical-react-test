## Test: Lazy Loading with React Suspense

For this task, you will demonstrate your understanding and implementation of lazy loading images using React Suspense. Your goal is to build a simple image gallery application that fetches a list of image URLs from an API endpoint and displays them in a gallery grid. The images should be lazily loaded, meaning they should only be loaded on-demand when they come into view.

Here's a step-by-step breakdown of the task:

1. **API Integration and Data Fetching:**
- Start by fetching a list of image URLs from an API endpoint. You can use the public image API like Pixabay, and API key will be provided.
- Utilize modern JavaScript techniques such as the Fetch API or Axios to make the API request and retrieve the image URLs.
2. **Gallery Grid Component:**
- Create a React component called GalleryGrid that will be responsible for rendering the image gallery.
- The GalleryGrid component should receive the list of image URLs as a prop.
3. **Lazy Loading Implementation:**
- Implement lazy loading functionality to load images on-demand as they come into view.
- Utilize React Suspense to achieve lazy loading. Use the Suspense and lazy components from React to wrap the image loading logic.
- Render each image as a separate component wrapped with the Suspense component, allowing it to be lazily loaded.
4. **Loading State and Placeholder:**
- Implement a loading state to display a placeholder or loading animation while the images are being loaded.
- Conditionally render a loading state component until the image is fully loaded.
5. **Gallery Layout:**
- Render the images in a visually pleasing gallery layout using CSS Grid or any other preferred layout technique.
- Display a fixed number of images per row to maintain a responsive and visually appealing design.
6. **Testing and Error Handling:**
- Ensure that the lazy loading behavior works as expected, i.e., the images load on-demand as they come into view.
- Implement error handling to handle any errors that may occur during the image loading process. Display appropriate error messages or fallback content.

Evaluation criteria for this task can include the following:
- Overall code quality, including readability, organization, and adherence to best practices.
- Proper implementation of React Suspense for lazy loading images. 
- Correct integration with the API to fetch the image URLs.
- Ability to render the gallery grid and display images in a visually appealing layout.
- Proper handling of loading states, including the use of placeholders or loading animations.
- Error handling and displaying appropriate error messages.

### Prerequisites

- Node.js (v14 or above)
- npm (v6 or above)
