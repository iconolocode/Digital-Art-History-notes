# Digital Art History notes
summaries of talks about Art History and Digital Methods
*As the recordings are available online, I assume there isn't a problem with sharing my notes. If their authors wish to, I will remove them.*

These are bullet points reworded by me and aren't perfectly accurate. Please refer to the original recording or writings of the author. 

---
## David G. Stork: “Rigorous Technical Image Analysis of Fine Art: Toward a Computer Connoisseurship”
https://youtu.be/Z0t_C0urQ5s
https://youtu.be/rbL_Y-hZh20

- Computer vision techniques on art 

Light direction detection:

Model independent (no need to have a 3d model) 
- cast shadow (angle between object and shadow) 
- occluding contour (need normal of the outer boundary of the object, used to detect photoshopped images to)

Model dependence (need 3d model)
- make a 3D rendered object of the painting until it matches the one in the painting
- use the glint in the eye
- shape from shading with a 3d model of a face that is adjusted to the person in the painting 
- make a full 3D model of the painting
- floor model and point source

Case study with the Girl with the Pearl
- great consistency of the direction of light painted by Vermeer
- did the painter use a model? The light here is so perfectly accurate that it couldn't just come from imagination
- did artists use optical devices to project a reflection on their canvas? This could explain the big improvement around 1430 in realistic depiction 
- if an object has slightly different light direction, it means it has been added later
- human brain isn't so good at detecting lightning differences, these methods allow us to detect collages

Also study (convex) mirrors in paintings, if reference was used. Dewrap view from curved mirror.

Did artists "cheat" with optical devices? See how accurate perspective is. The human brain doesn't see errors in perspective and artists can be really good at depicting things accurately without help. "Cheating" isn't necessary to have good enough perspective. 

What about art history in the future? At the moment computers are good at identifying things in an image, one day in the future computers could also do the iconological interpretation.

We could also do pattern recognition based on hands and ears to identify style or sicknesses in the portrayed persons. Computer connoisseurship.

---
## Lizzy Jongma: The Bigger Picture: The Rijksmuseum Digital Revolution
https://youtu.be/puBv4-0V1NE

> "Even before we could plan the digitization (of course really well carefully done digitization) of our most beautiful works of art in our collection, we found out that, well that the entire world had already digitized our collection. And this is just a random screenshot of over the one thousand different images that exist if you google for Vermeer's Melkmeisje"

Digitization of the collection already happened. Visitors put images of the artworks online.

*Questions were added by me to give some structure.*

Is it still necessary to digitize the collection?
- Yes, the quality of the images on the internet often isn't really good.

How can museum's photos distinguish themselves?
- Digitize in the best quality, high definition versions.

How does this compare to the real artworks in the museum?
- With the digital version you can look really close to the painting, see the brushstrokes, cracks and signature. This is not something you can do in a museum due to security reasons.

How does this compare to digital pictures of the artworks?
- Semi-museum experience, dive into the painting.

Why would people still go to museums then?
- Seeing photos of an artwork can make the person wanting to see the real thing. It is better to be famous on the internet than totally unknown.

What should we digitize?
- Not only the famous pieces, also the unknown ones. The whole collection is amazing, but a lot of pieces are too fragile to be ever put on display. We have to keep them in storage, but now we can finally share them.

What does the like button add?
- Real people liked the object, the object get's it's own community. People want to find 'lonely' artworks, to be the first to like. After one and a half year, each artwork had at least one heart. 

What other features does the Rijksstudio have?
-Took inspiration from Pinterest, users can make their own collections. Not only museum professionals use the function, people really enjoy to gather and collect, doing their own exhibitions, making links with objects that not even staff knows that they exist.

Where there sacrifices that needed to be done?
- Remuneration of the pictures. Since it is available online, the selling rights aren't needed anymore. 

Should we be happy with the free commercial use of the collection?
- Consider it like artists going to museums for inspiration, a source of creativity that leads to new artworks.

What other digital approaches where done?
- Also give developers access to the collection and metadata with an API. Be part of hackathon events. Connect with as many as possible platforms, to go from a local museum to a global art repository.

