# LearningBox

## Summary
This is an educational application called LearningBox. This application uses a unique card-based system to facilitate and optimize the learning process. Here are the key features you’ll be developing:

Card System: Each card in the system will contain a question, an answer, a period (default value is one day and is not editable by the user), and a schedule indicating when the card should be replayed.

**Management Feature**: This feature allows users to add new cards to the system, list all existing cards, delete any card or all cards from the list, and select any card from the list for editing and saving changes.

**Practice Feature**: This feature randomly selects an overdue card and displays its question with a button to reveal the answer. It also includes two buttons labeled ‘correct’ and ‘incorrect’ for users to report their performance. If the ‘correct’ button is clicked, the period of the card is doubled and the schedule date is recalculated (current date + period). If the ‘incorrect’ button is clicked, the period of the card is halved and the schedule date is recalculated (current date + period). There should also be a button to display the next random overdue card.

**Metrics Feature**: This feature provides users with statistics related to their cards.

## business rules
The default card period is one day. The minimum card period is one day

## Non functional requirements
The service will be a javascript webapp.
The data is stored in the web brsower

