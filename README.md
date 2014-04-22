firebase-login
==============

Authenticate your Firebase reference using your Firebase account credentials.

*Note: This library is not related to Firebase's Simple Login email/password authentication. It allows you to log in with your Firebase account credentials, not a user's Simple Login email/password account.*


Example
-------
    var ref = new Firebase('https://<Your Firebase>.firebaseio.com');

    FirebaseLogin(ref, {
            email: "<Your Email>", 
            password: "<Your Password>"
        }, 
        function (error, data) {
            console.log(arguments);
        }
    );