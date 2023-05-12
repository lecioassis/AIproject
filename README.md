# Real-Time Music Recommendation: Contextualized Algorithm for Playlist Personalization
> **_NOTE:_** This README file will be updated to its proper format further in the development of the project. For now it is a copy of the english version of the SUMMARY. 

When using the shuffle feature on Spotify, users often encounter undesired behaviors, such as the constant repetition of a limited set of songs within a larger playlist. This disappointing experience is the result of a sorting system that is not truly random. It has been found that Spotify's algorithm tends to spread songs from the same artist and albums throughout the playlist, intentionally introducing some imperfections in the playback, all with the purpose of creating an illusion of randomness. However, this project aims to break away from this paradigm by offering a new approach to song sorting, where cohesion and determination are prioritized over the mere sense of randomness.

In the proposed algorithm, songs will be carefully associated, taking into consideration different criteria. These criteria include the songs already listened to by the user, recently listened songs, the currently playing song, and also unheard songs that are relevant due to their popularity or similarity to the user's music repertoire. This approach seeks to ensure a more precise and personalized selection of songs to be added to the playlist.

Furthermore, external audiovisual context will be incorporated into the algorithm through capturing images and videos from a device. This integration will provide the algorithm with the ability to "see" and "hear," enabling the distinction of elements present in the environment. This audiovisual perception adds an additional layer of information to the song selection process. Additionally, extra parameters can be included to provide an even more comprehensive context that goes beyond what video and audio alone can recognize. This multifaceted approach aims to further enhance the quality of music recommendations and provide a more engaging and personalized experience for users.

The project's goal is to seek the highest possible user approval regarding the recommendations, balancing new music suggestions, songs already present in the library, and taking care to avoid detrimental feedback.

To execute the project, the Spotify Developer API will be used as a foundation to obtain essential data about songs and users. However, with some adjustments and configurations, the algorithm can be adapted to work with other databases as long as they follow certain key parameters. The implementation of the project will be done in Python, using the appropriate libraries for the steps of request, data processing, and application of artificial intelligence algorithms. Additionally, an interface will be developed that allows the user to log in with their Spotify account and grant the necessary permissions, such as access to the camera and microphone, for a more complete audiovisual experience. It is worth noting that the main objective of the project is not limited only to suggestions and information collection but also aims to allow changes to the playlist, offering users greater control over their musical preferences.

In conclusion, the development project of an alternative song sorting algorithm for Spotify represents an innovative, user-centric approach focused on providing a more cohesive, engaging, and personalized music experience. By considering the history of listened songs, the ranking of popular songs, the audiovisual context, and additional parameters, the algorithm seeks to balance familiarity and discovery, promoting user satisfaction and elevating music playback to a new level of quality.
