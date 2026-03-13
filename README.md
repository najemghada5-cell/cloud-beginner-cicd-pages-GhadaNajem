# Cloud Computing - CI/CD Assignment
**Name:** Ghada Mahmoud Najem  
**Course:** Cloud Computing  
**Instructor:** Dr. Faten F Abushmmala  

## Project Description
[span_2](start_span)This project demonstrates a simple **CI/CD (Continuous Integration and Continuous Deployment)** pipeline[span_2](end_span). [span_3](start_span)[span_4](start_span)It uses **GitHub Actions** to automate the build and deployment of a static website to **GitHub Pages**[span_3](end_span)[span_4](end_span).

## Live Website
Once the deployment is successful, you can visit the site here:
[span_5](start_span)[span_6](start_span)👉 **[رابط موقعك هنا بعد النشر]**[span_5](end_span)[span_6](end_span)

## Project Files
* [span_7](start_span)`index.html`: Contains the website content, including my name and CI/CD explanations[span_7](end_span).
* [span_8](start_span)[span_9](start_span)`style.css`: Provides the visual styling (including Dark Mode)[span_8](end_span)[span_9](end_span).
* [span_10](start_span)[span_11](start_span)[span_12](start_span)`script.js`: Includes an interactive JavaScript feature[span_10](end_span)[span_11](end_span)[span_12](end_span).
* [span_13](start_span)`.github/workflows/deploy.yml`: The automation file that manages the pipeline[span_13](end_span).

## How to Open Locally
1. [span_14](start_span)Download or clone this repository[span_14](end_span).
2. [span_15](start_span)Open the `index.html` file in any modern web browser[span_15](end_span).

## My Pipeline Flow
[span_16](start_span)[span_17](start_span)Whenever I push a change to the **main branch**, GitHub Actions automatically triggers the `deploy.yml` workflow[span_16](end_span)[span_17](end_span). 
1. **[span_18](start_span)Build Job**: It checks for the existence of required files[span_18](end_span).
2. **[span_19](start_span)Deploy Job**: It uploads the site files and publishes them to GitHub Pages[span_19](end_span).
٣.