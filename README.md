# History-app_1
![a-walk-through-art-and-history-free-ppt-template-and-google-slides-570x350](https://github.com/st10448997/History-app_1/assets/161011444/762eb5f6-9447-4ff6-be48-a66e02f62cea)


IMAD5112 Assignment 1

# The purpose of the app:
The purpose of creating an application where users are prompted to enter their age and then receive information about the history behind that age is to make history more personalized and engaging with the users.
By connecting historical events to the user's own life experiences,the application can create a more meaningful and relatable learning experience. This can help users develop a deeper understsanding and appreciation for history by showing how it directly intersects with their own lives. It can also foster a sense of connection to the past, as users see how events from different time periods have shaped the world they live in today. Additionally, by making history more personalized and engaging, the application may encourage users to explore further and learn more about different historical events and periods. This can ultimately lead to a more informed and well-rounded understanding of the world and its history.

IMAD5112 Assignment 1

# The purpose of the app:
The purpose of creating an application where users are prompted to enter their age and then receive information about the history behind that age is to make history more personalized and engaging with the users.
By connecting historical events to the user's own life experiences,the application can create a more meaningful and relatable learning experience. This can help users develop a deeper understs of the past and encourage them to explore and learn more about different historical events and time peroid

**Application Purpose: Personalized Historical Learning**

The purpose of this application is to revolutionize the way people engage with history by providing a personalized and interactive learning experience. By prompting users to enter their age, the app aims to bridge the gap between historical events and individual life experiences.

**Key Objectives:**

1. **Personalization:** By connecting historical events directly to the user's age, the application tailors information to their specific life experiences. This personalization makes history more relatable and meaningful.

2. **Engagement:** By making history more personalized, the app seeks to increase user engagement. By linking historical events to users' own lives, it creates a unique and immersive learning experience that captivates users' interest.

3. **Education:** The primary goal is to educate users about historical events in a fun and interactive manner. By presenting historical information in a way that directly relates to the user's age, the app aims to enhance understanding and retention of historical knowledge.

4. **Curiosity and Exploration:** The application encourages users to explore different time periods and historical events. By sparking curiosity and providing easily accessible information, it fosters a deeper interest in history and motivates users to learn more.

**Benefits:**

1. **Meaningful Learning:** By connecting historical events to users' own experiences, the app fosters a deeper understanding and appreciation of history. Users are more likely to remember and relate to historical information that directly relates to their lives.

2. **Customized Experience:** The app provides a unique and customized learning experience for each user based on their age. This tailored approach ensures that users receive information that is relevant and interesting to them.

3. **Fun and Interactive:** Through its personalized approach and interactive features, the app makes learning history enjoyable and engaging. Users can explore historical events in a way that feels like a journey through their own lives.

4. **Inspiration for Further Exploration:** By presenting historical information in an accessible and engaging format, the app inspires users to delve deeper into different time periods and historical topics. It serves as a gateway to further exploration and learning.

In summary, the application aims to revolutionize history education by providing a personalized, engaging, and educational experience that connects users' ages with relevant historical events. Through its innovative approach, the app seeks to inspire curiosity, foster understanding, and ignite a lifelong passion for history.

# Background Picture
The disign includes images and text ,as part of thr scrollable layout.It is a historical context,with reference to art and history.
The layout has a placeholder text like "TextView","EditText",and two buttons.These placeholders indicate the different types of user interaction elements that are part of the application,such as areas for displaying text (TextView),input fields for users to enter text (EditText) , botton for submitting the age entered and a button to clear out the recieved results

This code snippet defines the `MainActivity` class for an Android application. Let's break it down step by step:
David Bambatha Maphgumzana Sibeko was known as the "Malcolm X of South Africa" and began his political career as a journalist for the black South African magazine Drum. During his tenure w
1. ```kotlin
   class MainActivity : AppCompatActivity() {
   ```
   This line declares a class named `MainActivity` that inherits from `AppCompatActivity`. In Android, activities represent the different screens in an application, and `AppCompatActivity` provides backward-compatible features for newer versions of Android.

2. ```kotlin
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
   ```
   This is the `onCreate` method, a lifecycle method called when the activity is being created. Within this method:
   - `super.onCreate(savedInstanceState)` calls the superclass implementation of `onCreate`.
   - `setContentView(R.layout.activity_main)` sets the layout of the activity to be displayed from the XML file `activity_main.xml`. This XML file defines the arrangement and appearance of UI elements for the activity.

3. ```kotlin
        val txtInfor = findViewById<TextView>(R.id.txtInfor)
        val txtResults = findViewById<TextView>(R.id.txtResults)
        val editText = findViewById<EditText>(R.id.editText)
        val btnCalculate = findViewById<Button>(R.id.btnCalculate)
        val btnClear = findViewById<Button>(R.id.btnClear)
   ```
   These lines retrieve references to various UI elements defined in the layout file `activity_main.xml`:
   - `txtInfor` and `txtResults` are TextView elements with IDs `txtInfor` and `txtResults`, respectively.
   - `editText` is an EditText element with ID `editText`.
   - `btnCalculate` and `btnClear` are Button elements with IDs `btnCalculate` and `btnClear`, respectively.

#Iconic 

David Bambatha Maphgumzana Sibeko was known as the "Malcolm X of South Africa" and began his political career as a journalist for the black South African magazine Drum. During his tenure with that magazine, he became a leading figure within the Pan Africanist Congress of Azania.

Robert Sobukwe founded the Pan Africanist Congress in 1959. He was imprisoned from 1960-1969. After his release in 1969, he lived with his family under house arrest. 

Steve Biko was born in Tylden, Eastern Cape, South Africa in 1946. As a medical student, he founded a black student organisation in 1969 and created a national 'black consciousness' movement. The movement's aim was to combat racism and the South African apartheid government. ... 

Solomon Kalushi Mahlangu was a South African freedom fighter, struggle activist and operative of the African National Congress militant wing, Umkhonto we Sizwe. He was convicted of murder and hanged in 1979.

Oliver Reginald Kaizana Tambo was a South African anti-apartheid politician and activist who served as President of the African National Congress from 1967 to 1991. Wikipedia

Desmond Tutu was a South African Anglican bishop and theologian, known for his work as an anti-apartheid and human rights activist. He was Bishop of Johannesburg from 1985 to 1986 and then Archbishop of Cape Town from 1986 to 1996, in both cases being the first Black African to hold the position. 
Andrew Sibusiso Zondo was an Umkhonto we Sizwe operative. He detonated a bomb at Sanlam Centre in Amanzimtoti on 23 December 1985, killing five people 

Vuyisile Mini was a trade unionist, Umkhonto we Sizwe activist, singer and one of the first African National Congress members to be executed by apartheid South Africa.

Chris Hani, born Martin Thembisile Hani SSA, SBS, CLS, DMG, MMS, was the leader of the South African Communist Party and chief of staff of uMkhonto we Sizwe, the armed wing of the African National Congress

Peter Sexford Magubane OMSS was a South African photographer and anti-apartheid activist. He was also the personal photographer of President Nelson Mandela. 

Wikipedia Contributors (2019). Peter Magubane. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Peter_Magubane.

Wikipedia Contributors (2019). Chris Hani. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Chris_Hani.

‌Wikipedia Contributors (2019). Desmond Tutu. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Desmond_Tutu.

‌‌

‌
