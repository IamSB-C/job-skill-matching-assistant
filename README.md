# Job Application and Skill-Matching Assistant

## Overview

A beginner-friendly career guidance project built using n8n, JavaScript, and HTML/CSS. It compares a candidate's skills against sample job profiles and generates a report with match percentages and learning recommendations.

## Features

- Candidate information form
- Skill matching against sample job profiles
- Job match percentage calculations
- Matched and missing skill lists
- Dashboard summarising the results
- Four-week learning roadmap
- Beginner portfolio project suggestions
- HTML report with job-specific recommendations

## Tech Stack

- **Workflow automation:** n8n
- **Programming:** JavaScript
- **Report interface:** HTML and CSS
- **Local environment:** Docker

## How It Works

1. The candidate enters their name, skills, preferred role, and interests.
2. JavaScript compares their skills with predefined sample job profiles.
3. The workflow calculates match percentages and identifies missing skills.
4. A second code node generates a formatted report with recommendations.

## How to Run

1. Install and start n8n.
2. Import `workflow.json` into n8n.
3. Open the workflow and check the node connections.
4. Test the form using sample candidate details.

## Important Note

This project uses predefined sample job profiles and rule-based recommendations. It does not retrieve live job vacancies or use a generative AI model. Match percentages are based on the listed skills only.

## Learning Outcomes

- Building workflows with n8n
- Writing JavaScript for data processing
- Comparing skills using arrays and rules
- Generating HTML reports
- Connecting form inputs to workflow automation

## Future Improvements

- Add live job listing integrations
- Improve role-specific learning recommendations
- Integrate an AI model when an affordable option is available
- Add resume analysis and downloadable reports
