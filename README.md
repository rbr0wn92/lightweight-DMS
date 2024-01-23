# Document Management System (DMS)

## Overview
Document Management System (DMS) is a comprehensive tool designed to manage and track document revisions and metadata within projects. It provides an intuitive interface for adding, updating, and searching documents, ensuring efficient management of document lifecycles.

It is critical that the project remains lightweight and modular. The inspiration for this project is the ability to incorporate the system rapidly with minimal corporate-IT permissions/red-tape, while allowing for maximum access to the information through an API or even direct access.

All extra functionality beyond adding/updating/searching/retrieving documents should be implimented as an optional modular plugin.

## Features (Most To Come)
- **Document Instance Creation**: Create new document instances in the database.
- **Revision Tracking**: Update document instances with newer file versions while keeping track of older revisions.
- **Document Linking**: Ability to link documents from different projects, with updates reflecting across linked instances.
- **Metadata Flagging**: Add and search for documents based on metadata attributes.
- **Project Management**: Choose and modify current working project settings.

## Installation
1. Clone the repository: `git clone https://github.com/yourusername/DocumentManagementSystem.git`

2. Navigate to the project directory: `cd lightweight-DMS`

3. (Include steps specific to setting up and running your application)

## Usage
Currently the project exists as a Class object in Python.

The plan is to impliment all basic functionality and port it to an API.

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## To-Do List
- [ ] Create Document instances in the DB.
- [ ] Update Document instance with a newer file.
- [ ] Reference older revisions in Document.
- [ ] Check if the document being uploaded already exists.
    - [ ] Give option to link from another project (will update on current project if revised on the other project).
- [ ] Search for files based on document attributes.
- [ ] Add metadata flagging to documents.
- [ ] Search for documents with metadata flagging.
- [ ] Choose the current working project.
- [ ] Modify project settings.
- [ ] Port to API for remote access and integration.

## License
Distributed under the GNU Affero General Public License (AGPL). See `LICENSE` for more information.

## Contact
Ryan Brown - me@ryanbrown.engineer

Project Link: [https://github.com/yourusername/DocumentManagementSystem](https://github.com/rbr0wn92/lightweight-DMS)](https://github.com/rbr0wn92/lightweight-DMS)
