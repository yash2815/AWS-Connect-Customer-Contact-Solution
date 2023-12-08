# AWS Connect Customer Contact Solution

This project showcases the development and implementation of an end-to-end customer contact solution using AWS Connect, featuring an integrated Amazon Lex bot within the IVR (Interactive Voice Response) flow. The solution leverages various AWS services to enhance customer interactions and operational efficiency.

## Project Overview

- **Objective:** Develop a comprehensive customer contact solution on AWS Connect integrating Amazon Lex for interactive bot interactions.
- **Technologies Used:** AWS Connect, Polly Text-to-Speech, SSML, Amazon Lex.
- **Features:** Customized queues, routing profiles, personalized contact flows, Amazon Lex bot integration.

## Project Details

### Features Implemented

- **Amazon Lex Integration:**
  - Integrated Amazon Lex bot into the IVR flow to facilitate interactive customer interactions and automated responses.
    
- **Polly Text-to-Speech (TTS) with SSML:**
  - Leveraged Polly's TTS service with SSML for personalized prompts with tags like emphasis and prosody, enhancing customer interactions.

- **Customized Queues and Routing Profiles:**
  - Configured tailored queues and routing profiles to efficiently manage incoming customer contacts based on priorities and agent skills.

- **Personalized Contact Flow:**
  - Developed a customized contact flow linked to a Direct Inward Dialing (DID) number, providing a seamless customer experience.


## How to Use

- **Setup Instructions:** 
  - Log in to your AWS Management Console and access AWS Connect.
  - Create and configure queues, routing profiles, and contact flows based on the provided configuration files.
  - Polly Integration: Integrate Polly's Text-to-Speech service into your AWS Connect instance to utilize personalized prompts with emphasis and prosody.
  - Integrate the created Amazon Lex bot within the IVR flow in your AWS Connect instance.
  - Testing and Validation: Test the contact solution by simulating incoming contacts and verifying the functionality of queues, routing, and contact flows.
  
- **Prerequisites:**
  - AWS Account: Access to an AWS account with permissions to create and configure AWS Connect instances.
  - Access to AWS Services: Ensure access to AWS services such as Polly, IAM, and other necessary services used in this solution.
  - AWS Connect Instance: Create an AWS Connect instance to configure queues, routing profiles, and contact flows.
  - Polly Text-to-Speech Service: Enable access to the Polly Text-to-Speech service for personalized prompts.
  - Amazon Lex Bot: Create an Amazon Lex bot with appropriate intents and slots tailored for customer interactions.

## Screenshots

Screenshots uploaded in the screenshots folder.

## Conclusion

This project demonstrates the successful implementation of a customer contact solution on AWS Connect, highlighting personalized customer interactions and operational efficiency improvements.

