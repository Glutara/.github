<br>
<div align="center">
    <div >
        <img height="150px" src="assets/Glutara.png" alt=""/>
    </div>
    <div>
            <h3><b>Glutara</b></h3>
            <p><i>A Key to Your Diabetes Journey</i></p>
    </div>      
</div>
<br>
<h1 align="center">Glutara</h1>

![Glutara](assets/Banner.png)

**Glutara: Empowering Diabetes Management**

Glutara unlocks the power of technology to transform diabetes care. We go beyond simple monitoring, offering personalized insights, proactive health recommendations, and seamless connectivity with healthcare providers. Whether you're navigating remote areas or seeking community support, Glutara empowers you to take control of your health, one empowered step at a time.

## Problem Statement

<br/>
<blockquote align='center'>
<h3>“Indonesia ranked 5th in the number of people with diabetes in the world with a number reaching 19,47 million people.”

\- International Diabetes Federation (IDF), 2022

</h3>
</blockquote>
<br/>

Millions of individuals worldwide grapple with the relentless challenges of managing diabetes, a chronic condition that demands **consistent monitoring and care**. Despite the advancements in technology, the process remains burdensome, with **traditional finger-pricking glucose monitoring causing discomfort** and hindering regular monitoring. This issue is exacerbated for those leading busy lives, **leaving little time for necessary health measures**. The fear of potential health emergencies, particularly for individuals living alone, further compounds the need for a **more accessible and painless solution.**

## 💡 &nbsp;Solution Key Points

![Solution Key Points](assets/Features.png)

### 1. Pain-Free Precision

**Ditch the finger pricks** and embrace the future of painless, continuous glucose monitoring. Glutara seamlessly **tracks your glucose levels**, promoting **consistent monitoring** and empowering data-driven decisions for effortless adherence. Say goodbye to discomfort and hello to a new era of diabetes management, one comfortable step at a time.

### 2. Knowledge is Power

Glutara puts **real-time data insights at your fingertips**. Visualize your glucose trends, understand your body's language, and make informed choices every minute. Our intuitive dashboard transforms numbers into wisdom, giving you the power to **optimize your health journey and conquer diabetes**, one empowered decision at a time.

### 3. Strong Together

You're never alone with Glutara. Our **vibrant community connects individuals**, providing a safety net of mutual support and understanding, **especially for those navigating diabetes solo**. Share experiences, offer encouragement, and find solace in knowing you're not walking this path alone. Together, we build a **sense of belonging** and empower each other to thrive.

### 4. Accessible Empowerment

Accessing better health shouldn't break the bank. Glutara champions affordability and inclusivity, making diabetes management a possibility for everyone, regardless of background. Experience the transformative power of technology, free from financial barriers, and unlock a world of endless possibilities towards a healthier future.

<a href="https://raw.githubusercontent.com/Glutara/.github/main/assets/UCD.png">
<img src="assets/UCD.png" target="_blank" />
</a>
<br />

> Click image to enlarge.

This user case diagram gives an overview of the features of Glutara.

## 🎯 &nbsp;UN's Sustainable Development Goals & Targets

### SDG 3: Good Health and Well-Being (Target: 3.4)

![SDG3](assets/SDG3.png)

The inspiration for Glutara lies in the millions of lives touched by diabetes. We saw an unmet need and harnessed the power of innovation to create a solution that makes a real difference. This isn't just about technology; it's about empowering individuals to reclaim their health and live life to the fullest.
1. **Reducing Premature Mortality**
Diabetes isn't a life sentence. Glutara empowers individuals to manage their condition proactively, minimizing complications and contributing to the goal of reducing premature mortality from non-communicable diseases like diabetes.
2. **Tackling NCDs Head-on**
Diabetes isn't just a personal burden; it's a global health challenge. Glutara tackles it head-on by optimizing glycemic control and reducing healthcare costs, ultimately lessening the burden of NCDs on individuals and healthcare systems.

### SDG 9: Industry, Innovation, and Infrastructure (Target: 9.5)

![SDG9](assets/SDG9.png)

At the heart of Glutara lies a belief: Technology shouldn't be a barrier, but a bridge. We're passionate about making advanced solutions accessible and affordable, democratizing healthcare and improving the lives of millions.
1. **Innovation that Empowers**
We're not just building a CGM; we're building a bridge to a future where scientific research and development in diabetes soar. Glutara's data-driven insights pave the way for personalized treatment plans and groundbreaking discoveries.
2. **Non-invasive Revolution**
Ditch the needles, embrace freedom. Glutara's painless CGM technology is a game-changer, unlocking seamless monitoring and empowering individuals to actively participate in their own health journey.

### SDG 11: Sustainable Cities and Communities (Target: 11.6)

![SDG11](assets/SDG11.png)

