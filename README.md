# Cloud Resume Challenge

## Resume in HTML, CSS, and JS
The resume itself uses the resume template designed and developed by [stypr resume-template](https://github.com/stypr/resume-template) who was in turn inspired by [AwesomeCV](https://github.com/posquit0/Awesome-CV).

My resume is hosted on S3, served by CloudFront, and utilizes JS, Lambda functions and DynamoDB for keeping track of visitor count. The page view counter is in the footer.

I used Jake Jarvis's GitHub Action to sync my S3 bucket to this repo so any changes I make here propagate to S3.

![alt text](/Diagram.jpg?raw=true "Diagram")

## Example

https://sefielbaz.com

[https://jselbaz.github.io/resume-template/](https://jselbaz.github.io/resume-template/resume/) (page visit counter disabled due to CORS settings)
