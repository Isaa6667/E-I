E&I Amusements Code & License Key Storage
Overview

This repository is used by E&I Amusements to securely store, manage, and organize application code and JSON-based license keys. It serves as a centralized location for development assets and licensing data required for internal systems and deployed products.

Purpose
Maintain structured storage for application source code
Store and manage license keys in JSON format
Provide a consistent system for accessing and updating licensing data
Support internal tools and amusement systems requiring license validation
Repository Structure

/code
Contains all application source code, scripts, and related development files

/licenses
Contains JSON files that store license keys and associated metadata

JSON License Format

Each license is stored as a JSON object with a standardized structure. Example:

{
"license_key": "XXXX-XXXX-XXXX-XXXX",
"issued_to": "Client or Location Name",
"product": "System Name",
"issue_date": "YYYY-MM-DD",
"expiry_date": "YYYY-MM-DD",
"status": "active"
}

Guidelines
Code Storage
Keep code organized by project or module
Use clear and consistent naming conventions
Document major functions and components
Avoid committing sensitive credentials directly in code
License Storage
Store each license as an individual JSON file or grouped logically
Ensure license keys are unique
Update status fields when licenses change (active, expired, revoked)
Validate JSON formatting before committing
Security Considerations
Restrict access to authorized personnel only
Do not expose this repository publicly
Encrypt sensitive data where possible
Regularly audit license files for accuracy and integrity
Usage
Developers can access code for updates and maintenance
Systems can read JSON license files for validation
Administrators can add, update, or revoke licenses as needed
Maintenance
Review and clean outdated licenses periodically