We believe a healthy planet and healthy communities go hand-in-hand. Glutara was born from the desire to not only empower individuals but also contribute to a more sustainable future for all. We envision cities where technology fosters well-being and builds resilient communities.
1. **Greener Footprint, Healthier Future**
Traditional diabetes management, with its disposable strips and bulky devices, leaves an environmental footprint. Glutara's reusable technology and reduced waste generation pave the way for a more sustainable healthcare future.
2. **Connecting Our Communities**
Diabetes shouldn't isolate individuals, especially those living alone in urban environments. Glutara's community support feature fosters connections, promotes safety, and builds resilience within our cities.

## 👨🏻‍💻 &nbsp;Technology Stack

<div align="center">
<kbd>
<img src="assets/icons/Flutter.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/Dart.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/Firebase.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/Go.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/Gin.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/TensorFlow.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/Maps.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/Arduino.png" height="60" />
</kbd>
<kbd>
<img src="assets/icons/ESP32.png" height="60" />
</kbd>
</div>
<div align="center">
<h4>Flutter | Dart | Firebase | Go | Gin | TensorFlow | Google Maps Platform | Arduino | ESP32</h4>
</div>

## 🛠️ &nbsp;System Architecture

<a href="https://raw.githubusercontent.com/Glutara/.github/main/assets/System.png">
<img src="assets/System.png" target="_blank" />
</a>
<br />

> Click image to enlarge.

### 1. Presentation Layer

**Users** of Glutara will directly interact with the Presentation Layer, namely the Glutara wearable built with **Arduino & ESP32**, as well as the Glutara mobile application built with **Flutter & Dart**. Any business or computational logic is abstracted onto the serverless backend hosted on **Cloud Run**. With Cloud Run's auto-scaling and load balancing capabilities, in the event of more traffic, our backend is able to seamlessly scale horizontally to meet the growing demands of the application. Due to the flexibility and versatility of Cloud Run, an external load balancer in the form of Google's **Cloud Load Balancing** could be tapped on to deploy our backend to multiple regions and further reduce latencies and downtime.

**Click to get more information:**
Glutara frontend mobile application: [Link](https://github.com/Glutara/glutara-mobile)
Glutara backend: [Link](https://github.com/Glutara/glutara-backend)


### 2. Backend Services & Storage Layer
Many miscellaneous backend and storage services abstracted and handled via **Google Cloud**, as detailed below.

| Google Cloud Service     | Purpose & Use                                                                                 |
| ------------------------ | --------------------------------------------------------------------------------------------- |
| Google Maps Platform     | Directions API to display route back home & Maps SDK to display map on the mobile application |
| Firebase Cloud Messaging | Handles push notifications to user                                                      |
| Firebase Authentication  | Handles all authentication related painpoints                                                 |
| Firebase Storage         | Stores profile assets for the frontend application                                            |
| Firebase Cloud Firestore | Main production database for all the main storage purposes                                    |

### 3. AI/ML Platform

Powered by TensorFlow's cutting-edge machine learning, Glutara extracts hidden patterns in your data, unlocking personalized insights and proactive health guidance.

**Click to get more information:**
Glutara machine learning: [Link](https://github.com/Glutara/glutara-machine-learning)

# Getting Started

[Flutter `(Version 2.19.2+)`](https://docs.flutter.dev/get-started/install) must be installed to run this application.

Detailed instructions on how to run the application can be found [here](https://github.com/Glutara/glutara-mobile).

## 👥 &nbsp;Contributors

| <a href="https://github.com/mikeleo03"><img width="100px" height="100px" src="assets/picprof/Leon.png" alt=""/></a> | <a href="https://github.com/GoDillonAudris512"><img width="100px" height="100px" src="assets/picprof/Dillon.png" alt=""/></a> | <a href="https://github.com/margarethaolivia"><img width="100px" height="100px" src="assets/picprof/Olivia.png" alt=""/></a> | <a href="https://github.com/AustinPardosi"><img width="100px" height="100px" src="assets/picprof/Austin.png" alt=""/></a> |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <div align="center"><h3><b><a href="https://github.com/mikeleo03">Michael Leon Putra Widhi</a></b></h3><p>Hustler</p><p><i>Bandung Institute of Technology</i></p></div>                                                                               | <div align="center"><h3><b><a href="https://github.com/GoDillonAudris512">Go Dillon Audris</a></b></h3></a><p>Hacker</p><p><i>Bandung Institute of Technology</i></p></div>                                                                          | <div align="center"><h3><b><a href="https://github.com/margarethaolivia">Margaretha Olivia Haryono</a></b></h3></a><p>Hipster</p><p><i>Bandung Institute of Technology</i></p></div></a>                                                               | <div align="center"><h3><b><a href="https://github.com/AustinPardosi">Austin Gabriel Pardosi</a></b></h3></a><p>Hacker</p><p><i>Bandung Institute of Technology</i></p></div>                                                                            |
