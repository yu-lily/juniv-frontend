This is an app for converting DNA/RNA sequences into a format suitable for patent submission.

# Starting Page
The starting page should have a left sidebar for nav with logo, new project button, project history, global contacts, and preferences button.

The body should contain two big buttons for creating a new project, one that lets you upload a file, and one that creates a blank project

Below the buttons, there should be a table for project history below the buttons, with the columns:
- Project Name
- Applicant File Reference
- Applicant Name
- Invention Title
- Status
- Creation Date
- Last Modified

# Create Project Page
A header of the project details, and two main tabs: General Information, and Sequences.

## General Information
The editable fields should be:
- Application Identification (Subfields: IP Office, Application Identification, Applicant File Reference, Application Number, Filing Date)
- Priority Identification (Subfields: IP Office, Filing Date, Application Number, Selected Earliest Priority Application Yes/No)
- Applicant & Inventor, with choices to pull options from Global Contacts
- Invention Title (Subfields: Invention Title, Language)

## Sequences
A table of sequences with the columns:
- Sequence ID Number
- Sequence Name
- Length
- Molecule Type
- Organism
- Skipped Sequence

When a row of the table is clicked, it should open up an area inline in the table to allow the user to edit the sequence. Within this area, there should be a features table with the columns:
- Feature Key
- Location
- Qualifiers

The sequence text box should have the following UI elements:
- An indicator to show the numerical index of the current cursor position
- An "Add feature here" button, that will create a new feature with start/end indicies matching what is highlighted
