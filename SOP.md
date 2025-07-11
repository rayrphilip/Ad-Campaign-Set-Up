# Ad Campaign Setup SOP for Media Platform

## Overview

This Standard Operating Procedure (SOP) outlines the standardized process for setting up advertising campaigns using a former internal media platform. It is intended for trained internal users, media buyers, and agency partners responsible for managing ad campaigns on behalf of clients. Since the platform is no longer operational and I no longer have system access, this documentation has been compiled from memory with the assistance of a former colleague.

## Assets & Requirements Table

Before setting up a campaign, ensure the following are in place:

| Assets & Requirements | Specifications |
| :-------------------- | :------------- |
| Access to the Internal Media Platform | Valid user account, login credentials, necessary permissions to create/manage campaigns |
| Campaign Plan | Defined objectives, target audience, budget, and flight dates |
| Brand Information | Correct legal name, billing details, and any required internal IDs |
| Landing Page URLs | Final, correctly written URLs for all ad destinations |
| UTM Parameters (optional) | Pre-defined tags for traffic source tracking |
| Ad Files | All images and videos meeting ad specifications |
| Tracking Prerequisites | Have been tested by web development team and clearly defined Conversion events |
| Technical Setup | Latest Google Chrome browser installed and any ad blocking software disabled |

Once you’ve met all the requirements, you can proceed to create a new campaign. If you have any issues pertaining to any of these requirements, please contact your Account Manager.

## Create New Campaign

1. Log into the internal media platform using your credentials

   - Open a web browser and navigate to the platform login page.
   - Enter your username and password.
   - Complete two-factor authentication if prompted.
   - Verify that you are logged in by confirming your username appears in the top-right corner of the dashboard.

2. Navigate to the Campaign Creation Page

   - From the main dashboard, locate **Campaigns** on the left-hand navigation menu.
   - Select **Create New** to open the campaign setup form.

3. Enter the Campaign details

   - In the **Campaign Name** field, use the standardized naming convention:
```
     CLIENT_CAMPAIGNNAME_YYYY-MM-DD
     (e.g., VIBENETMEDIA_WatchoraPromotion_2020-02-08)
```
   - Enter the client name (in place of “CLIENT”), the title of the campaign (in place of “CAMPAIGNNAME”), and the start date of the campaign (in place of “YYYY-MM-DD”).

5. Set a Budgeting Allocation

   - **Total Campaign Budget**: Enter the overall budget allocated for the campaign.
   - **Daily/Monthly Budget Caps**:
      - Specify a daily budget to control spending (e.g., $600/day).
      - *Optional*: Set a monthly budget to align with billing cycles.
   - **Bidding Strategy**: Select the appropriate strategy based on campaign goals.
  
6. Define Flight Dates (start and end dates for the campaign)

   - In the **Start Date** field, select the campaign’s launch date.
   - In the **End Date** field, select the last day of the campaign.
   - *Optional*: Enable **Pacing** to evenly distribute impressions over the entire campaign duration.

7. Select Targeting Criteria

   - Navigate to the **Targeting** section of the form.
   - Configure the following parameters as needed:
      - **Geographic Targeting**: Select specific countries, regions, or cities
      - **Demographic Targeting**: Define the age and/or gender
      - **Behavioral Targeting**: Choose interests and/or behavior
      - **Device Targeting**: Specify devices or operating systems being used
   - Use the platform's preview tool to verify the estimated audience reach.
   - Click **Save**.
  
8. Configure Pixel Tracking

   - Navigate to **Tools** and click **Pixels & Conversions**.
   - Click **+ New Pixel** or choose an existing one.
   - Assign a clear name.
   - Select its function (View-through, Click-through, or Conversion).

9. Upload Creative Files

   - In the **Creative Upload** section, click **Browse** to select the desired files from your device.
   - Supported file types include JPG, JPEG, PNG, GIF, HTML5, and MP4 (refer to platform specifications for size and format requirements).
   - Ensure files adhere to the naming convention:
```
CLIENT_CAMPAIGNNAME_ASSETTYPE_YYYY-MM-DD_VERSION.FILETYPE
(e.g., VIBENETMEDIA_Watchora_Banner_2020-02-08_v2.jpg)
```
   - Upload all required creative assets (e.g., banners, videos) and assign them to the appropriate ad placements.
   - Preview each uploaded file to confirm correct rendering in the platform.

9. Review & Submit
   - Review all entered details, including campaign name, budget, flight dates, targeting, and creatives.
   - Click **Save Draft** to store the campaign for further edits, or **Submit** to send for approval (if approval workflows are enabled).
   - If errors are detected (e.g., missing fields, incorrect file formats), address them based on the platform’s error messages.
   - After submission, the campaign will enter a review and approval process by the media operations or QA team

## Conclusion

This guide has outlined the standard process for setting up advertising campaigns on the internal media platform. It serves as a key reference to help users maintain consistency and accuracy throughout campaign creation, ensuring effective and timely launches.
