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
5. Run locally or publish to your Power BI Service.
6. Enter the file location paths using Excel or SharePoint Online. 
### Using Excel
7. Copy and paste the complete path to the folder containing your completed assessment files in the **'Assessments Folder'** field. Remove quotes from path name. (Example: C:\Users\foo\Documents\Assessments)
8. Copy and paste the complete path to the file for the POA&M (Plan of Action and Milestones) in the **'POA&M file'** field. Remove quotes from path name. (Example: C:\Users\foo\Documents\POA&M Template.xlsx)
### Using Sharepoint Online
7. Enter your SharePoint site URL. (Example: https://securitybagel.sharepoint.com/sites/SecurityBagelCMMCBagel)
8. Enter the folder name containing your completed assessment files.
9. Copy and paste the complete path to the file for the POA&M (Plan of Action and Milestones) in the **'POA&M file'** field. The path can be found under by clicking on the file (...) then details, and copying the Path.  (Example: https://securitybagel.sharepoint.com/sites/SecurityBagel-CMMCBagel/Shared%20Documents/Files/POA&M.xlsx)


## Features
### 
1. **Automated SPRS Scoring**: Calculates SPRS scores with POA&M allowance status for compliance with 32 CFR Part 170.
2. **Combined Assessment Metrics**: Consolidates metrics and scores across individual facility/device assessments, CUI assets, security protection assets, or other assessment scope.
3. **Interactive Dashboards**: Visualize compliance metrics, track assessment completion, and identify gaps.
4. **Real-Time Assessment Updates**: Track live assessment progress in Power BI Service for continuous updates.
5. **Free and Open-Source**: Fully free and modifiable to fit your needs.
6. **POA&M Management**: Track remediation actions and monitor progress on outstanding controls.
7. **Free and Open-Source**: Also fully free and modifiable to fit your needs.

## Contributing
This repository is licensed under the GNU General Public License (GPL).
Organizations can freely use and modify these Power BI templates to meet their unique requirements.
- **Distribution**: If you distribute modified versions publicly, they must remain open-source under the same GPL license.
- **Attribution**: Please credit the original author when showcasing or redistributing these templates.
- **Improvements**: Contributions are welcome! If you enhance the data model, optimize performance, or add useful features, please consider submitting those changes back to this repository. This helps the community benefit from ongoing improvements and collaboration.

## Live Demo
https://securitybagel.github.io/CMMC-Bagel/live-demo.html

## Screenshot
![CMMC Bagel Lite](https://github.com/SecurityBagel/CMMC-Bagel/blob/main/Images/CMMC%20Bagel.png)
