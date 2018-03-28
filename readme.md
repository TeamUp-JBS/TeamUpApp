TeamUp (Social Networking Application):

TeamUp is an academic oriented social networking webiste which allows user to add, message, and create private groups with other users. Primarily, it is meant to serve as a platform to learn about different careers and academic subjects, as well as enable one to connect with users whose professions correlate with their interests. All user accounts come with a profile, where users enter their information. Once users add friends (connections), they are able to view those user's accounts, and vice versa. Private messaging is possible only among friends, and the same goes for a private group forum creation. Voice is integrated in the personal calendar, where users can dictates events they should save for future refrence (groups all have a shared calandar). The framworks that were used in creating the project were:

- JavaScript
- HTML
- CSS
- MongoDB
- NodeJS
- Github

If given more time, we would work on improving the overall aesthetic of our website instead of using stock images. Also, integrate the ability to accept/reject friend requests. Also, a news feed would be beneficial to have as it is a key componenet of all successfuly social networking sites. Adding different types of profile setup (students, teachers, employeers, etc) should be included as not every user will require certain fields.

    - Joshua Alvarado

Instructions for Voice Setup:

    To run our app in your computer, you need to install the following packages and account:

    1. Install all the required NPM packages:
        Meteor npm install --save

    2. Set up Google Speech API - https://cloud.google.com/speech/

    3 . Install Google Cloud SDK - https://cloud.google.com/sdk/docs/

    4. Open the SDK and execute the following command:
        gcloud auth application-default login

    5. Then run:
	Meteor --settings settings.json
