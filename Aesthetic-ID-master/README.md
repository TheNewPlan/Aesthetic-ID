# Aesthetic-ID

# What?
Aesthetic ID is a project that utilizes the Microsoft Cognitive Emotion API to help detect emotions of an image a user submits (which at this point is still only a static url, there was not enough time to implement a ).  This will also provide the user with sensory details of the aesthetic of vaporwave as well as provide various text and music selection for the user.

# Who wrote Aesthetic-ID?
It is authored by Matt Hallowell and Craig Bruenger, who both collaberated to bring Aesthetic-ID to life.

# When?
Between January 14-15 at Uncommon Hacks @ Chicago, Illinois.

# Why?
A e s t h e t i c s, as well as the challenge of learning a foreign artificial intelligence API and implementing it into a web interface.

# What were your challenges?
Working with the Microsoft API was a challenge to implement using Javascript, and we were able to overcome this issue after dilligently searching through the code and by asking others for input.

In addition, working with forms and attempting to parse urls in a manner cleanly to access in a new window ran into it's own issue we ran into after working to implement the API and Javascript.  We unfortunately did not have enough time within the 24hrs to reach this strech goal.

Lastly, we learned that the Microsoft API access code refreshes every 24hrs, which unfortunately would need to be updated in the reposity approximately every day at 12:37pm.  

# What Languages does Aesthetic-ID currently implement?
HTML, CSS3, JavaScript, jQuery(API Request)

# How do you operate Aesthetic-ID?
As of the latest commit, this will only function locally, which will require your own Microsoft Ocp Key from Microsoft.  We also recently discovered that this key changes every 24hrs, which will require a new key to be replaced.  In addition, you will need to change the url within the data attribute to send the photo through the cognitive API to detect the emotion.

# What is the future for Aesthetic-ID?
Make the input box functional (temporarily disabled, submission).
Display the user submitted image and the Emotion Detection software output on a new and styled .html page.
Cleanup the dirty/redundent website framework/styling.
Finalize styling of the webpage.
Create a method to help the user reset their input and run the calcuation again.
Find a cleaner backend solution for the Javascript/jQuery.
Clean and organize the file hierchy, move resources to a resource folder.
Deploy the web application online rather than strictly locally.
Implement our dynamic styling/sound packages for all visible emotions in the submitted photo.
Ａｄｄ　ｍｏｒｅ　ａｅｓｔｈｅｔｉｃ
