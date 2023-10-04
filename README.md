# Stock-Management-System

The stock management system allows users to store, issue and receive items using a simple interface. The system includes reorder level alert which informs the users that the item is running low. The system also keeps track of all updates of the items.

Detailed features include:
## Login and logout 
A standard login and logout page that enables users to login using username and password.
![Screenshot 2023-10-04 144532](https://github.com/bhavanap12/stock-management-system/assets/23119773/a87b66a6-44be-4515-b08f-f5c4c0def31d)

## Home page 
Home page which has brief description of the system
![Screenshot 2023-10-04 144550](https://github.com/bhavanap12/stock-management-system/assets/23119773/9f2bcfe3-32f6-4c65-a87d-9d81e036f5da)

## List Items
A list of items page where the list is stored in a table and can be filtered using Category and Item name. The list can also be exported as a CSV file by checking the displayed box. This has the id, category, item name, quantity, reorder level, timestamp and delete button.
![Screenshot 2023-10-04 144642](https://github.com/bhavanap12/stock-management-system/assets/23119773/dd3acbcc-5334-499e-ac0c-45f5b8a285fd)

## Update Items
The quantity can be updated by clicking on the Item name in the List of Items table. The redirected page looks like this
![Screenshot 2023-10-04 144718](https://github.com/bhavanap12/stock-management-system/assets/23119773/38489ea0-9f78-41f4-8fbd-78a0543ac1d3)

## Issue/Receive Items
Items can be issued or recieved by clicking on the quantity in the List of Items table. The redirected page has Issue and Recieve button
![Screenshot 2023-10-04 144730](https://github.com/bhavanap12/stock-management-system/assets/23119773/bdb6772a-5369-4a76-b876-84c3c9c5525c)

Issue page has quantity to be issued and issue to fields which helps in tracking of the items
![Screenshot 2023-10-04 144800](https://github.com/bhavanap12/stock-management-system/assets/23119773/a7d210c4-5fb3-4ee7-86a5-1ef8c959ce78)

Recieve page gas quantity to be recieved and the logged in user is stored as the reciever directly.
![Screenshot 2023-10-04 144909](https://github.com/bhavanap12/stock-management-system/assets/23119773/99ad4f3f-ba9b-4f64-b4f3-cc2e288e6cea)

## Reorder level
Reorder level helps in giving alerts to the users that the item is running low and it has to be ordered. Different level can be set for different item.
![Screenshot 2023-10-04 144743](https://github.com/bhavanap12/stock-management-system/assets/23119773/af9f686b-c466-495d-b613-8bc07b13291c)

## Delete item
Items can be deleted from the table using the button. This redirects to confirmation page and user can select the choice appropriately.
![Screenshot 2023-10-04 144922](https://github.com/bhavanap12/stock-management-system/assets/23119773/5f82b168-435b-4649-8952-38cbab6a82e0)

## Add item
Items can be added by entering category, item name and quantity in the page.
![Screenshot 2023-10-04 144936](https://github.com/bhavanap12/stock-management-system/assets/23119773/e89ae918-2665-488b-992c-6a7c04b33e14)

## History of Items
The history of items issued, recieved are stored and displayed in a table. It has item details, timestamps and the user names. User can filter based on Category, item name and time stamp.
![Screenshot 2023-10-04 145201](https://github.com/bhavanap12/stock-management-system/assets/23119773/f0ddf040-a184-4655-9488-67c4cb07b49d)

## Message alerts
Alerts like 'Added item, Updated, Deleted item' are displayed appropriately based on the action.
![Screenshot 2023-10-04 152830](https://github.com/bhavanap12/stock-management-system/assets/23119773/7eef119d-e85c-44ec-901a-57a3dc3e8d23)


# Technologies and languages used:
  * Python
  * Django
  * MySQl
  * HTML
  * CSS
