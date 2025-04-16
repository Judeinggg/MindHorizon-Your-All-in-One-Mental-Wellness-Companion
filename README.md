# Zenjott-Your-All-in-One-Mental-Wellness-Companion


## Overview
zenjott is a web application designed to support users in tracking their mental well-being, providing a platform for self-reflection, and offering a community, resources, and tips for mental health improvement.

## Key Features
### Mood Tracking
- Users can log their daily moods using emoticons.
- The app allows users to record specific emotions or add notes to capture contextual details.

### Journal Entries
- Users can write daily journal entries to express their thoughts, feelings, and experiences.

### Mental Health Resources
- The app provides curated mental health resources, articles, and educational content.
- Resources cover stress management, mindfulness, and coping strategies.

### Tips and Suggestions
- Personalized tips and suggestions are offered based on users' mood patterns and journal content.

### Memes Collections
- There is a collection of memes where users can view as many memes as possible to lift their spirits.

### Graphical Analytics
- Visual representation of mood trends over time through a pie chart.
- Analytics can help users and mental health professionals gain insights into patterns and trends.

### Community Support
- Integration of a community feature where users can share insights or tips.
- A supportive and positive community environment fosters a sense of connection and understanding.

### Security and Privacy
- Prioritizes user privacy and data security, ensuring that journal entries and personal information are securely stored and accessible only to the user.
- Implementation of Django Authentication sign-in for enhanced security.

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Django
- Database: PostgreSQL
- Authentication: Django Authentication

#### New Features:

1. **Prevention of Cyberbullying and Hate Speech**:
   - Users must now accept terms and conditions on good conduct before joining the community.
   - Implemented a pre-trained hate speech detection model from Hugging Face Transformers to automatically identify and take down posts containing hate speech.
   - Added a feature for users to report offensive posts and comments, enabling the community to self-regulate and maintain a supportive environment.

2. **User Anonymity**:
   - Users can now choose between being anonymous or being known at any time.
   - The ability to toggle between anonymity and visibility provides flexibility and empowers users to engage in discussions comfortably.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for new features, improvements, or bug fixes.