How was it received?
- People were creative and made stuff with it, and shared it online. On platforms like Etsy they sold their versions of the artworks. ArtSTOR annexed the collection, but it was in Dutch, so they translated it and gave that data to the Rijksmuseum. Aggregators redirect a lot traffic towards the museums website. With wikicommons, a lot of pictures of the collection were used on Wikipedia. Artworks are connected to global stories. Knowledge is made accessible, information isn't limited to the museum's staff or papers. Artworks from those platforms allows for example to see in which topics some countries are interested. 

---

## Brendan Ciecko: Exploring Artificial Intelligence in Museums
https://youtu.be/EzZyD76bPkA

AI big trend, everywhere, also in museums.

Collections: structuring and analysing the meta-data. AI can do data cleaning and classification. 

Traffic: understanding how ticketing, marketing and social media relate. Predict busy times.

More personal: find things that can interest you, help you find what you are looking for.

Chatbots 

Digital projects can help with fund raising 

New techniques:
- Computer vision
- Topic modeling
- Sentiment analysis 
- Text extraction 
- Art authentication 
- Recognize similarities and patterns
- Accuracy of replicates
- Color composition 
- Face recognition 
- Link news to art
- Writing labels

-> can lead to interesting discoveries 

---
# Emilie Gordenker: Dutch Old Masters and New Technologies

https://youtu.be/euE6obcJlek

Digitization comes to the museum:
- Montias Database
- media tours and interactive games
- websites 

Lot of things changed the last 20 year.
How does it affect the field?

Use tech to reach a younger and more international audience. 

A lot of museums have open digital collections. But some institutes hold on their images licenses.

Make interactive websites, videos, 3d visualizations and VR.

Use platforms like Europeana and Google Arts and Culture to share content with everyone. 

Storytelling can be done through infrared and other technologies.

AI to answer questions about AI

---

## Elizabeth Honig: Human vision, computer technology and the image investigation tool
https://youtu.be/fL0qfrQeAaI

Dutch painters made a lot of paintings by reusing sketches. Jan Brueghel has a big quantity of it in his corpus of works, from small elements to whole compositions.

A tool to compare similar images OpenArt based on Drupal by Agile Humanities. 

Grids were used when making paintings, hence it is an useful tool to compare compositions. 

Extracting details, make them transparent, resize and flip them to overlay them and compare them. It links the metadata and calculates the scale difference.

This annotated dataset is also useful for computer vision research. Computers started to study a bigger collection and found similar windmills in Brueghel's fathers painting.

---

## Carl Stahmer: Archive-vision using content based image recognition to build a World-Wide Library of early printed materials
https://www.youtube.com/watch?v=1VBSMiXPp7c

Images were reused in different contexts or were remade into paintings.

Technology used:
- SURF feature points
- Homography
- text mining TFIDF to identify features 
- Similarity network (Markov Clustering)

Website: English broadside ballad

Search by image, can upload your own images too

Labeling: machine assisted cataloging, aggregate tags from other images

Later: sort by topic, not only visual similarity but also semantic similarity 

---
## Vardan Papyan, XI Han: Experiences with Deep Learning for multi label art classification
https://youtu.be/8b72gpcUrPw

Help tagging images which is often done manually based on a dataset with images and their labels.

With the algorithm the workload is reduced and the archivist only needs to correct the labels. 

It's difficult to label specific tags that aren't used really often.

How big should the dataset be then? For the Frick Collection per tag at least 500 examples were needed for okay results and 5000 examples for 90% accuracy.

---

## Bjorn Ommer: Understanding Art: Distant viewing meets close reading.
https://www.youtube.com/watch?v=eEWJURvdqUA

Deep learning needs big datasets and annotations.

Imagenet doesn't work great on art, it had to be an AI trained with art in its data set, do transfer learning.

But with art history we want a model that evolves with new art.

Similarity / dissimilarity in art is difficult to define. Similarity in color, composition, posture, theme?

---
## Sabine Lang: Understanding art: a critical assessment of potentials and challenges 
https://youtu.be/RqLIShTpol4

Things we can do:
- Search for parts in images
- Sort images by criteria, like a map with an axis for social status and another for age.

Study of shape: how images changed when they were copied. Gestures used for communication in manuscripts, pose analysis.

