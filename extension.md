# Extension:

 ## Send to any individual on the whole UW campus
To send to any individual on the whole UW Campus, Alice must provide additional information about Bob on the left-hand side of the back of the notecard. Alice must provide information such as Bob’s name, Bob’s year at UW, office or home address, classes, department, major, place of work, and clubs or activities that Bob participates in. Alice does not need to provide information that is not applicable to Bob or that Alice does not know. Nodes can use this information to help find the best path to Bob. If a Node has anything in common with Bob such as a shared club or class then that node can bring the card to Bob as they go to class. The Node may not themselves have a shared aspect with Bob but if they know someone who does or know how to get to a location such as Bob’s office then the node will know where to deliver the card next. If a node has nothing in common, it will hand the card to an arbitrary node that is nearby.

## Specify whether contents are ASCII text, Unicode text, or binary values
To specify whether contents are ASCII text, Unicode text, or binary values each encoding type will be assigned a value. In this case:

	Binary values -> 0

	Unicode text -> 1

	ASCII text -> 2

This value will be in the bottom left corner of the notecard. The reason we use numbers instead of letters in this case is to not limit the amount of future encoding types that may be invented and wanted to be used. Say if we used the first letter for the encoding type. A new encoding type that started with the same letter wouldn’t be able to be used. We would also only be able to use 26 unique encoding types. By using numbers instead, we aren’t limited by encoding types and the message can still be interpreted properly.

## Keep a record of what nodes the card has passed through

As a way to uniquely identify which nodes the card has passed through. Nodes are expected to write their complete UWNetID on the right-hand side of the back of the card. They are also expected to write a number corresponding to when they received the card before their UWNetID with a colon. For example, the first node would write 1:\<UWNetID> and whichever node the first node hands the card to would write 2:\<UWNetID>. Each time incrementing this number by one so that Bob can retrace the path the card took along the nodes. Nodes are encouraged to write as small as they can while still being readable to allow for enough space for all the UWNetIDs.
