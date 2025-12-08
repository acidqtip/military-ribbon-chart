# Military Ribbon Chart - Career Planning Tool

## Overview
The Military Ribbon Chart is a web-based career planning and visualization tool designed to help military officers, mentors, and career managers track, plan, and analyze career progressions. The tool visualizes career milestones as a "ribbon chart," providing a clear, color-coded timeline of assignments, education, and command experiences.

## Key Features

### 1. Create & Visualize Charts
*   **Officer Profile**: Input detailed officer information including Rank, Name, Duty Title, Unit, AFSC, and Year Group.
*   **Career Milestones**: Add assignments with specific details such as Position Title, Unit, Location, Dates, and Type.
*   **Ribbon Chart Visualization**: Automatically generates a "ribbon chart" grid view where each cell represents a year, and colored blocks indicate assignment types.
*   **Timeline View**: Displays a detailed vertical timeline of the career history with durations calculated automatically.

### 2. Assignment Categories
Assignments are color-coded for easy recognition:
*   🟦 **Operational**: Standard operational assignments.
*   🟪 **Staff**: Headquarters and staff positions.
*   🟥 **Command**: Leadership and command roles.
*   🟩 **School/Education**: Professional Military Education (PME) and advanced degrees.
*   🟧 **Joint**: Joint service assignments.

### 3. Biography Import (Prototype)
*   **PDF Upload**: Includes an interface to upload official military biography PDFs.
*   **Data Extraction**: Simulates the extraction of career data from uploaded files to populate the chart automatically.

### 4. Database & Mentorship
*   **Saved Charts**: Save and manage multiple career charts in a local database (using browser memory).
*   **Mentor Matching**: Find potential mentors by matching career aspirations and interests (e.g., Command, Joint, Staff) against the database of saved senior officer profiles.

## How to Use
1.  Open `index.html` in any modern web browser.
2.  **To Create a Chart**:
    *   Navigate to the "Create Chart" tab.
    *   Fill in the Officer Information.
    *   Add assignments one by one in the "Add Career Milestone" section.
    *   View the generated Timeline and Ribbon Chart at the bottom.
    *   Click "Save Chart" to store it in the browser's local session.
3.  **To Find a Mentor**:
    *   Go to the "Mentor Matching" tab.
    *   Enter your career goals and check boxes for desired experiences.
    *   Click "Find Mentor Matches" to see officers with relevant experience.

## Technical Details
*   **Single-File Application**: The entire tool is contained within `index.html`, making it easy to deploy and run offline.
*   **Technologies**: Built with vanilla HTML5, CSS3, and JavaScript.
*   **Responsive Design**: Distinct styles for desktop and mobile viewing.