Automatic cuneiform script detection.

---
## Samanyha Deutch and João Lucas Rulff da Costa: ARIES: ARt Image Exploration Space 
https://www.youtube.com/watch?v=jBjfog_VsEQ

Art historical practice to compare and organize art, done with images transparencies, photocopies or powerpoint.

It was a time consummated practice. A tool to do it digitally.

https://artimageexplorationspace.com/

---
## John Resig implementing image similarity matching: comparing open source and commercial solutions 
https://youtu.be/JzYeEGDVNNU

A lot of physical photos of art and prents that got digitized. But there isn't much meta data. We can't link them together by their creator or title as these infos are missing. 

Pharos = multiple art databases, same problem, different meta data standards from each institutions.

Combine photos of art to their source, different possible technologies:
- Pastec (open source)
- Clarifai (commercial, color insensitive)

Issues
- When an image is cropped, it doesn't always find the source
- Tags are not always relevant 

---
## Ahmed Elgammal: ArtPi - the art API: artificial intelligence for art recognition 
https://youtu.be/jq7cDXG-zqU

Search by criteria, specialized for art.

Can match images in selfies.

Quantify style

---
## Sabine Süsstrunk and Frédérick Kaplan: Deep learning: extracting syntax and semantic from images
https://youtu.be/1g56Vg2B-GE

- Annotate videos, allows to query and classify them
- Annotate body poses: the pathos poses aren't possible in reality, so they come from a visual language 

Replica project:
- Paper physical archive to digital.
- Use machine learning to identify the content on the paper boards.
- Match the extracted names with artists names in the Getty database.
- Cluster search results by similarity.

---
## Conrad Rudolph: FACES 2.0: Faces, Art and Computerized Evaluation Systems
https://youtu.be/0xTK7IYMFi0

Find the identity of portraits.

Face recognition in photographs need to deal with different angles, lighting and age.

With paintings there are extra factors: style of the artist, subjective interpretation, traditions in representation.

FACES 1.0: successful, but testing images had cumbersome (uses face features extraction with anthropometric distances and local features)

FACES 2.0: redesign of the algorithm, automation, available online (uses deep neural networking, which mimics the human brain, more flexible and nuanced). Trained on a labelled dataset of already identified portraits and created its own feature set based on a process of layered analysis.

Requirements:
- more than 4 known images of the person, but more is better
- good images

Technology around face recognition could be used in other ways for the art: styles depiction, hands, ornaments, networks of people by using the owner data and the portrayed.

---
## John R. Smith: Creativity: The Next Horizon for Artificial Intelligence 
https://youtu.be/ApwW9VRe3EY

Can Ai be creative? Creativity: ideas that come from nowhere.

MOV37 in chess

Here: making movie trailers
Datasetv horror movies as they are less subtle, more exaggerated which is easier for the machine to identify objects in it.

Select snippets by uniqueness, rare features, but this gave results that aren't really what was wanted

Other selection criteria: emotions. Train the machine on characters with no facial expressions from Disney (C-3PO), and identify emotions in posture and sound.

Deployed a similar system on a golf event to identify exciting moments, IBM H5.

A reverse approach: official trailer versus the source film. Let the computer make a feature space which determinates which scenes with specific characteristics used in the trailers. Results: scary, tender, suspence.

Select top 10 scenes according to those characteristics for a film that wasn't publicly released.

Also asked a human video editor to make from it a trailer.

Is the program here creative? More of a supporting role, as it only selects the data. One scene was kept out, as it was a spoiler.

---
## Jennifer Deason: Personalizing the art world taste fingerprints and computer vision
https://youtu.be/UizpnLm541Y

Techniques used in commercial settings that can be used in the art world:

Pinterest: Words can have multiples meanings. How to filter images by meaning? Pinterest is one of the biggest image databases. It remembers paths taken previously by the users to get an idea of the topic they are researching and get the correct meaning.

Amazon prime: shows actor names and music in a video. In the future, maybe and links to buyable items which appear in the backgroundy/decor.

Netflix: adapts thumbnails depending on the interest of the viewer

