eLogic — Digital Logic Simulator
Project Description
eLogic is an interactive web-based digital logic simulator developed for the Digital Logic Design Laboratory at SRM Institute of Science and Technology. It allows students to design, simulate, and analyze digital circuits without physical hardware components.

Who We Are Making This For
This project is built for SRMIST engineering students enrolled in Digital Logic Design and related courses including CSE, ECE, EEE, and IT branches. Secondary users include professors who can demonstrate circuits in class, lab instructors who need to reduce hardware maintenance costs, and remote learners who need 24/7 access to lab facilities.

Key Features
The simulator includes a complete gate library with AND, OR, NOT, NAND, NOR, XOR, XNOR, and Buffer gates. Users can drag gates onto an infinite canvas, connect them with wires, and see real-time simulation with green wires indicating logic HIGH and dim wires indicating logic LOW. Double-clicking input nodes toggles their values.

The platform includes 12 structured experiments covering the entire DLD curriculum from basic logic gates to counters and registers. Each experiment comes with voice narration, pre-built circuit layouts, and relevant theory.

Additional features include auto-generation of truth tables, real-time Boolean expression derivation, waveform visualization, an AI tutor powered by Claude, voice command recognition, undo/redo functionality, import/export of circuits as JSON files, dark and light themes, keyboard shortcuts, and a minimap for navigation.

Technical Implementation
The application is built using HTML5, CSS3, and vanilla JavaScript with Canvas API for rendering. No build process or dependencies are required. The simulation engine uses recursive propagation through connected gates with cycle detection. The application runs entirely in the browser with optional cloud features for AI tutoring.

Python Server Usage
To run this project locally, you can use Python's built-in HTTP server:

bash
python -m http.server 8080
Then open your browser to http://localhost:8080

For local network access during lab sessions:

bash
python -m http.server 8080 --bind 0.0.0.0
Students can then access the simulator using your computer's IP address.

Educational Value
The simulator addresses common pain points in digital logic education including expensive hardware kits, limited lab access, difficulty debugging physical circuits, and varying student learning paces. It provides a risk-free environment where students can experiment, make mistakes, and learn through hands-on practice.

Target Environment
The application runs on any modern web browser including Chrome, Firefox, Edge, and Safari. Internet connection is required only for AI Tutor features and voice synthesis. The application can be deployed on SRMIST internal servers, GitHub Pages, Netlify, or any static web hosting service.

Conclusion
eLogic 2.0 transforms digital logic education at SRMIST by providing an accessible, intelligent, and engaging platform that reduces costs while improving learning outcomes for all engineering students.

# VOXLOGIC
