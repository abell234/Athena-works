# Athena-works
[![Athena Award Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Faward.athena.hackclub.com%2Fapi%2Fbadge)](https://award.athena.hackclub.com?utm_source=readme)


❤️ This Heart Disease Risk Checker is a simple, interactive website that helps users estimate their heart disease risk based on everyday life factors and health history. With a quick questionnaire, users instantly see their risk level (Low, Medium, or High), a visual progress bar, and personalized tips for heart health.

Why did I make this?
I built this as my capstone project for Kode With Klossy, but I’ve completely restructured both the code structure and the user experience.
Heart disease is the world’s leading cause of death, but many people don’t know their own risk. I wanted to create a tool that makes it easy and accessible for anyone to check and reflect on their heart health in just a couple of minutes.

How did I make it?
Frontend only: Written in HTML, CSS, and JavaScript no backend was required.
Questionnaire form: The HTML presents all the questions (age, sex, family history, lifestyle habits, medical history).

Scoring logic: JavaScript receives the user’s responses and uses simple functions to assign each answer a risk score.

Calculations: risk score is the sum of points from each answer. The higher risk answers (like not exercising or smoking) adds more points to your score.

The total score assigns a risk category: Low (≤10), Medium (11–20), High (21+).
Results display after submitting the form, scores are shown along with a risk badge (in color), a progress bar, and custom tips based on answers.
The styling uses warm reds and pinks, a beating heart animation, and a layout designed for clarity.

What I struggled with & what I learned
I struggled with understanding how to combine all questionnaire answers into a fair scoring system (balancing “risk points” for different behaviors took some trial and error) based on the CDC and AHA guidelines. Also, making the results section update smoothly without reloading the page, and keeping everything visually clear this took me a while to figure out. My biggest struggle was with debugging to make sure all input was validated, results didn’t show twice, and tips were relevant for everyone.

What I learned: I learned how to break big problems down into manageable code pieces. Also, clarity of clean UI/UX for health questionnaires that have to be based on trusted information. I also gained a deeper confidence in JavaScript. By working with forms, dynamic content, and conditional statements, and the importance of constructive feedback and my own creative decisions in making the project.

Code Overview:
Form handling: The JavaScript processes each answer on submit, prevents page reload, and updates the result display.

Scoring functions: Each of the factors (age, exercise, etc.) has its own function for assigning points.

Result logic: adds the points, then sets the progress bar color, and prints the advice with tips based on the user's answers.

Health resources used:
CDC – Heart Disease Information

American Heart Association – Heart Disease & Stroke 2025

Better Health Channel – Diet Factors

CDC – Sleep and Heart Health

AHA – Heart/Kidney Connection

Disclaimer
This tool is for educational purposes only and not a substitute for medical advice. Please contact a health professional with any concerns.

Thanks for reading! If you have suggestions, feel free to open an issue or fork the project. ❤️
