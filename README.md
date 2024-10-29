# JavaScript Menu Filtering Project

This project is a JavaScript-based application that dynamically displays a list of menu items with category filter buttons. Users can filter menu items by category, allowing for a seamless and interactive browsing experience.


## Features
- **Dynamic Menu Display**: Loads and displays all menu items by default when the page loads.
- **Filter by Category**: Users can filter menu items by selecting category buttons.
- **Responsive Design**: The app is optimized for desktop and mobile devices.

## Technologies Used
- **HTML**: For structuring the page and content.
- **CSS**: For styling the elements and creating a visually appealing design.
- **JavaScript**: For dynamically rendering the menu items and implementing filtering functionality.

## Code Explanation
The JavaScript code uses:

- **DOMContentLoaded** event to initialize menu display on page load.
- **map()** to convert menu items to HTML format.
- **reduce()** to extract unique categories for button - creation.
- **filter()** to display items based on selected category.

## Key Functions
- **diplayMenuItems(menuItems)**: Renders a list of menu items.
- **displayMenuButtons()**: Creates and displays category buttons for filtering.
