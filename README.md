# AFBN-Web3-Academy

AFBN Academy is the "Ultimate Web3 Masterclass" and a comprehensive free curriculum for learning about decentralized technology. It is designed to take users from zero to expert in topics such as Blockchain, DeFi, NFTs, Security, and Smart Contract mechanics.

## Getting Started

Open `index.html` in your browser. No build tools required.

## License

MIT © 2026 AFBN

# AFBN Academy

## Description
AFBN Academy is the "Ultimate Web3 Masterclass" and a comprehensive free curriculum for learning about decentralized technology. It is designed to take users from zero to expert in topics such as Blockchain, DeFi, NFTs, Security, and Smart Contract mechanics.

## Features
* **Extensive Curriculum**: The academy features over 2,500 in-depth lessons spread across 12 specialized modules. Modules include topics like AI × Blockchain, Gaming, History, and DAOs.
* **Curated Learning Paths**: The interface offers tailored learning tracks based on experience level. Users can choose between Beginner, Intermediate, and Advanced paths.
* **Interactive UI**: The application utilizes a highly responsive, modal-based interface. It also features dynamic background animations with floating particle effects.
* **Accessibility**: The code includes a built-in Google Translate widget supporting dozens of languages.
* **Progress Tracking**: Users can mark individual lessons as complete. This action triggers a success toast notification and visually updates the button state.
* **WordPress "Nuclear Overrides"**: The styling is engineered specifically to bypass rigid legacy WordPress themes. This is achieved using aggressive CSS isolation, utilizing properties like `position: fixed !important` and `z-index: 999999`, alongside a total container reset.

## Tech Stack
* **HTML5 & CSS3**: Utilized for structure and advanced styling, including flexbox layouts, CSS grids, and custom gradient variables.
* **Vanilla JavaScript**: Handles all internal logic, event delegation, tab switching, and modal rendering. The script relies purely on Vanilla JS to remain lightweight and functional within restrictive CMS environments.
* **External Libraries**: Incorporates FontAwesome 6.4.0 for iconography and fetches Google Fonts (Inter) for all typography.

## Installation & Usage Instructions
Because the application is built entirely with Vanilla JavaScript, HTML, and CSS in a single file structure, installation requires no build tools or package managers.

### Option 1: Standalone HTML Deployment
1. Clone this repository to your local machine.
2. Double-click the `index.html` file to open it directly in any modern web browser.
3. The application will render instantly and overtake the viewport.

### Option 2: WordPress Integration
This code includes specific architectures designed to be injected into WordPress environments without conflicting with existing theme styles.
1. Log into your WordPress admin dashboard.
2. Navigate to the page or post where you want the academy to be hosted.
3. Add a **Custom HTML** block to the editor.
4. Copy the entire contents of the source code and paste it directly into the block.
5. Publish or update the page.
* **Note**: The integrated "Nuclear Overrides" will automatically hijack the viewport and explicitly hide the WP Admin bar when the app is active.

## License & Intellectual Property
* **Creator**: Academy code and course content were created by William Simmons, CEO of @AFewBadNewbies.
* **Copyright**: © 2025 A Few Bad Newbies — Free education for everyone.