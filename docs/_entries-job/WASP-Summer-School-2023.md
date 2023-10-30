---
layout: base-entry
company: "WARA Media & Language"
project: "WASP Summer School 2023"
location: "Norrköping, Sweden (Remote)"
employment: "freelance"
positions:
    - full stack developer
    - research engineer
    - teaching
    - cinematic creator
technologies:
    - Python (Uvicorn, FastAPI, Celery)
    - Docker
    - HTML
    - CSS
    - Javascript
    - Unreal Engine 4.27
    - Git
    - SSH
start: "01-06-2023"
end: "01-09-2023"
---

## About
The [WASP Summer School Synthesis of Human Communication 2023](https://internal.wasp-sweden.org/event/wasp-summer-school-synthesis-of-human-communication-2023/) was a networking event organized by [Wallenberg AI, Autonomous Systems and Software Program](https://wasp-sweden.org/). It took place in Norrköping, Sweden, between 21-Aug-2022 and 25-Aug-2022.

Speakers from industrial and academic backgrounds were invited to present their work to attendees, while PhD students were tasked with completing an assignment on the topic of generative AI, to earn credits towards their degrees.

The summer school was rounded off in the [Norrköping Visualisation Center](https://visualiseringscenter.se/en) 3D dome, in which [3D video demos](https://youtube.com/playlist?list=PLIg3Fnk71bdlQlrX4EucgoRc3J5JjKhzP&si=To6hrlftbgQJDcMM) showcasing the students' submissions were presented.

---

## Responsibilities
Teaching & Organization:
- Write a technical [gesture generation tutorial](https://github.com/TeoNikolov/wasp-ss2023-gesgen/blob/main/tutorial.md) with student exercises.
- Give a technical presentation on the PhD student assignment.
- Present a tutorial on mapping speech audio to gestures.
- Mentor students during the completion of their assignment.
- Organize and coordinate the collection of assignment submissions.
- Plan the testing of hardware and software in the [Norrköping Visualisation Center](https://visualiseringscenter.se/en) 3D dome.
- Formulate technical and organizational questions for collecting student feedback.

Technical:
- Develop a complete [web application](https://github.com/TeoNikolov/wasp-ss2023-gesgen) with a browser front-end and **Python** back-end.
  - **Celery** for task scheduling.
  - **FastAPI** for exposing a REST API over HTTP.
  - **Uvicorn** for launching a web server.
  - **Javascript** for handling API communication and front-end updates.
  - **CSS** and **HTML** for front-end design.
  - **Docker** (compose) for decoupling [app modules](https://github.com/TeoNikolov/wasp-ss2023-gesgen/tree/main#build-the-docker-images) and managing deployment.
  - **Git** for version control ([repo link](https://github.com/TeoNikolov/wasp-ss2023-gesgen)).
- Deploy the web application on 2 remote **Linux** servers using **Docker**.
- Monitor web server resources over **SSH**.
- Monitor and ensure web application availability over **SSH**.
- Use **Blender** with **Python** scripts to visualize **BVH** data and convert it to **FBX**.
- Produce [5 cinematics](https://youtube.com/playlist?list=PLIg3Fnk71bdlQlrX4EucgoRc3J5JjKhzP&si=To6hrlftbgQJDcMM) in **Unreal Engine 4.27** from **FBX** data, in collaboration with [Mihail Tsakov](https://www.linkedin.com/in/mihailtsakov/).
- Build an **nDisplay** project (UE4.27) and test it in the [Norrköping Visualisation Center](https://visualiseringscenter.se/en) 3D dome.
- Maintain a [**Git** repository](https://github.com/Svito-zar/wasp-2023-summer-school) with instructions for the student assignment. 

For technical details, check the [gesgen web application](https://github.com/TeoNikolov/wasp-ss2023-gesgen/) Git repo.
