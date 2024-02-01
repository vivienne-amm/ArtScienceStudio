# ArtScienceStudio
The [**Art Science Studio**](https://pq.cz/pq-2023-info/projects-2023/student-exhibition-pq/germany-pov-pq/) is a collaborative studio bringing together five computer science students from TU Dresden with six theatre students from the Dresden Academy of Fine Arts (HfBK). The course was led by junior professors Theda Nilsson from HfBK Dresden and Matthew McGinity from TU Dresden. 
we 
To represent Germany at the student competition of the 15th edition of the [Prague Quadrennial of Performance, Design, and Space](https://pq.cz), we created a pavilion encapsulating elements of German culture - the garden houses adorned with garden gnomes and techno music.

The pavilion was exhibited in Prague during the Prague Quadrennial which took place from the 8th to the 18th of July.

Below is a selection of my contributions:

## AR Posters
![image](https://github.com/vivienne-amm/ArtScienceStudio/assets/58234607/7d179cca-e8c7-4843-b6e8-13fc6c94d809)

I designed three posters using Figma and Blender that were exhibited on the exterior of the pavilion. To incorporate augmented reality functionality, an AR marker was integrated into each poster.
Since I did not possess any prior Blender experience and due to time constraints, the decision was made to create and modify Blender shapes based on online tutorials by [Ducky 3D](https://www.youtube.com/@TheDucky3D).

- The first poster features a dancing figure wearing a warning vest matching the vests worn in the pavilion. This poster is an instructional guide explaining how to use the AR markers on the posters and stamps.
- The second poster showcases a vibrant transforming flower, symbolizing the garden house ([Tutorial](https://youtu.be/nsqeZV9mKTc)).
- The third poster embraces a techno-inspired aesthetic, reflecting the ambiance of the techno club at nighttime  ([Tutorial](https://www.youtube.com/watch?v=MrgusWbdEGY)). 

https://github.com/vivienne-amm/ArtScienceStudio/assets/58234607/783bd63c-9dd4-4b42-bd39-28706d2e59f5

### AR Application and AR Stamps
![Group 5](https://github.com/vivienne-amm/ArtScienceStudio/assets/58234607/2269378a-96b2-4a07-8a62-d1eb331af711)
*(A) AR Pavilion Decoration application (B) Club Entry Stamp Functionality (C) Stamp used as AR marker*
#### Stamp
For the pavilion, entry stamps were created that combined two functionalities:
1. Club Entry Stamp Functionality: Incorporating the club entry stamp into the pavilion was supposed to give the feeling of a genuine club environment. However, while traditional clubs often employ stamps as exclusive and mandatory indicators for entry, the garden club adopted a different approach: Here, the stamps were optional and were supposed to foster a sense of belonging and a welcoming atmosphere.
2. Additionally, the stamps served as AR markers. By scanning the stamps using their mobile devices, visitors were able to observe an AR experience in which an animation of dancing characters was superimposed onto their camera feed. This feature allowed visitors to virtually carry these dancing characters with them throughout the club, ensuring a perpetual lively atmosphere, even if they happened to be the sole visitors at that time.

The stamps were made utilizing the laser cutter available in the Makerspace at the TU Dresden. The JavaScript Library [AR.js](https://ar-js-org.github.io/AR.js-Docs/) was chosen, primarily due to its cross-browser compatibility. The animated characters were generated using [Mixamo](https://www.mixamo.com/#/) and [Blender](https://www.blender.org). The vest worn by one of the Mixamo characters served as the template for all other characters, ensuring a consistent "warning vest" appearance. This design choice corresponded with the uniforms worn by students from TU and HfBK, promoting visual coherence and identification.
The AR Marker itself had the design of the PQ logo. 

#### AR Pavilion Decoration App
I developed an app for the HfBK annual exhibition, aiming to establish a stronger connection between the pavilion and the AR elements.
With this app, visitors had the opportunity to decorate the pavilion and bring animated dancing characters to life inside of it. They can choose from a variety of items inspired by garden houses, dance, and music themes, including watering cans, boomboxes, plants, dancing people, and vinyl records. Users can easily place the chosen items on the screen with a simple tap.
The app, created using [Unity](https://unity.com/de) and [AR Foundation](https://unity.com/de/unity/features/arfoundation), was accessible on iPads within the pavilion.