Thread Genius: map links between different works,  which allows to recommend things that the user could be interested in. (Took a concept from Spotify and adapted it in a visual way. Got bought by Netflix)

--- 
## Aba Irollo: Cultural Heritage reuse data in research 
https://youtu.be/viNWfTStK5M

Survey of users of the database that are interested in art history.

Tend to use assets like book, manuscripts and newspapers instead of art objects.

Tools used with it:
- OpenCV
- SOD CV
- API
- Openrefine

---
## Elizabeth Bemick: Digital study of chain lines 
https://youtu.be/viNWfTStK5M

chain lines = (impressions left by wires used when making paper from pulp) allows to know if drawings come from these same sketchbook

### Nick Mols:
Architecture theory is based on concepts of points, lines and planes. These concept can be translated to vector 3D. Designs were distributed in prints. With a scanned version the ink can be digitally extracted in great detail and transposed to CAD 3D with Luci. This digital version is more precise than the paper one as the printing techniques have limitations. We can get more close to the proprtions and vision of the designer. 

### Reagan Martin:
Old copyright in Venice. Annotation of the documents from the archives and making a database from it. By visualizing the data interesting conclusions can be made. 

### Liron Efrat:
Research on how augmented reality apps are used. A collection of them was made and which allowed to index them. fabricofdigitallife.com  re-curating of art, research process becomes creative

Other digital methods for art history:
- Watermarks in paper and make them searchable in databases
- Remote sensing will allow us to see alterations on paper
- Visualizations tools are often based on language analysis tools. We could study like this artist contracts
- New frameworks of analysis  

---
## Alonzo C. Addison: Digitizing a disappearing world: crowds, cloud and culture
https://youtu.be/dJtLS4QBnBg

Historical sites degrade with time due to:
- Crowds: Touching, vandalism, waste, fungus and bacteria
- Clouds: rain, flooding, pollution, climate change
- Also war and other conflicts

3 categories:
- Capturing: flatbed scanning, 360 panoramic filming, photogrametry, aerial imaging, 3D scanning, geographical mapping.
- Computing: processing the captured data. 
- Creating alternate realities: AR, VR

Challenges:
- Not all information is translated in scans
- Errors in metadata 
- Wrong resolution 
- What do we reconstruct? 
- Is it sustainable 
- Duplicate projects
- Lifespan of digitalfiles and encoding
(See examples in video)

We need to have guidelines 

Future:
- Mass digitization 
- Crowdsourcing 
- Sharing data and opensource

---
## Carla Schroer and Mark Mudge: bringing scientific imaging to a broad base of cultural communities 
https://youtu.be/8eLFX4iTE_A

CHI: cultural heritage imaging

Democratize technology for people to share their culture and reinforce local narratives and empower their voice

- RTI: reflectance transformation imaging
- Multi spectral imagin
- High dynamic range imaging
Allows "Enhance mode"

Digital lab notebook: record the digitization proces

Lot of stuff on the website culturalheritageimaging.org

See also mukurtu.org 

---
## Emily L. Spratt: Searching for the through seeing: optimizing computer vision technology for the art
https://youtu.be/ffp9YX4-dlg

Love for the senses, sight being the most important.

This capacity has become reproducible by machine. Computer vision makes us ask what does seeing really mean? How does this affect how we perceive art?

Human perceptual quality versus machine enabled vision

Transforming visual information to knowledge about the world. 

We know little about how vision works on a neurobiological level. Art is on a higher-order level of thinking, which remains largely theoretical.

Vision is really complex.

[Section about vision in art history]

Internet and computer vision changes the way we interact with images. We should study their impact or use them as a collaborator.

---
## Leonardo Impett: open problems in computer vision for the history of arts 
https://youtu.be/zsQKFxqqTto

CV in art =/= CV on art

Different uses:
- Search engines
- Visual links
- Corpus visualization 

Examples: Replica Prohect, ArtMiner, PixPlot

PHAROS is a dataset twice bigger than ImageNet 

Distant reading: analysing a big corpus

Pathos concept: specific position to express emotions. Computational analysis shows that a lot of these poses are derived from one general pose

Michael Baxandall: a viewer from the same time period would not only recognize the topic of an artwork, but also a specific time point of the event

---
