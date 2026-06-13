🚀 AetherSheets

AetherSheets is an autonomous AI-inspired spreadsheet platform that simulates multiple intelligent agents collaborating to collect, validate, repair, and organize business data in real time.

Built as a standalone HTML application using React, Tailwind CSS, and modern UI design principles, AetherSheets demonstrates how autonomous agents can work together inside a spreadsheet-like environment.

✨ Features
🤖 Multi-Agent Architecture

AetherSheets contains three specialized AI-inspired agents:

Agent Alpha
Data collection and scraping
Company intelligence gathering
Information retrieval
Agent Beta
Data validation
Cross-reference verification
Quality assurance
Agent Gamma
Error detection
Self-healing workflows
Formula and data repair
📊 Spreadsheet Intelligence
Interactive spreadsheet grid
Company tracking dashboard
CEO information management
Industry classification
Validation status monitoring
⚡ Autonomous Execution

One-click autonomous workflow execution:

Gather company information
Validate retrieved data
Detect inconsistencies
Repair failures automatically
Update spreadsheet records
🔧 Self-Healing Simulation

Enable Broken Data Source Mode to simulate:

Missing data
Connection failures
Validation errors
Automatic recovery workflows

This demonstrates how autonomous systems can recover from failures without human intervention.

📄 AI Research Reports

Generate automated reports summarizing:

Processed companies
Validation results
Agent activity
Data quality metrics
📜 Live Activity Logs

Monitor every action performed by agents in real time.

Examples:

Data retrieval
Validation checks
Error detection
Repair operations
Workflow completion
🛠️ Technologies Used
HTML5
CSS3
JavaScript (ES6+)
React 18
Tailwind CSS
Babel Standalone
🎯 Project Vision

AetherSheets explores the future of spreadsheets by combining:

Autonomous workflows
Agent-based systems
Intelligent validation
Self-healing processes
Human-AI collaboration

The goal is to move beyond traditional spreadsheets toward intelligent systems capable of managing and validating information independently.

🚀 Deployment

This project is fully static and can be deployed on:

Netlify
Vercel
GitHub Pages
Netlify Deployment
Download the project.
Rename the main file to index.html.
Drag and drop it into Netlify.
Your site will be live instantly.
📷 Screenshots

Add screenshots here:

Dashboard
Agent Control Center
Autonomous Run
Research Report
Activity Logs
🔮 Future Roadmap
Natural language command center
AI-powered data analysis
Interactive visualizations
Confidence scoring
Real-time external data sources
Multi-sheet support
Workflow automation builder
👨‍💻 Author

Built by Kashvi Nagpal as an exploration of autonomous spreadsheet systems and AI-inspired workflow automation.

If you like this project, consider giving it a ⭐ on GitHub.



prompts used:-
Act as a senior frontend engineer. Create a beautiful, full-stack web application named "AetherSheets" inside this directory using React, Tailwind CSS, and a modern Vite build setup. 1. App Interface: Design a premium, highly visual dashboard with a futuristic dark-theme grid (Rows 1-10, Columns A to E) resembling a high-end spreadsheet. 2. Sidebar: On the left, build an "Agent Control Center" showing three distinct active AI Agents with pulsing green CSS indicator animations: - "Agent Alpha: OSINT Web Scraper" - "Agent Beta: Validation & Truth Engine" - "Agent Gamma: Formula Self-Healer" 3. The Action Bar: Create a prominent, glowing "Execute Autonomous Run" button at the top, along with a secondary toggle switch titled "Simulate Broken Data Source". 4. Console Log: Add a scrolling "Live Agent Activity Log" console window spanning across the bottom of the interface to display simulated real-time terminal output. 5. Setup & Preview: Initialize all necessary files, install Tailwind CSS dependencies, configure the build settings, and prepare the project to be run locally.


Now, create a backend processing utility (or integrated API function if using a single-page full-stack layout) that connects to the Groq API. 1. Initialize the Groq client to look for an environment variable named 'GROQ_API_KEY'. Use the 'llama-3.3-70b-versatile' model for core analysis. 2. Structure a system prompt for the Groq engine that looks exactly like this: ''' You are an advanced corporate intelligence spreadsheet agent. You are handed a company name. Your job is to output a clean, valid JSON object containing exactly three fields: - "ceo": The full current legal name of the active CEO. - "ticker": The official stock exchange ticker symbol. - "industry": A 2-word industry classification. Output ONLY raw, valid JSON. Do not include markdown code wrappers, explanations, or thinking blocks outside the JSON brackets. ''' 3. Hackathon Rate-Limit Protection: Implement a sequential processing loop using an explicit 1.5-second 'setTimeout' or sleep delay between handling row processing requests. This ensures our requests stay completely safe from hitting the Groq Free Tier Requests Per Minute (RPM) limits.
