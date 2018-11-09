Inspiration:

Hosts of social events/parties create their own music playlists and ultimately control the overall mood of the event. By giving attendees a platform to express their song preferences, more people end up feeling satisfied and content with the event.

What it does:

Shuffle allows hosts to share their event/party playlists with attendees using a web interface. Attendees have the ability to view and vote for their favorite tracks using a cross-platform mobile application. The tracks in the playlist are shuffled in real time based on user votes.

How we built it:

We used React for the web application (host) and react-native for the mobile application (client). Both applications access a central database made using MongoDB Stitch. We also used socket.io deployed on Heroku to provide real time updates.

Challenges we ran into:

Integrating MongoDB Stitch and socket.io in order to show real time updates across multiple platforms.

Accomplishments that we're proud of:

We're proud of the fact that we were able to create a cross platform web and mobile application. Only a valid internet connection is required to access our platform.

What we learned:

All team members were able learn and experiment with a new tool/technology.

What's next for Shuffle:

Integration with various music streaming services such as Spotify or Apple Music. Ability to filter playlists by mood using machine learning.

Built With:
React.js (Web App), React Native (Mobile App), Node.js, Socket.io, MongoDB Stitch, Heroku
