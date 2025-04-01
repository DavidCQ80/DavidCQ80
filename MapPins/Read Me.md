To setup create a character called Pins assign your desired image to it, create an ability/macro called details with !showMapPin as the command. 

Next drag it out onto the gm layer this will create an invisible token on the token layer that can move the pin from the token layer. 

Now you just need to enter the details of your pin in the Gmnotes on the pin token be sure not to delete the token id stored there as this links the tokens. 

Moving back to the token layer click where the pin is located and move it to your desired location. 

Run the details token action and it will create a handout called Map Pins in the journal and the details stored on the pin token from the gm layer will populate in it.

		To create and populate Map Pins handout !showMapPin
		To delete a map pin !deleteMapPin
	        To lock the mirrored pin run !lockMapPins
		To add an image to the handout place this in the gm layer token "![Description](url)"
