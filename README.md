# Movie App TMDB

This is a simple Android application to view information on movies that is available through the [TMDB API](https://developers.themoviedb.org/3/getting-started/introduction). Feel free to download and run the app on your Android smartphones to get a feel of this app. If you face any issues while using the app, let me know by raising an issue. All sorts of feedback will be appreciated 😁

# For developers

This is app is MIT licensed so you can clone the repo and use the code however you seem fit. Any changes made to the original code is not my responsibility. You take sole ownership of the app when you change the code. If you're facing any problems, feel free to reach out to me.

# Setting up your own API key

First you need to get your TMDB API key from [here](https://developers.themoviedb.org/3/).
If you have issues with getting a new API key, here's a short tutorial on [YouTube](https://www.youtube.com/watch?v=Q7swsALUS-o).

Navigate to `lib/secret/themoviedb_api.dart` and replace the X's with your API key.

Before: `const String themoviedbApi = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX';`

After: `const String themoviedbApi = 'your-api-key';`

Once you have added your API key, you can run the `flutter run` command and test out the app.

Feel free to comment or raise and issue if you come across any problems!

**Leave a ⭐**

~ Safwan👑
