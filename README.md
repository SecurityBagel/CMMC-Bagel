<p align="center">
  <img src="https://github.com/SecurityBagel/SecurityBagel/blob/main/SecurityBagel.png"/>
</p>

# CMMC Bagel Lite
An open-source Power BI template designed for compliance metrics, assessment tracking, and POA&M management. Ideal for auditing and managing your CMMC compliance program across one or more assessments for combined scoring.

## Directions
1. [Download Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free).
2. In Power Query, set the **'Assessments Folder'** parameter to the path of your local folder containing completed assessments.
3. Run locally or publish to your internal Power BI Service for broader access.

## Usage
1. Place your completed Assessment Template worksheets  within a local folder, or adjust the template to connect to other sources like OneDrive, SharePoint, etc.
2. Name each assessment in the corresponding Excel worksheet tab for easy identification.
3. Ensure the **'Assessments Folder'** parameter points to the local path of your assessments.

## Features
1. **Automated SPRS Scoring**: Calculates scores with POA&M allowance status in compliance with 32 CFR Part 170.
2. **Combined Assessment Scoring**: Consolidates scores across individual facility/device assessments, CUI assets, security protection assets, or other assessment plans.
3. **POA&M Tracking and Alerts**: Supports POA&M tracking with automated status updates for past-due items.
4. **Real-Time Assessment Updates**: Track assessment progress live—enable sync in Power BI Service for continuous updates.
5. **Free and Open-Source**: Fully free and modifiable to fit your needs.

## Contributing
This repository is licensed under the GNU General Public License (GPL).
Organizations can freely use and modify these Power BI templates to meet their unique requirements.
- **Distribution**: If you distribute modified versions publicly, they must remain open-source under the same GPL license.
- **Attribution**: Please credit the original author when showcasing or redistributing these templates.
- **Improvements**: Contributions are welcome! If you enhance the data model, optimize performance, or add useful features, please consider submitting those changes back to this repository. This helps the community benefit from ongoing improvements and collaboration.

## Demo
https://securitybagel.github.io/CMMC-Bagel-Lite
