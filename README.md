# InterviewInSync

##### Deployed Link: http://tgs-hackathon.s3-website.ap-south-1.amazonaws.com/
 
## Project Overview

InterviewInSync is an interview scheduling application that simplifies the interview process for HR professionals, candidates, and interviewers. The application is built with a modern tech stack, including React for the frontend, Zustand for state management, AWS DynamoDB and Lambda for the backend, AWS API Gateway for API management, CloudWatch for monitoring, and Code Pipeline for continuous deployment.

## Modules & Routes

`/schedule-interview`
`/application-status` 
`/upload-documents` 
`/interviewer-panel`

The application consists of Candidate Module onnly:

### Candidate Module

The Candidate module is tailored for job applicants and provides them with the following features:

- Schedule interviews based on available slots.
- View the status and details of their interviews.
- Upload and manage their resume and other application materials.

## Tech Stack

The InterviewInSync application leverages the following technologies:

### Frontend

- **React**: A popular JavaScript library for building user interfaces.
- **Zustand**: A state management library for managing application state.
- **Zustand Query**: Zustand query to fetch API.
  
### Backend

- **AWS DynamoDB**: A fully managed NoSQL database service by Amazon Web Services.
- **AWS Lambda**: A serverless computing service that executes code in response to events.
- **AWS API Gateway**: A managed service that enables developers to create, publish, and manage APIs.
- **CloudWatch**: Amazon's monitoring and observability service for tracking application performance and logs.
- **AWS SES**: Amazon's SES service to send email as per requirement.

### Deployment

- **Code Pipeline**: A continuous integration and continuous deployment (CI/CD) service provided by AWS.
- **Amazon S3**: A scalable object storage service for hosting static assets and artifacts.

## Getting Started

To get started with InterviewInSync, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `yarn`.
3. Runs the app locally using `yarn start` in terminal, open `http://localhost:3000` to view it in your browser.
4. Access the application through the provided URL.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please contact our team at [team@interviewinsync.com](mailto: dhruv@thegeeksquad.com, kartik@thegeeksquad.tech).

Thank you for choosing InterviewInSync for your interview scheduling needs! We hope it simplifies and streamlines your hiring process.
