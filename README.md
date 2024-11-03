<p align="center">
  <img src="https://github.com/SecurityBagel/SecurityBagel/blob/main/SecurityBagel.png"/>
</p>

# CMMC Bagel
An open-source Power BI template designed for compliance metrics, assessment tracking, and POA&M management. Ideal for auditing and managing your CMMC compliance program across one or more assessments for combined scoring.

## Directions
1. [Download and install Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free).
2. Download and complete the **'Assessment Template.xlsx'** and **'POA&M Template.xlsx'** Excel files. Required fields are noted.
3. Place your completed assessment worksheets within a folder. Use one Excel file per Assessment and name each assessment worksheet tab.
4. Download and run the **'CMMC Bagel lite.pbit'** file. (Ignore version errors)
5. Copy and paste the path to the folder containing your completed assessment files in the **'Assessments Folder'** field. Remove quotes from path name.
6. Copy and paste the file path for the POA&M (Plan of Action and Milestones) in the **'POA&M file'** field. Remove quotes from path name.
7. Run locally or publish to your Power BI Service.

## Features
### Basic
1. **Automated SPRS Scoring**: Calculates SPRS scores with POA&M allowance status for compliance with 32 CFR Part 170.
2. **Combined Assessment Metrics**: Consolidates metrics and scores across individual facility/device assessments, CUI assets, security protection assets, or other assessment scope.
3. **Interactive Dashboards**: Visualize compliance metrics, track assessment completion, and identify gaps.
4. **Real-Time Assessment Updates**: Track live assessment progress in Power BI Service for continuous updates.
5. **Free and Open-Source**: Fully free and modifiable to fit your needs.
### Lite
1. All the features in Basic, plus...
2. **POA&M Management**: Track remediation actions and monitor progress on outstanding controls.
3. **Free and Open-Source**: Also fully free and modifiable to fit your needs.
### Pro (Coming Soon)
1. **Customer Responsibility Matrices**: AWS and Azure customer responsibility worksheets and assessment.
2. **Risk**: Control maturity, weighting, asset criticality, and scoring.
3. **Tool Integrations**: Automate evidence gathering and test metrics.
4. **Additional Standards**: NIST CSF, framework mappings (ISO 27001, NIST 800-53), and more...
5. **SSP Builder**: Export a formatted SSP with Power BI report builder.
6. **Advanced Calculations and Visualizations**: POA&M ROI, What-if analysis, risk scoring.
7. **Customer support**: The Pro version will include additional support.

## Contributing
This repository is licensed under the GNU General Public License (GPL).
Organizations can freely use and modify these Power BI templates to meet their unique requirements.
- **Distribution**: If you distribute modified versions publicly, they must remain open-source under the same GPL license.
- **Attribution**: Please credit the original author when showcasing or redistributing these templates.
- **Improvements**: Contributions are welcome! If you enhance the data model, optimize performance, or add useful features, please consider submitting those changes back to this repository. This helps the community benefit from ongoing improvements and collaboration.

## Live Demo
https://securitybagel.github.io/CMMC-Bagel/live-demo.html

## Screenshot
![CMMC Bagel Lite](https://github.com/SecurityBagel/CMMC-Bagel/blob/main/CMMC%20Bagel%20Lite.png)
