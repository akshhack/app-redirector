# App Redirector (TODO: working name)
Mobile applications do make our life easier but also distracts us from focusing on our work. When bored, our thumbs twindle right towards those Youtubes, Instagrams and Messengers. Instead how more productive could you feel and be spending all that time scrolling through feeds but journalling instead? App redirector seeks to achieve just this. Any time you click on a distracting, "unproductive" app (as per your definition), you're redirected to a more "productive" app (gain as per your definition).

#### How it Works
Once the user has submitted a list of unproductive and productive apps, we store this data on a local database (SQLite).
The main task of blocking and redirecting is done by a background service. The service continuously fetches the foreground (currently active) app and queries through the database to check whether this app is blocked or not. If the app is blocklisted then we randomly choose a whitelisted app and open it up instead.

#### Screenshots
TODO: <Insert screen shots here>
