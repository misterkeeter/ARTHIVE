
# ArtHive

ArtHive is an open-source Content Management System (CMS) designed specifically for artists, with a focus on creating a living archive of all the ephemera around their shows. It enables artists to upload and tag photos, texts, and videos, and use those tags to populate and organize content for easy exploration.

## Project Goals
ArtHive is built with the intention of providing artists with an intuitive, flexible platform to document and showcase the full breadth of their work and creative processes. The CMS emphasizes the importance of tags, allowing artists and audiences to "rabbit hole" through related pieces and collections seamlessly.

## Key Features
- **Media Upload and Tagging**: Artists can upload photos, videos, and text entries, applying tags to each item to facilitate organization and browsing.
- **Tag-Based Navigation**: ArtHive’s design allows for easy exploration based on tags, enabling a dynamic, interconnected archive.
- **Collaborative Access**: Artists can add collaborators or guest users, making it a flexible tool for project teams.
- **Responsive, Artist-Friendly UI**: Using Vue.js and Vuetify, ArtHive offers a polished, accessible interface that is mobile-first in design.

## Tech Stack
- **Backend**: Flask with Firebase for data storage and authentication
- **Frontend**: Vue.js and Vuetify for the UI, enabling a consistent and responsive user experience
- **Deployment**: Considered platforms include Netlify or Render for efficient and scalable hosting

## Getting Started
To set up ArtHive on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/arthive.git
   cd arthive
   ```

2. **Install Backend Dependencies**:
   Make sure you have Python and Flask installed.
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Firebase**:
   - Create a Firebase project and configure Firebase authentication and storage.
   - Add your Firebase configuration file to the backend.

4. **Install Frontend Dependencies**:
   Navigate to the frontend directory and install Vue and Vuetify dependencies.
   ```bash
   npm install
   ```

5. **Run the Application**:
   - Start the Flask server for the backend.
   - Start the Vue.js frontend server.

## Contributing
ArtHive is open-source and welcomes contributions from developers, artists, and anyone interested in creating new ways to archive and showcase artistic work.

---

*Created by [Your Name]*
