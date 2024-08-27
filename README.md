# Chatterly-Card
Blog Post Card
This card was created using React Js.
![Screenshot 2024-08-27 122116](https://github.com/user-attachments/assets/5bb20642-b3d9-4669-bd3c-0f3d69a8043e)
![Screenshot 2024-08-27 122202](https://github.com/user-attachments/assets/7110525b-d8bd-4b71-b970-8de2350dbbfc)
![Screenshot 2024-08-27 122133](https://github.com/user-attachments/assets/5b54cbfd-34b5-47ae-b20b-f987576f73e8)
This code defines a React functional component called CardsTab. Here's a summary of what it does:

1. Imports: It imports several components (Header, Card, Title, and Footer) from the Chatterly directory.
   
3. Images and Profile Logos: The component defines constants for images and profile logos, which are paths to different assets (images) used within the cards.

4. CardsTab Component:

* Renders a layout consisting of a Header, Title, a container with multiple Card components, and a Footer.

* Each Card component is passed props such as title, date, author, image, profile image (img),
the number of likes, and comments.

* There are 9 cards in total, each representing a different topic (like "Nature Photography", "Artificial Intelligence", etc.).

4. Export: Finally, the CardsTab component is exported for use in other parts of the application.

## This component likely serves as a tab or section in a larger application, displaying a series of cards with different content.

# Imports and Disables ESLint Rule:

* The react/prop-types ESLint rule is disabled, meaning the component does not enforce prop types validation.
* The component imports styles from a Card.css file.

5. Component Props:

* The Card component takes the following props:
* title: The title of the card.
* image: The main background image of the card.
* date: The date associated with the card.
* author: The author of the card.
* img: The profile image of the author.
* like: The number of likes.
* comment: The number of comments.

6. Styling:

  * The component defines an inline style object called style, which is used to style the color and margin of the text displaying the number of likes and comments.

7. Component Structure:

*   The component renders a div with the class container, containing another div with the class shop-item.
* Inside shop-item, there are two main sections:
* box-img: Displays the main background image using the image prop.
* box-content: Contains the card’s text content, including the title, author details, date, and icons for likes and comments.

8. Icons:

* Font Awesome icons (fa-heart for likes and fa-comment-dots for comments) are used to visually represent the number of likes and comments.

9. Export:

* The Card component is exported for use in other parts of the application.

