# Anti-dup:
 ## Problem
 How can we ensure that each card is received once and only once?
 ## Solution
To make sure Bob always receives a card Alice will send out another card if Bob requests the message as missing or if the card's time to live has expired. If Alice receives this request she will send out another card to Bob and this process will continue until he receives it. To ensure that each card is received only once Bob will notify Alice when he has received a card in order to prevent further duplicates. In addition to this Bob will check all cards that have the same card number and only accept cards that don’t contain duplicate numbers. The card number is already included in the specification in the top left corner with the card number being above the message length.

 
To notify each other about status such as Bob missing or receiving a card, he will use the admin commands directed at Alice so she can properly interpret his request.
