# To the Power of Math!

A simple web application that calculates the result of a base number raised to the power of an exponent. The app uses AWS services like Lambda, API Gateway, DynamoDB, and is hosted via AWS Amplify.

## Features
- Input base and exponent to calculate power.
- Uses AWS Lambda to compute results.
- Stores calculation history in DynamoDB.
- Hosted on AWS Amplify.

## Technologies
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: AWS Lambda, API Gateway
- **Database**: AWS DynamoDB
- **Hosting**: AWS Amplify

## Setup

1. **Clone the repo**:
    ```bash
    git clone https://github.com/your-username/serverless-webapplication.git
    ```

2. **Deploy Frontend**:
    - Go to **AWS Amplify Console** and upload your `index.html` and other files.
    - After deployment, get the URL to access the app.

3. **API Gateway & Lambda**:
    - Link API Gateway to Lambda function for calculation.
    - Update the `callAPI` function in the frontend with the API Gateway URL.

4. **DynamoDB**:
    - Set up a table called `PowerOfMathDatabase` with `ID` as the partition key.

![Screenshot 2025-04-27 171747](https://github.com/user-attachments/assets/2cbb67e4-9f67-4006-b2a3-a0cd50cde990)


## License
MIT License
