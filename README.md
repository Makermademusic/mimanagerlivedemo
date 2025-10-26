Mi Manager: The Indie Artist Business Suite

Mi Manager is a personal finance and productivity tracker designed for independent artists, musicians, and music producers. It acts as an on-demand business manager, providing the strategic roadmap, financial clarity, and legal guidance necessary to convert creative assets into sustainable revenue streams.

Key Features

Mi Manager is a single-page application built for real-time tracking and multi-user collaboration.

1. Strategic Master Plan

Four Phases: Provides a clear, milestone-driven roadmap for music releases (Production, Pre-Release, Launch, Post-Release).

Guided Execution: Each milestone expands into a Best Practice Guide, offering specific, actionable advice (e.g., PRO registration, distributor submission timing).

2. Financial Tracker & Asset Monetization

Net Profit KPI: Users can model estimated monthly income (Streaming, Sync, Merch) and track project expenses to instantly calculate Estimated Net Profit.

Dynamic Investment Suggestions: Provides data-driven recommendations on where to reinvest profits (e.g., scaling marketing, funding the next project).

3. Collaboration & Data Sharing

Multi-User Access: Projects are stored in a public, real-time database (Firestore). Users can generate a unique Share ID to collaborate with managers, bandmates, or producers.

4. Pitch-Ready Demo Mode

Read-Only Investor Mode: Includes a dedicated project (investor-demo-001-pitch-ready) that automatically locks into read-only mode, protecting the demo data while showcasing aspirational performance metrics for investors.

5. Essential Tools

Content Calendar: Tracks scheduled marketing tasks (teasers, VLOGs, email blasts) tied to the release strategy.

Legal Agreement Guide: Provides informational guides on critical agreements like Sync Licenses and Producer Agreements.

Technology Stack

Mi Manager is designed for maximum stability and speed in a single-file environment.

Frontend: Single-file HTML5, pure JavaScript (ES6+).

Styling: Tailwind CSS (via CDN) for a clean, modern, responsive, and distinct Black/Red design.

Database: Firebase Cloud Firestore for real-time, cloud-based storage of project data and user metadata.

Quick Launch & Deployment

For Immediate Preview (Local File Method)

To launch the app immediately without hosting or command line tools:

Save the entire content of this file (index.html) to a file named MiManagerDemo.html on your computer.

Double-click MiManagerDemo.html. The app will launch instantly in your web browser.

For Live Deployment (Recommended)

To deploy the app for public use and stable feedback:

Configure Firebase: Create a Firebase project, enable Authentication (Anonymous) and Firestore Database.

Set Security Rules: You MUST configure Firestore security rules to allow read/write access to the public /projects/ collection for authenticated users (request.auth.uid != null).

Host: Deploy the index.html file using a service like GitHub Pages (via browser upload) or Netlify (via drag-and-drop).
