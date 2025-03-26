# MTS1-Journey-Fyle-2024
My Full-Time Journey at Fyle Inc. | MTS1 Role

## 🔹 The Leap from Intern to MTS-1 at Fyle: My Journey 🚀 (1st July 2024)

Hello, tech enthusiasts and aspiring developers! 👋

Hopefully, you have jumped onto this repo after reading my [Internship-Journey](https://github.com/SahilK-027/Internship-Journey-Fyle-2024) if not I highly recommend going through that journey first.

So, Fasten your seatbelts as I take you through my exciting leap from an intern to a full-time MTS-1 (Member of Technical Staff) at Fyle. This journey isn’t just about learning to code better but evolving as a developer, teammate, and problem-solver in a fast-paced, dynamic environment. As I like to mention this is not just a README; it's a living document, a story in progress. Join me as I navigate the challenges, celebrate victories, and immerse myself in the world of pixels and protocols.

Buckle up, fellow coders! The journey begins here. Let the journey unfold! 🌟

## 🔹 From Internship to MTS1: Key Projects 🌱 

During my internship at Fyle, I got the opportunity to work on a variety of impactful tasks that set the foundation for my role as an MTS1. I have worked on fixing numerous usability issues and bugs but here are some key projects I handled included:

- **StyleLint Upgrade Dependency**: I worked on upgrading the StyleLint dependency and documented the process as part of the infrastructure updates. This involved ensuring that the changes didn’t break existing workflows and maintaining consistency in the codebase.
- **Date of Spend and Travel Field Name Issue**: This was an interesting challenge where I had to address discrepancies in field names for expenses, ensuring accurate data representation across the platform.
- **List View Alert Icons (Initiative 1)**: I contributed to an initiative that improved the alert icon visibility in list views, enhancing the user experience and making important notifications more accessible.
- **Projects API Migration (Initiative 2)**: A crucial part of my internship was working on migrating the Projects API, which included handling active categories in Quick Fyle. This task required a deep understanding of the system and collaboration with other teams to ensure a smooth transition.

Each of these initiatives has not only tested my technical skills but also given me a chance to take ownership and contribute to real-world features. This experience laid the groundwork for my responsibilities as an MTS1, where the focus shifted from just implementing tasks to thinking holistically about the project, scalability, and future impact.

## 🔹 Corporate Cards API Migration 💳 (25th July 2024)
This quarter, I’ve been working on the Corporate Cards API Migration. This initiative has been a deep dive into corporate card systems and has taught me a lot about both technology and documentation.

### The Legendary ED Doc
I started by writing a highly detailed ED (Engineering Design) document from scratch. This document has been invaluable throughout the project, serving as a reference for changes and guiding the implementation. This experience has taught me the importance of writing clear, detailed, and forward-thinking documentation.

### Test Cases, Test Cases, and More Test Cases
For every change, I wrote thorough test cases. Writing tests for every change isn’t glamorous, but it’s essential. Catching those bugs before they sneak in is its reward.

### Achievements

- Throughout this initiative, I’ve learned so much about VISA Nest, RTF, Virtual Cards, and even how Bank Statements are handled. 
- I also migrated APIs for 14 different actions, and reduced 10 redundant API calls, all without a single P0 issue so far—feels like winning! 
- This initiative has not only strengthened my technical skills but also sharpened my ability to handle complex migrations and work at scale.

### Export API Migration 🔄

We’ve now completed the migration of the Export API as well, marking a significant milestone in this initiative. Export functionality allows users to generate detailed reports of their Corporate Card transactions, making it a crucial component.

Frontend tasks for the Export API migration included:

- Refactoring advanced settings for list view columns.

- Transitioning user settings and default export preferences to the backend.

- Rewriting new column configurations for the list view table.

- Verifying export formulas with the backend team.

This migration took three weeks and required close collaboration with the backend team. Rigorous testing ensured a smooth transition with significant improvements in functionality.

With the Export API migration complete, this initiative is now officially wrapped up, delivering robust and scalable solutions across the board.

## 🔹 Move Reminder Dialog To FDL 🔔 (16th Oct 2024)
Currently, I'm working on migrating the **"Add Reminder" dialogue** to a new design that not only improves usability but also aligns with Fyle's fresh design standards. This initiative involves updating both the **Settings** and **Admin** personas, where the dialogue is displayed using `Angular.js`. With a fresh design from **Figma** to follow, the goal is to make this UI sleek, modern, and user-friendly.

### **Key Changes Involved:**

- **CSS Updates**: We’re updating margins, paddings, and font sizes to match the latest FDL specifications.
- **Layout Changes**: The form inputs, titles, and buttons will all get a facelift to follow new alignment rules.

The initiative itself has a relatively quick turnaround—**1 week** (as exports API migration is pending from the last initiative I will work on this for a week and then get back to exports API migration) to get through everything, including design doc writing, dev work, testing, and release!

## 🔹 CI-CD ⛙ (17th Oct 2024)
Today marked my first production deployment for the Fyle web app! 🎉 In addition to deploying the web app, I also managed the deployments for our Outlook and Chrome extensions. Balancing this new responsibility with my regular tasks has been quite exciting.

### Highlights:
- **Balancing Act:** Juggling production deployments with everyday tasks was both challenging and fun.

- **Process Boost:** I initiated a standardized frontend deployment schedule (yes, convincing everyone to cherry-pick and test before noon has its fun moments!).

## 🔹 Documentation & READMEs Revamp 📚
- **Notion Overhaul:** I reorganized “The World of Design Docs” into neat, clear sections, making it super easy to find the right document.

- **Updated READMEs:** Updated the READMEs for Fyle-app, Fyle-mobile-app, and Fyle-outlook.

## 🔹 Display exact amount in mobile app
Users were finding it tricky to see full amounts in decimals without extra clicks—so we knew it was time for a change!

### The Plan:

- Dashboard:
   - Display up to 9 digits with two decimals.
   - For amounts with 10+ digits, switch to a shorthand format.

- Other Screens:
   - Show up to 15 digits with two decimals for better clarity.

### New Pipe 🛠️:

- What’s New:: I created a new pipe to ensure exact currency formatting (no “K” or “M” shortcuts). This new pipe works as an override to Angular’s native `currencyPipe` while still respecting settings like skipSymbol and fraction.

- It was a fun challenge to tweak the way we display amounts in the app. By using different pipes for different needs, we maintained the old implementation and achieved all the required consistency.
