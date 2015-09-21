# Husband-Aide

UPDATED for Swift 2.0

This is the appDelegate file for a first-time user flow; It checks if user has launched before via NSUserDefaults, if they have load desired viewController, if they haven't contact backend server that sends anonymous "authID" which is then saved in NSUserDefaults for future use, then subscribes user with that "authID", then sends user to desired first time viewController.  This was pieced together from numerous stackOverflow question and answers.

This is utilized by taking advantage of the 3rd party framework SwiftyJSON. Make sure to include this in your project.

https://github.com/SwiftyJSON/SwiftyJSON
