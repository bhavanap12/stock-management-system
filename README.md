# Stock-Management-System

The stock management system allows users to store, issue and receive items using a simple interface. The system includes reorder level alert which informs the users that the item is running low. The system also keeps track of all updates of the items.

Detailed features include:
## Login and logout 
A standard login and logout page that enables users to login using username and password.
![Screenshot 2023-10-04 144532](https://github.com/bhavanap12/stock-management-system/assets/23119773/33111b08-30ed-4834-b3ed-c696c77ff7d8)

## Home page 
Home page which has brief description of the system
![Screenshot 2023-10-04 144550](https://github.com/bhavanap12/stock-management-system/assets/23119773/f8e8a519-f8aa-42db-bc74-20e2d56a6bdc)

## List Items
A list of items page where the list is stored in a table and can be filtered using Category and Item name. The list can also be exported as a CSV file by checking the displayed box. This has the id, category, item name, quantity, reorder level, timestamp and delete button.
![Screenshot 2023-10-04 144642](https://github.com/bhavanap12/stock-management-system/assets/23119773/dd3acbcc-5334-499e-ac0c-45f5b8a285fd)

## Update Items
The quantity can be updated by clicking on the Item name in the List of Items table. The redirected page looks like this
![Screenshot 2023-10-04 144718](https://github.com/bhavanap12/stock-management-system/assets/23119773/ce2ebf44-4595-464f-8f56-e59cc96f0ad3)

## Issue/Receive Items
Items can be issued or recieved by clicking on the quantity in the List of Items table. The redirected page has Issue and Recieve button
![Screenshot 2023-10-04 144730](https://github.com/bhavanap12/stock-management-system/assets/23119773/d3d15ab4-c192-4b2f-94dd-e2037ca68a28)

Issue page has quantity to be issued and issue to fields which helps in tracking of the items
![Screenshot 2023-10-04 144800](https://github.com/bhavanap12/stock-management-system/assets/23119773/b66701c4-9162-476a-9d7f-5a14c91e4893)

Recieve page gas quantity to be recieved and the logged in user is stored as the reciever directly.
![Screenshot 2023-10-04 144909](https://github.com/bhavanap12/stock-management-system/assets/23119773/9d3d8d29-7565-42c1-a6c2-8230fcb73a38)

## Reorder level
Reorder level helps in giving alerts to the users that the item is running low and it has to be ordered. Different level can be set for different item.
![Screenshot 2023-10-04 144743](https://github.com/bhavanap12/stock-management-system/assets/23119773/55198578-2282-4cc9-bf39-3c6d31fd03be)

## Delete item
Items can be deleted from the table using the button. This redirects to confirmation page and user can select the choice appropriately.
![Screenshot 2023-10-04 144922](https://github.com/bhavanap12/stock-management-system/assets/23119773/5d91b2cc-248a-46fe-98e7-c7702411d3c3)

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
