---
layout: default
title: Summer 2025 CREATE internship program
---

* TOC
{:toc}

## About Me

My name is Susanna Haley, and I am a high school sophomore interning at the CREATE (Center for Research and Education on Accessible Technology and Experiences.) Lab through the YES2 internship program at the University of Washington. YES2 stands for Youth Employment Solutions 2. This program helps low vision and blind students ages 16 to 21 gain job experience and become more independent. It is the second program in a series of two.During my internship, I worked alongside two other YES2 interns, Mohammad and Kaleb. Together, we helped three PhD students with their research projects. I specifically worked with Brianna Wimer on the Flowcharts Project. This project aims to make flowcharts more accessible for individuals with low vision or blindness by extracting and converting the flowchart information—such as nodes and arrows—into a list format that can be more easily accessed.

<p style="text-align: center;">
  <img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/susanna_haley_profile_image.jpg" alt="Photo of Susanna Haley. She is wearing a white shirt. Has black hair. behind her is a white wall." width="400" height="400 text-align:center">
</p>


## Week 1

On the first day of my internship, I had the opportunity to meet my three mentors—Brianna, Adrian, and Carlos—in person at the CREATE Lab, located in the Bill and Melinda Gates Center for Computer Science & Engineering. The first week was an introductory week. It allowed us to get to know one another and to meet other PhD students and interns, such as Kajia, Kate, and Toby.
In the beginning, I started to learn Mermaid, a text-based tool used to create and visualize diagrams like flowcharts. Afterward, I transitioned to learning the basics of Flask, a lightweight Python framework for building web applications.
<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/CREATE_lab.jpg" alt="![person standing to the left and right. looking through glass to a lab. The lab has couch with blankets, wooden desks and a wooden table in the middle. Has advanced printing and other accessible technologies in the back." width="400" height="400 text-align: center;"></p>
## Week 2

I looked over 32 PDFs, including additional PDFs in the zip files, and extracted a total of 342 images that looked like flowcharts. I organized this data into a Google Sheet, documenting details such as file name, PDF name, and lecture name. Next, I applied inclusion and exclusion criteria to narrow down the number of flowcharts that met the definition for the project. The inclusion criteria required flowcharts to have at least two nodes within a shape and at least one edge. The exclusion criteria eliminated flowcharts that were not in English, lacked visual clarity, or were duplicates.

<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/pdfs.png" alt="example of google drive with pdf's in them" width="400" height="400 text-align: center;">
</p>


## Week 3
I began learning how to use OpenAI’s API to automatically generate Mermaid code for the flowchart images, which would then allow me to visualize them more efficiently. OpenAI’s API (Application Programming Interface) is a tool that lets developers connect their code to OpenAI’s AI models. However, as I continued applying the inclusion and exclusion criteria, I began to struggle with recognizing which images were true flowcharts and which were not. Some images labeled as flowcharts did not meet the definition or characteristics of a flowchart, leading to confusion. To fix this, I revisited the images and created Mermaid code for each one to confirm that it was indeed a flowchart. This process helped me ensure accuracy but was time-consuming and required careful attention to detail. So i had to stop the OpenAi project I was doing. 
<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/criteriaattemp.png" alt="example of her inclusion exclusion criteria Susanna attempted" width="400" height="400 text-align:center"></p>



## Week 4
I further explored APIs and learned how to use ChatGPT-4o’s API. Chatgpt-4o is a different large language model version. I learned how to generate content based on prompts to Chatgpt4o. I began by having the AI generate random flowcharts. Then, I developed a program where users could input the number of nodes and edges, as well as the topic of the flowchart. The program has two buttons: "Generate Flowchart," which automatically produces the flowchart as an SVG image using AI, and "Handdrawn," which provides a list of nodes and descriptions, allowing users to manually assign node positions. SVG files, or Scalable Vector Graphics, are primarily used for creating and displaying two-dimensional graphics, especially on websites This feature helps include hand-drawn flowcharts into our dataset. Additionally, I collected statistics on the flowcharts, including the number of nodes, edges, and the variety of shapes used. I categorized these measurements into groups of fewer than 10 , between 10 and 19, and 20 or more nodes and edges.

<p style="text-align: center;">
<img src="https://raw.githubusercontent.com/haleysus018/Susanna-Haley-CREATE-internship-blog/master/images/mermaidgenerator.png" alt="shows her example website of the mermaid generator she created. there are 3 input boxes where you put in the topic of the flowchart generated, amount of nodes and edges. There are two buttons generate flowchart and handdrawn flowchart. There is a textarea box, where the output will go if you push handdrawn flowchart." width="400" height="400 text-align:center">
</p>

## Struggles
I had a hard time slowing down and taking my time. I usually like to work quickly, but I learned that in research, accuracy matters most. Sometimes, I didn’t really understand the bigger purpose of what I was working on, so I wasn’t sure if I wanted to keep going. I also found it tough to decide which images were actually flowcharts, especially when it came to the “clarity” part of the exclusion criteria because I wasn’t sure what counted as clear or not, so I needed to go back and redo a lot of my work, which was disappointing. Using the API was also sometimes frustrating because sometimes my prompts for the OpenAI API didn’t work well, and that made things harder.

## What I learned
During this internship, I learned enough Mermaid to create flowcharts. I also started to learn a bit of Flask and set up my computer as the server for my Flask program. Additionally, I learned more about APIs and some basic prompt engineering-a specific way to write a prompt to get the LLM to produce a specific output- to get the LLM to give me the specific output I was looking for so that I could render it in the HTML file. HTML is markup code to structure the content on a webpage. I also gained a deeper understanding of accessibility technology—such as the Monarch—and the ideas within this community, as well as what research might be like for me if I decide to pursue that path. The monarch is a multiline refreshable braille display  and graphics developed by American Printing House for the Blind. Finally, I learned a little bit of pandas-a lightweight python framework to work with data in files- to work with Excel sheets and gather statistics from them instead of doing it manually. This week, Week 5, I learned about how to deploy a simple website using services like pythonanywhere.

[flowchart generator tool](https://haleysus018.pythonanywhere.com/)
[Mermaid main website](https://mermaid.js.org/)


