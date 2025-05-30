# PDS Reports Website

This is a lightweight website hosted on GitHub Pages, designed to display reports sourced from Google Sheets. It provides a clean, responsive interface for quick access to various PDS reports, tailored for both desktop and mobile users.

## Project Overview

- **Purpose**: Provide easy access to PDS reports for stakeholders.
- **Host**: GitHub Pages (`https://nicholas-pds.github.io/pds-reports/`).
- **Data Source**: Google Sheets (dynamically linked to report pages).
- **Last Updated**: May 5, 2025.

## Features

- **Home Page**: Centralized navigation hub with links to all report pages.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- **Clean Interface**: Minimalist layout with a header graphic featuring the PDS logo.
- **Report Views**:
  - **Cases Leaving Today**: Real-time view of cases scheduled to leave.
  - **Daily Huddle EFF Report**: Efficiency metrics for daily huddle meetings.
  - **EFF Report Manager Meeting**: Detailed efficiency report for managers.
  - **Historical Sales Report**: Sales performance over time.
  - **Historical Approval Report**: Approval trends and metrics.
  - **Remake Report**: Insights into remake processes.
  - **Account Management Dashboard**: Comprehensive account metrics overview.

## File Structure

```bash
root/
│
├── index.html                     # Main homepage
├── rushcases.html                 # Cases Leaving Today report page -- NOT CURRENTLY USED
├── rushcases2.html                # Dashboard view for Cases Leaving Today
├── prevday.html                   # Previous day overview report
├── eff.html                       # Daily Huddle EFF report page
├── eff2.html                      # EFF Report Manager Meeting page
├── eff3.html                      # Dashboard view for EFF
├── remake.html                    # Remake report page
├── histsales.html                 # Historical Sales report page
├── histabprod.html                # Historical Approval report page
├── ammetrics.html                 # Account Management Dashboard page
├── pds logo 1.jpg                 # Header image (PDS logo)
├── PDS instagram Logo R2 (2) - Copy.png  # Additional logo file
└── README.md                      # This file
```

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nicholas-pds/pds-reports.git
   cd pds-reports
   ```

2. **Serve Locally (Optional)**:
   To preview the site locally, use a simple HTTP server (e.g., Python's built-in server):
   ```bash
   python -m http.server 8000
   ```
   Then, open `http://localhost:8000` in your browser.

3. **Deploy to GitHub Pages**:
   - Ensure the repository is public or has GitHub Pages enabled (Settings > Pages).
   - Push changes to the `main` branch, and the site will update automatically at `https://nicholas-pds.github.io/pds-reports/`.

## Usage

- Navigate to the homepage (`index.html`) to access links to all reports.
- Each report page pulls data directly from Google Sheets, ensuring real-time updates.
- Use the browser's back button or homepage link to return to the main navigation.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Add feature"`).
4. Push to your fork (`git push origin feature-branch`).
5. Open a pull request on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.