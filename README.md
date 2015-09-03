# Husband-Aide

This is the appDelegate file that is a first time user flow; It checks if user has launched before via NSUserDefaults, if they have load desired viewController, if they haven't contact backend server that sends anonymous "authID" which is then saved in NSUserDefaults for future use, then subscribes user with that "authID", then sends user to desired first time viewController.  This was pieced together from numerous stackOverflow question and answers.
