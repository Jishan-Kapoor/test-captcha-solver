# Captcha Solver Web Application

## Summary
This static web application allows users to solve captchas by providing an image URL as a query parameter. By default, it handles the sample image provided.

## Setup
To deploy this application on GitHub Pages, follow these steps:
1. Fork the repository to your GitHub account.
2. Go to the Settings of your forked repository.
3. Scroll down to the GitHub Pages section and select the branch to deploy from (e.g., main).
4. Access the deployed application at `https://yourgithubusername.github.io/captcha-solver/?url=sample.png`.

## Usage
- Access the page by opening the deployed URL and appending `?url=url_of_captcha_image.png`.
- Query parameters: 
  - `url`: The URL of the captcha image to be solved.
- Key features:
  - **Automatic solver**: The web app automatically processes the provided captcha image.
  - **Image preview**: Displays the captcha image for verification.

## Code Explanation
This web application is built using HTML and JavaScript. It utilizes the provided URL of the captcha image in the query parameter to solve the captcha. The key logic revolves around processing the image and finding the necessary solution.

Key libraries: None used.

## License
This project is licensed under the MIT License.