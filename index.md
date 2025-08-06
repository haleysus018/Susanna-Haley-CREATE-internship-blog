---
layout: default
title: Summer 2025 CREATE internship program
---

* TOC
{:toc}

## About Me

My name is Susanna Haley, and I am a high school sophomore interning at the CREATE (Center for Research and Education on Accessible Technology and Experiences.) Lab through the YES2 internship program at the University of Washington. YES2 stands for Youth Employment Solutions 2. This program helps low vision and blind students ages 16 to 21 gain job experience and become more independent. It is the second program in a series of two.During my internship, I worked alongside two other YES2 interns, Mohammad and Kaleb. Together, we helped three PhD students with their research projects. I specifically worked with Brianna Wimer on the Flowcharts Project. This project aims to make flowcharts more accessible for individuals with low vision or blindness by extracting and converting the flowchart information—such as nodes and arrows—into a list format that can be more easily accessed.

<p style="text-align: center;">
  <img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/susanna_haley_profile_image.jpg" alt="Photo of Susanna Haley. She is wearing a white shirt. Has black hair. behind her is a white wall." width="400" height="500 text-align:center">
</p>


## Week 1

On the first day of my internship, I had the opportunity to meet my three mentors—Brianna, Adrian, and Carlos—in person at the CREATE Lab, located in the Bill and Melinda Gates Center for Computer Science & Engineering. The first week was an introductory week. It allowed us to get to know one another and to meet other PhD students and interns, such as Kajia, Kate, and Toby.
In the beginning, I started to learn Mermaid, a text-based tool used to create and visualize diagrams like flowcharts. Afterward, I transitioned to learning the basics of Flask, a lightweight Python framework for building web applications.
<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/CREATE_lab.jpg" alt="![person standing to the left and right. looking through glass to a lab. The lab has couch with blankets, wooden desks and a wooden table in the middle. Has advanced printing and other accessible technologies in the back." width="400" height="500 text-align: center;"></p>
## Week 2

I looked over 32 PDFs, including additional PDFs in the zip files, and extracted a total of 342 images that looked like flowcharts. I organized this data into a Google Sheet, documenting details such as file name, PDF name, and lecture name. Next, I applied inclusion and exclusion criteria to narrow down the number of flowcharts that met the definition for the project. The inclusion criteria required flowcharts to have at least two nodes within a shape and at least one edge. The exclusion criteria eliminated flowcharts that were not in English, lacked visual clarity, or were duplicates.

<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/pdfs.png" alt="example of google drive with pdf's in them" width="600" height="400 text-align: center;">
</p>


## Week 3
I began learning how to use OpenAI’s API to automatically generate Mermaid code for the flowchart images, which would then allow me to visualize them more efficiently. OpenAI’s API (Application Programming Interface) is a tool that lets developers connect their code to OpenAI’s AI models. However, as I continued applying the inclusion and exclusion criteria, I began to struggle with recognizing which images were true flowcharts and which were not. Some images labeled as flowcharts did not meet the definition or characteristics of a flowchart, leading to confusion. To fix this, I revisited the images and created Mermaid code for each one to confirm that it was indeed a flowchart. This process helped me ensure accuracy but was time-consuming and required careful attention to detail. So i had to stop the OpenAi project I was doing. 
<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/criteriaattemp.png" alt="example of her inclusion exclusion criteria Susanna attempted" width="500" height="400 text-align:center"></p>



## Week 4
I further explored APIs and learned how to use ChatGPT-4o’s API. Chatgpt-4o is a different large language model version. I learned how to generate content based on prompts to Chatgpt4o. I began by having the AI generate random flowcharts. Then, I developed a program where users could input the number of nodes and edges, as well as the topic of the flowchart. The program has two buttons: "Generate Flowchart," which automatically produces the flowchart as an SVG image using AI, and "Handdrawn," which provides a list of nodes and descriptions, allowing users to manually assign node positions. SVG files, or Scalable Vector Graphics, are primarily used for creating and displaying two-dimensional graphics, especially on websites This feature helps include hand-drawn flowcharts into our dataset. Additionally, I collected statistics on the flowcharts, including the number of nodes, edges, and the variety of shapes used. I categorized these measurements into groups of fewer than 10 , between 10 and 19, and 20 or more nodes and edges.

<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/mermaidgenerator.png" alt="shows her example website of the mermaid generator she created. there are 3 input boxes where you put in the topic of the flowchart generated, amount of nodes and edges. There are two buttons generate flowchart and handdrawn flowchart. There is a textarea box, where the output will go if you push handdrawn flowchart." width="500" height="400 text-align:center">
</p>

## Struggles
I had a hard time slowing down and taking my time. I usually like to work quickly, but I learned that in research, accuracy matters most. Sometimes, I didn’t really understand the bigger purpose of what I was working on, so I wasn’t sure if I wanted to keep going. I also found it tough to decide which images were actually flowcharts, especially when it came to the “clarity” part of the exclusion criteria because I wasn’t sure what counted as clear or not, so I needed to go back and redo a lot of my work, which was disappointing. Using the API was also sometimes frustrating because sometimes my prompts for the OpenAI API didn’t work well, and that made things harder.

## What I learned
During this internship, I learned enough Mermaid to create flowcharts. I also started to learn a bit of Flask and set up my computer as the server for my Flask program. Additionally, I learned more about APIs and some basic prompt engineering-a specific way to write a prompt to get the LLM to produce a specific output- to get the LLM to give me the specific output I was looking for so that I could render it in the HTML file. HTML is markup code to structure the content on a webpage. I also gained a deeper understanding of accessibility technology—such as the Monarch—and the ideas within this community, as well as what research might be like for me if I decide to pursue that path. The monarch is a multiline refreshable braille display  and graphics developed by American Printing House for the Blind. Finally, I learned a little bit of pandas-a lightweight python framework to work with data in files- to work with Excel sheets and gather statistics from them instead of doing it manually. This week, Week 5, I learned about how to deploy a simple website using services like pythonanywhere. After it has generated the flowchart as an SVG then it will insert the mermaid code it used to render it as an svg and put it into a read only box.  I also learned more about file handling and how to use regexp to find things. 

## Mad libs generator tool
You enter how many edges and nodes you want for your flowchart, plus a short description of what the flowchart should show. Then you click either the "Generate Flowchart" button or the "Hand Drawn" button. The "Generate Flowchart" button asks OpenAI's API to create mermaid code based on your inputs. This code appears in a text box where you can edit it if you want. Then you click "Render Mermaid Diagram" to turn that code into an SVG image shown on the page. The "Hand Drawn" button asks OpenAI to create a list of nodes and edges with properties, which you can use to decide how to position them, shown in a read-only box. 

[mad libs generator tool](https://haleysus018.pythonanywhere.com/)
<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/Screenshot 2025-08-05 153102.png" alt="shows an example of her mermaid mad libs generator tool. There are three text boxes for topic,nodes and edges. then there is a blue generat flowchart and then to the right of that the green handdrawn button. There is a place where it the AI hands back the mermaid code and then below that a green render mermaid diagram button ." width="500" height="400 text-align:center">
</p>
## How I built this
I built three input areas where the user can enter the node, description, and number of edges. Then, I created multiple routes. Routes define the URL path and specify what the server should do when someone visits that path. Each route corresponds to an action triggered by a button press. For example, the "generate flowchart" route is triggered when the user presses the "Generate Flowchart" button. This route sends a prompt to OpenAI to create Mermaid code without any markdown or formatting that could prevent it from rendering on the webpage. Then, it sends that Mermaid code back as a JSON object into a textarea on the HTML page. The user can edit the code if desired and then press the "Render Diagram" button, which renders the Mermaid code in that textarea as an SVG image and inserts it into a designated part of the HTML page.

If the user presses the "Handdrawn" button, it triggers the "handdrawn" route. This route prompts the OpenAI API to generate a list of nodes and their properties and edges and their properties. The result is displayed in a box on the HTML page where the user cannot edit it but can view it. This allows the user to decide the positioning of the nodes and edges manually.

## Diagram generator
You type valid mermaid code in a text box. For example, it starts with "graph direction_of_flowchart" followed by the nodes and their connections. After typing your code, you click the submit button, and the page renders your mermaid code as a flowchart diagram in SVG format. If the code is invalid, it will show an error.

<a href="mermaid_generator.html">Open Mermaid Generator</a>
<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/Screenshot 2025-08-05 154602.png" alt="Shows an example of her mermaid generator. There is a textarea where the user writes in their mermaid code then you push the green submit button and there is a purple toggle dark mode button. The flowchart will then appear in an area on the page below those two buttons." width="500" height="400 text-align:center">
</p>
## how I built this
I created a textarea in the webpage where users can enter their mermaid code. The code is saved in a variable and passed to a function that uses mermaid's API render function. This function turns the mermaid code into an SVG diagram. The SVG is then inserted into a specific part of the HTML page for display. If the code isn't valid mermaid syntax, an error is shown.

## Natural language generator of flowchart
This website is a simple static site without any backend programming. If deployed with a backend like Flask, it could work fully. Right now, it doesn't because the backend part is missing.

If it worked fully, you would type in plain, natural language describing how you want a flowchart to look—what nodes it should have, their shapes, where the arrows (edges) point, etc. Then the site would send this description to the OpenAI API, which would generate Mermaid code (a text format for diagrams) based only on your description. That Mermaid code would be used to create and display the flowchart as an SVG image on the page.
<a href="natural_langauge_mermaid_generator.html">convert natural language to mermaid flowchart</a>

<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/Screenshot (1972).PNG" alt="There is a text area where the user puts in their description of their desired flowchart and then there is a part of the website where the mermaid flowchart will appear when you push the generate flowchart button. The generate flowchart button is pink and the toggle mode button is purple. the genereated flowchart will appear below these two buttons in a designated area. 
  " width="500" height="400 text-align:center">
</p>
## how I built this
I had an app.py,index.html and style.css files. I had a textarea where the user types in their description. I then send it to OpenAi API and prompt it to give me back mermaid code that matches the users description. It gives me back mermaid code. Then i parse that mermaid code from json-simple text format that all coding languages and servers can read and easily be parsed-into a javascript object. I then put that javascript object into a function I created that uses mermaid's render function to render the mermaid code that was passed and then insert it into the html page in a specific part of the html page. 
## Mermaid website
If you need the mermaid live ediotr or the mermaid documenattion look at this website:[Mermaid main website](https://mermaid.js.org/)

## my final dataset along with alt text note the rendered svg files look differenet from the original ones

<a href="alt_text_dataset.html">Alt text flowchart dataset</a>

## How I built this 




