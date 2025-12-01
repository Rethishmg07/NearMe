# Ex03 Places Around Me
## Date: 1/12/25

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title> mapp</title>
    </head>
    <body>
        <h1 align="center">Tiruvannamalai</h1>
        <h3 align="center">rethish(25012569)</h3>
        <img src="Screenshot (15).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="hill" title="hill" href="hill.html" coords="680,363,75" shape="circle">
    <area target="" alt="asaramam" title="asaramam" href="asramam.html" coords="410,700,608,760" shape="rect">
    <area target="" alt="skandasramam" title="skandasramam" href="skandasramam.html" coords="581,493,67" shape="circle">
    <area target="" alt="niruthi lingam" title="niruthi lingam" href="niruthi lingam.html" coords="47,484,91,448,138,448,147,509,101,541,50,535" shape="poly">
    <area target="" alt="kubera" title="kubera" href="kubera.html" coords="804,67,719,4,685,72" shape="poly">
</map>
 
    </body>
</html>
Hill.html:
<html>
    <head>
        <title align="center">About HILL</title>

    </head>
    <body style="color: rgb(255, 255, 255);"  bgcolor="yellow">
        <h1 align="center"> Arunachaleshwarar hill</h1>
        <p style="font-size: 25;">Arunachala Hill is a sacred mountain in Tiruvannamalai, South India, revered by Hindus as a physical manifestation of Lord Shiva. It is considered one of the five main Shaivite holy places and is associated with the fire element (Tejo Linga). The mountain is famous for its spiritual significance, the practice of circumambulating it (Giri Pradakshina), and the history of saints and sages, like Ramana Maharshi, who have meditated there. 
Spiritual significance
Manifestation of Shiva: According to mythology, Shiva appeared as a column of fire between Brahma and Vishnu, and this light took the form of Arunachala Hill.
Symbol of Shiva: The hill is regarded as the "first lingam" (Adi-Lingam), symbolizing the supreme being in the form of a fire mountain.
Spiritual benefits: It is believed that simply seeing or thinking of the hill can neutralize karma, and a circumambulation around its base is considered a spiritually beneficial act. </p>
    </body>
</html>

niruthi lingam.html:
<html>
    <head>
        <title align="center">niruthi lingam</title>

    </head>
    <body style="color: rgb(255, 255, 255);"  bgcolor="gray">
        <h1 align="center"> Niruthi Lingam </h1>
        <p style="font-size: 25;"> Arulmigu Niruthi Lingam Temple is one of the eight Ashtalingams located along the Girivalam path in Tiruvannamalai. It is situated in the southwest direction of the Arunachala Hill. The temple is dedicated to Lord Niruthi, the guardian deity of the southwest direction. 
Sacred Geometry – Tiruvannamalai | Arunai Anantha Resort ...
Location and significance
Direction: The lingam is located on the southwestern side of the Girivalam path, which encircles the Arunachala Hill.
Deity and association: The lingam is associated with Lord Niruthi, who is also known as the king of the Asuras (demons). It is also connected with the planet Rahu.
Spiritual benefits: Devotees believe that worshipping at the Niruthi Lingam can bring various benefits:
Protection from negative energies, black magic, and evil influences.
Removal of obstacles and challenges in life.
Blessings of good health, wealth, and fame.
Blessings for couples seeking to have children.
Relief from ailments related to skin, nerves, and mental health. 
Visiting the temple
Address: 62MM+R3G, Tiruvannamalai, Tamil Nadu 606603.
Girivalam pilgrimage: The Niruthi Lingam is the fourth of the eight lingams on the sacred Girivalam route. Many devotees visit it as part of their pilgrimage around Arunachala Hill.
Timings: The best time to visit is during the early morning or late evening to avoid the heat. 


 </p>
    </body>
</html>

Kubera.html
<html>
    <head>
        <title align="center">Kubera lingam</title>

    </head>
    <body style="color: rgb(255, 255, 255);"  bgcolor="pink">
        <h1 align="center"> Kubera Lingam </h1>
        <p style="font-size: 25;">The Kubera Lingam in Tiruvannamalai is a sacred Shiva lingam located on the Girivalam path (the circumambulation path) encircling the Arunachala Hill. It is dedicated to Lord Kubera, the god of wealth, who is believed to worship Shiva here to maintain his prosperity. The temple is situated in the northern direction from the mountain and is associated with the planet Jupiter (Brihaspati). 
