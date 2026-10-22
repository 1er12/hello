CIT 240 Team Project — Testing & Verification Report

This document records the verification tests performed for the website, setup instructions, and team member profile details.

Team Members

Our team consists of five members contributing to different areas of the project:

Student A: Jhoer Celino (username/id: 1er12) — Homepage

Student B: Jinky Alopena (username/id: glitch) — Team Profile

Student C: Alden Alcarde (username/id: source) — Setup Notes

Student D: Ella Mae Carisma (username/id: cloud) — Workflow Guide

Student E: Zyra Lozada (username/id: hash) — Testing & Quality Assurance

Testing Log

Check 1: Webpage Display (index.html)

Objective: Verify that index.html loads correctly in a browser and all basic layout elements display properly.

Actual Results: The page opens without missing tags or broken structures. Navigation and headers display as expected.

Issues Found: None.

Check 2: Setup Instructions

Objective: Ensure the setup instructions in the documentation allow a user to clone and launch the project on Windows.

Actual Results: The git clone command successfully cloned the repository, and the setup steps were easy to follow.

Issues Found: The repository URL field in the setup instructions contains a placeholder (<YOUR-REPOSITORY-URL>) instead of the explicit project URL, which might confuse new collaborators if not specified.

Check 3: Complete 5-Member Team List Verification

Objective: Confirm all 5 team members, usernames, and assigned responsibilities from the Team Profile document are included accurately.

Actual Results: All five members (Jhoer Celino, Jinky Alopena, Alden Alcarde, Ella Mae Carisma, and Zyra Lozada) along with their corresponding handles and duties match the team roster.

Issues Found: In the original source file, the header syntax for members (##Members) was missing a space after ##, causing Markdown engines to render it as raw text instead of a proper Heading Level 2 tag.
