# AUT Trade Calculator

This is a trade calculator for the game AUT (A Universal Time). It allows players to calculate the fairness of a trade between two players based on the items they want to exchange. The calculator takes into account the points assigned to each item and provides a trade fairness result.

## Usage

1. Open [https://aut-trading.github.io/](https://aut-trading.github.io/) in a web browser.
2. Select items from the drop-down menus under "Player 1 Items" and "Player 2 Items". These menus contain a list of available items for trade.
3. To add additional items for a player, click the "+ Add Item for Player 1" or "+ Add Item for Player 2" buttons.
4. Once you have selected all the items for the trade, click the "Calculate Trade" button.
5. The trade result will be displayed, showing the items selected for each player and the fairness of the trade.

## Styling

The calculator has a dark theme with a simple and intuitive layout. The main styles are defined in the embedded CSS section of the HTML file. The styles define the appearance of various elements such as the form, fieldsets, buttons, and result section.

## JavaScript Code

The calculator utilizes JavaScript to handle the trade calculation and result display. Here are the key functions:

- `getPlayerItems(containerId)`: Retrieves the selected items for a player from the specified container element.
- `calculateTotalPoints(items)`: Calculates the total points of the selected items for a player.
- `calculateTradeFairness(pointsPlayer1, pointsPlayer2)`: Determines the fairness of the trade based on the difference in points between the two players.
- `displayTradeResult(itemsPlayer1, itemsPlayer2, tradeFairness)`: Updates the trade result section with the selected items and fairness result.
- `addPlayerItems(containerId)`: Adds an additional item selection dropdown for a player.

The JavaScript code also includes an event listener that triggers the trade calculation when the form is submitted.

## External Resources

The HTML file includes a link to a Discord server at the bottom of the page. You can click on the "Join our Discord server" link to join the community and potentially get more information about trading in the game.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. You are free to share and adapt the code for non-commercial purposes, as long as you give appropriate credit, provide a link to the license, and indicate if changes were made. If you remix, transform, or build upon the code, you must distribute your contributions under the same license as the original.

For more information about the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license, visit the [Creative Commons website](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Feel free to use and modify this trade calculator to suit your needs. Happy trading!
