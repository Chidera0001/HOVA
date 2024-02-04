Flutter Mobile App - Technical Assessment
Overview:
This Flutter mobile app was developed as part of the technical assessment for the Junior Flutter Developer position at HOVA AI. The primary goal of the project was to implement a responsive screen based on the provided UI design and integrate a mock JSON REST API response from MockAPI.

Project Structure:
The project follows a well-organized structure to enhance maintainability and readability. Key directories include:

lib: Contains the main Dart code for the application.
assets: Houses any static assets used in the app, such as images or custom fonts.
Installation:

To run the application, follow these steps:
Clone the repository:
git clone [repository-url]

Navigate to the project directory:
cd HOVA

Install dependencies:
flutter pub get

Run the app:
flutter run

Ensure you have Flutter and Dart installed on your system.

Implementation Details:
The responsive screen was implemented using Flutter, focusing on an effective project structure and widget hierarchy. Key decisions include:
Widget Choices: Utilized Flutter's responsive widgets such as LayoutBuilder and MediaQuery to ensure adaptability across different devices.
State Management: Employed Provider for efficient state management, enhancing the app's scalability.

API Integration:
The app seamlessly integrates a mock JSON REST API response from MockAPI. This demonstrates proficiency in handling data within a Flutter application. A snippet of the integration is shown below
// Example code snippet for API integration
Future<void> fetchData() async {
final response = await http.get('https://api.mockapi.io/data');

if (response.statusCode == 200) {
// Handle and process the JSON data here
} else {
// Handle error cases
}
}

Deployment (Bonus Opportunity):
As a bonus, the app has been successfully deployed. The deployment process involved:
Using firebase, I successfully deployed the app, below are some of the deployment details.
Project Console: https://console.firebase.google.com/project/hova-4d9e9/overview
Hosting URL: https://hova-4d9e9.web.app

Conclusion:
This technical assessment provided an opportunity to showcase skills in Flutter development, project structuring, and API integration. Challenges were met with innovative solutions, contributing to a valuable learning experience. Given more time, enhancements could be made in terms of UI polish and additional features.

Thank you for the opportunity to participate in this assessment.

Best regards,
Chidera Anele,
c.anele@alustudent.com
