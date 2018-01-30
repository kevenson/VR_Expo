
# VR Expo
## The Educational Affordances of VR

My VR Expo is a mobile VR experience for Google Cardboard. This experience is somewhat unique in the sense that it that was designed for educators to help showcase the many educational affordances of virtual reality.

The application puts users in a small college quad where thy can use the waypoint navigation system to move through the scene and learn more about the applications of virtual reality at a series of five stations, based on reasearch I conducted for this project. The primary focus is on higher education--covered in the Digital Humanities, Social Sciences, and Natural Sciences stations--but there are also two stations that cover applications in K-12 and for online learning.

This application took me about two full weeks to complete (~20 hours). In addition to the main scene with the five information stations, there are a number of smaller scenes you can travel to at the stations that demo specific functionality, like the ability for students to "tour" a 3D model they've created in virtual reality.

You can see a video demo of the application being played here:

### INSERT YOUTUBE PLAY video

## Outcomes

This was another practice project for me. My goals going in were to continue developing my skills with Unity--particularly transitioning through multiple scenes and adding helpful audio with instructions and descriptions--and researching and communicating some of the educational affordances of virtual reality.

This last part is important. I work as a technology consultant for higher ed, so having a wide variety of use-cases in mind for virtual reality is part of my job. This project not only helped me think about those use-cases, but also begin developing "proof-of-concepts" with Unity covering some of these use-cases that I can use for communication and also as a basis for future projects.

## Process

As with previous projects, the first step in creating my VR Expo application was creating a persona for the project--an imagined person who I thought would be interested in this type of application. This is a common method for developers, which allows them to test some of their insights and impulses on an imaginary user before they've started the hard work of developing their application.


#### Persona

##### Westerfield Chestnut

![image](https://upload.wikimedia.org/wikipedia/commons/6/61/Constantin_Jiquidi_-_Vintil%C4%83_C._A._Rosetti%2C_Foaia_Popular%C4%83%2C_19_mar_1900.JPG){:height="35%" width="35%"}
###### Age: 56
###### Occupation: Historian (Associate Professor)
###### Quote: "VR provides new methods to reinvigorate the study of the ancient world"
###### VR Experience level: low

Westerfield is a professor and academic researcher who studies human societies in ancient Mesopotamia, and is inspired by the potential of VR to provide new ways to understand, visualize and interact with these societies. He has demoed custom VR applications developed by colleagues that allow users to walk through reconstructed cities and inspect ancient artifacts that are not available to the public. He is very interested in learning more about emerging VR tools and methods to support the digital humanities.

#### Sketches

Next in the process were a series of sketches I did for the overall structure of the application.

My first idea was to build the showcase within a large auditorium or classroom, as you can see in this first sketch:

![Sketch1](/ProjectFiles/FirstPush/s1.jpg){:height="35%" width="35%"}

However, just for the sake of practice, I did a follow-up sketch using a park as the environment for the showcase, as you can see here:

![Sketch2](/ProjectFiles/FirstPush/s2.jpg){:height="35%" width="35%"}

After running these by my user tester for the project, we decided we liked the park environment better than the classroom for the main scene, so I did a couple follow-up sketches and eventually decided on a college quad as my environment:

![Sketch4](/ProjectFiles/FirstPush/s4.jpg){:height="35%" width="35%"}

#### Building in Unity

Once the basic environment for the app was settled, it was time to start building this in Unity. If you're not familiar with it, [Unity](https://unity3d.com) is a powerful game engine that has become one of the most popular platforms for creating VR experiences. It’s free for individuals to download and there are tons of tutorials available online so I would definitely recommend checking it out and experimenting.

For this

Additionally, I knew that I wanted some kind of audio tutorial for this particular application. To accomplish this, I first wrote out my short descriptions for each of the five stations plus the introduction. Then I used [Amazon Polly](https://aws.amazon.com/polly/) to create playable mp3 files out of these text descriptions using natural-ish sounding voices. You can listen to these here:

Intro:
<audio src="/ProjectFiles/Media/AWS_Polly_Intro2.mp3" controls preload></audio>

## User Testing

#### User Test 1 - Basic Design & scale

-- alternate scene in classroom, too small, stayed with quad

#### User Test 2 - Movement

too low - moved waypoints up

#### User Test 3 - UIs


#### User Test 4 - Sound & Mechanics

changed terrain to improve performance

## Breakdown of VR Expo


## Conclusion
