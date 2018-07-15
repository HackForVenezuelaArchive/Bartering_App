# Bartering_App
Android 4.0 application to assist Venezuelans in trading goods and services

# Resources

Using Firebase as a database (back-end) and Android as a user interface (front-end), users will be able to post items that they can trade or want for a good or service. 

# Description of User Interaction

Users can post a request for goods and services. For example, a user may request a mechanic, and is willing to give scrap metal and medicine as payment. Another user may submit that they are willing to give mechanic services for items similar to scrap metal and/or medicine.

Both users, if their requests match, will be allowed to text each other, where they will be reminded to 
1. send photos with a timestamp as proof of their items, to prevent fraud
2. meet in a public location, to prevent robbery
3. set up a meeting time 
4. make adjustments to their requests (for example, if they only specificed they needed "medicine", they can then specify the medicine and amount they need)

After meeting and exchanging goods, users may be able to rate the person they exchanged items with. The ranking may affect how users are prioritized in the database, with lower-rated users being matched with users less often. 

# Possible Additions/Suggestions

 A third party may be present to make sure both parties have fairly exchanged goods

# TODO:

1. Add members to repository and give proper crediting
2. Post pictures of front-end UI
3. Create sample database using Firebase
   1. Users will have firstname/lastname, ID, rating, and optional password/request history
   2. Requests will have an item/multiple items needed, and an item/multiple items for offer, along with a userID and possible timestamp/request deadline
   3. Users may have some anonymized chatlog or phone number registered to their account 
