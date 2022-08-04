# PixarUpload
A nice javascript/React program with characters and movies from Pixar. the purchase area is not functional due to not actual ecommerce site


# Discord SillyNFTier#5653 J.Cramer

in file server\config\config.js:

typically mongodb Atlas Database 'Pixar1' is populated with 6 collections - carts,characters,movies,orders,tokenblacklists,users

you can populate characters with server\config\databaseCharactersInfo.json
you can populate movies with server\config\databaseMovieInformation.json

there is a sample user at server\config\databaseUsersInfo.json
the other collections get populated depending on actions.

in file server\config\config.example.js rename file to server\config\config.js
then ....
change '<username>' to your mongodb username ie "Johnny" (no quotations) before the : then change '<password>' to your collection password
dbURL: "mongodb+srv://<username>:<password>Test123@cluster1.nymha.mongodb.net/<collection>",

This file runs from Root directory /pixarDirectory using "npm start"
it runs client side and server side concurrently

