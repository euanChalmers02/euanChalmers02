# Home Page


**About Me:**
My name is Euan Chalmers I am a 3rd year computing science student at the University of Edinburgh. I am currently looking for an internship opportunity. I have an interest in software engineering with a focus on cloud computing. As well as database design and data-driven applications.I am experienced working in various roles in dynamic work environments that require me to be organised but also adaptable. I have proven experience on several work and personal projects. I am a friendly, positive, and hardworking individual keen to work hard.

3rd Year Computer Science Student @ University of Edinburgh.

🧑‍💻[GITHUB](https://github.com/euanChalmers02)            🖥️[CV](https://euanchalmers.s3.eu-west-1.amazonaws.com/cv)                            🏢 [LINKEDIN](https://www.linkedin.com/in/euan-chalmers-3a10261b2/)

📝BLOG                ✉️Contact Me             🗣️[FEEDBACK](https://webpagebucket77.s3.eu-west-1.amazonaws.com/feedback.html)     

<aside>
💥 NEW: please check out my under development PintPrices web app (v0.1) [HERE](https://webpagebucket77.s3.eu-west-1.amazonaws.com/ReadMe)

</aside>

---

**Featured Projects:**

| Project | Progress | Languages & services used | Link |
| --- | --- | --- | --- |
| PintPrices |  | Python3, AWS lambda, AWS dynomodb AWS S3 |  |
| FDS packages |  | Python3 |  |
| RandomOrderGenerator |  | Python3 JSON |  |
| DatabaseGenerator |  | Python3 , Real , SQL |  |
| PropertyFinderLocal |  | Python3, Json/Java? |  |
| Java Logging |  | Java |  |

---

**Blog posts:**

| Title | Link |
| --- | --- |
| DBMS transactions | https://euanchalmers.s3.eu-west-1.amazonaws.com/blog/Transactions |
| Transaction → Drawing precedence graphs  | https://euanchalmers.s3.eu-west-1.amazonaws.com/blog/Drawing+Precedence+Graphs |
| Functional Dependencies | https://euanchalmers.s3.eu-west-1.amazonaws.com/blog/FunctionalDependencies |
| Databases Cheatsheet | https://euanchalmers.s3.eu-west-1.amazonaws.com/blog/DatabasesCheatsheet |
| Boolean Relational Calculus Query  | https://euanchalmers.s3.eu-west-1.amazonaws.com/blog/BooleanRelationalCalculusExample |
| Using Real - Relation algebra interpreter  | https://euanchalmers.s3.eu-west-1.amazonaws.com/blog/Using+Real+-+Relational+Algebra+Interpreter |
| …More to come…… |  |

---

### Current Personal Project Highlights

---

**Closest sausage roll web app:**

This uses my own J**son** dataset of Greggs locations to find the distance to your next sausage roll fix. It uses **AWS lambda** function to return a lnglat and square(1) value which is then used to find the distance to the nearest Greggs location from the dataset stored in **S3** bucket. This is then visualised using the **Mapbox** api (see below)
<img width="798" alt="Screenshot 2022-12-22 at 00 03 59" src="https://user-images.githubusercontent.com/113519226/209029902-2dbc145b-a905-4b7b-8288-1abb2b3762b3.png">
Further developments include adding a **python** generated **QR code** that will give a google maps route from your current position to the store. 

---

**Pint Price Finder Web App:**

Displays over 50,000 pubs across the uk along with their prices for popular drinks. The goal is to have users submit price updates for their local pubs. (NOTE: currently synthetic data). The system is built with using **javascript** to render the data that is stored in an **S3 bucket** with **aws lambda functions** used to create the dynamic html pages for both pub descriptions and update prices.(See below for some images)
<img width="1438" alt="Screenshot 2022-12-22 at 00 16 05" src="https://user-images.githubusercontent.com/113519226/209029891-96e4cb1d-ebe5-4a7b-a38f-ee6170212bc5.png">

Further developments including intergatrating my **drinks api(3)** to add relevant descriptions to each drink that displayed, further building on my **data driven design**. Additionally i will aim to improve the css and design of the pages. I will also be adding logging as i have sketched below.

---

**Drinks API:**

When building my pint price finder app (above) i can across a lack of any alcoholic drink apis, so to solve my lack of information i built my own. It contains > 3000 diffrent drinks ranging from wine to beer and spirts. You can use it to get descriptions and alcoholic percentages or use the RANDOM function to get a random drink. It was built using a simple **web scrapper** along with python to create the **python** files along with a simple **AWS lambda** function to act as the API and get the json file from my **S3 bucket**.

**[click here for your random drink](https://lg3gc7zrov3dqe5jsui4xuvgqe0lrujz.lambda-url.eu-west-1.on.aws/?drink=RANDOM)**

---

**Contact Me:**

euanbruce.chalmers@gmail.com
