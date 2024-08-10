# Finding-Missing-Person-Using-AI

Hundreds of people, especially children, go missing every day in India. There are various NGOs and government initiatives to help with this issue. This project tries to implement an existing or new way to assist in locating missing persons.

## Objective
The objective of this project is to help police and higher authorities to track down missing people quickly. The usual process to track a person involves an investigation, which requires time and experience to ask the right questions. While investigation methods are generally effective, they can be time-consuming and may fail if the missing person has been moved to a different location.

In such cases, the ideal approach is to review CCTV footage and other evidence, which can also be very time-consuming. Given the number of people who go missing every day, it can be a challenge to keep up with these cases.

## Solution
### Registering New Cases
The first step is to register a new case. The GUI application, built using PyQT5, allows to collect all relevant information and store it in a PostgreSQL database.

### Waiting for Users to Submit Images
Common people, who want to make a change in society, can use a mobile application to submit photos of people they believe are missing or found begging, while keeping their identity anonymous. The anonymity is crucial due to the fear of local troublemakers.

### Matching Cases
The next step is to match the case images with user-submitted images using the KNN algorithm.

Once done, you'll have to click on the Refresh button to train the KNN model and then on Match to start matching images.

### What is Left?
 Login (Authentication)
 Submit new case
 Mobile Application (to submit user photos)
 View submitted cases
 View confirmed cases
 Unit tests

 
### Reference
Gagandeep Singh