Location and significance
Location: The temple is situated on the northern part of the Girivalam path, a few hundred meters before the Panchamukham. It is located about 3.8 kilometers north of the Arunachaleshwarar temple.
Legend: Legend states that Lord Kubera, the god of wealth, comes to this sacred spot to worship Arunachala to secure his wealth and prosperity. A lingam was installed at this location, facing north from the mountain, to honor this event.
Worship: Devotees visit this temple to seek blessings for financial stability, abundance, and prosperity. It is considered one of the eight lingams on the Girivalam path. 
Associated deity and planetary influence 
Lord Kubera: The temple is dedicated to Lord Kubera, who is known as the chief of the Yakshas (nature spirits), the treasurer of the gods, and the one who distributes wealth.
Lord Brihaspati: The lingam is also associated with Lord Brihaspati (Jupiter), the planetary ruler of the lingam. 
        </p>
</html>

asramam.html
<html>
    <head>
        <title>About Asramam</title>

    </head>
    <body style="color: rgb(255, 255, 255);" bgcolor="cyan">
        <h1 align="center">Asramam</h1>
        <p>The Sri Ramanasramam ashram in Tiruvannamalai is a spiritual center dedicated to the teachings of Sri Ramana Maharshi, located at the foothills of Arunachala Hill. It is a peaceful place for spiritual seekers to stay, meditate, and experience silence, with features like a meditation hall, a samadhi (final resting place) shrine, and healthy vegetarian food. Visitors can also explore the grounds, visit the bookshop for his teachings, or participate in spiritual activities. 
Key features of Sri Ramanasramam
Spiritual center: The ashram was established by Sri Ramana Maharshi and is dedicated to his teachings on self-inquiry and inner peace.
Samadhi Shrine: The main attraction is the shrine where Sri Ramana Maharshi's samadhi is located, a place where devotees sit in silence to meditate.
Meditation Hall: A serene and simple hall that is popular for its deep spiritual presence and stillness.
Silence: The ashram maintains silence to foster a peaceful and tranquil environment for visitors.
Residences: The ashram provides a place for visitors to stay, typically for a week or less, and is open to people of all beliefs.
Food: Healthy and tasty vegetarian meals are served three times a day.
Bookshop: A bookshop is available for visitors to explore Sri Ramana Maharshi's teachings. 
Activities and spiritual experiences
Meditation: Visitors are encouraged to meditate in the quiet and peaceful atmosphere of the ashram.
Girivalam: The ashram is situated near the base of Arunachala Hill, and visitors can participate in the ritual of walking the Girivalam path around the hill.
Learning: The ashram is a great place to learn about Indian spirituality and Sri Ramana Maharshi's philosophy through daily activities and discussions.  </p>
    </body>
</html>


skandasramam.html
<html>
    <head>
        <title>skandasramam</title>

    </head>
     <body style="color: rgb(255, 255, 255);"  bgcolor="blue">
        <h1 align="center"> Skandashramam </h1>
        <p> Skandashram is a sacred cave on Arunachala Hill in Tiruvannamalai where Sri Ramana Maharshi lived from 1916 to 1922. It's a popular spot for meditation and offers a bird's-eye view of the Arunachaleshwarar Temple. The ashram can be reached by a scenic uphill path that starts from the back of Ramanashram and is a popular pilgrimage site for spiritual seekers. 
Historical Significance: It was Ramana Maharshi's residence before he moved to the current Ramanashram after his mother's passing. The ashram retains the cave where he meditated, which is now preserved as a meditation hall for visitors. There is also a small room where his mother, Alagammal, lived.
Accessibility: The ashram is located about 1.4 kilometers uphill from Ramanashram. The path is rocky and can be challenging, so it's recommended to wear appropriate footwear or walk barefoot when the stones are hot. The path to Skandashram is also part of the way to Virupaksha Cave.
Meditation and Views: The ashram is a place renowned for its peaceful and meditative atmosphere. From its location on the hillside, it provides a panoramic view of the Arunachaleshwarar Temple. </p>
    </body>
</html>







```


## OUTPUT
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot 2025-12-01 112203.png>)
![alt text](<Screenshot 2025-12-01 112126.png>)
![alt text](<Screenshot 2025-12-01 112105.png>)
![alt text](<Screenshot 2025-12-01 112038.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
