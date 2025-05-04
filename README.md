# GTM Server Side Template - UET Data to Microsoft Ads/Bing
sGTM template for Bing/Microsoft Ads Server-side

## Description

This GTM (Google Tag Manager) Server Side template allows the sending of UET (Universal Event Tracking) data to Microsoft Ads/Bing, both server-side and/or via browser pixels. It is designed to be flexible and compatible with any server-side solution, regardless of the hosting provider.

Additionally, if the client has opted for Sirdata's data enrichment service, the template includes additional features that can be executed automatically. These features include consent-based conditioning, sharing of user data such as SHA-256 hashed email addresses, a cookieless ID, adjustments for adblockers, and other premium functionalities provided by Sirdata.

## Features

### 1. UET Data to Microsoft Ads/Bing
The template allows sending event tracking data to Microsoft Ads/Bing using the UET API, both server-side and via traditional browser pixels. This flexibility ensures reliable data collection and optimization across different environments.

### 2. Sirdata Integration (Optional)
If the client has chosen to enrich data via **[Sirdata](https://sgtm.sirdata.io/login)**, the template includes the following features:
- **Consent-based Conditioning**: Data collection is done in compliance with user consent preferences.
- **SHA-256 Hashed Email Sharing**: User email addresses can be safely shared after being hashed in SHA-256.
- **Cookieless ID**: A unique user identifier is generated without relying on traditional cookies.
- **Adblocker Handling**: The template includes specific adjustments for bypassing adblockers.
- **Premium Advanced Features**: Depending on the Sirdata service subscription, additional features may be available to enhance user data enrichment.

### 3. Client Options for Data Sending
Clients can choose from the following configurations:
1. **Server-side Data with Browser Pixel Backup**: Use server-side tracking as a complement to the browser pixel, particularly when the browser pixel is blocked by adblockers, leveraging an existing UET ID.
2. **Full Data Collection via Pixel and/or Server-side**: Send all data systematically via either the pixel or server-side, using a dedicated UET ID for tracking.

### 4. Hosting Flexibility
The template is designed to be compatible with any server-side hosting solution, offering great flexibility for integration. The user can easily deploy the template in their existing environment, regardless of the hosting configuration.

## Prerequisites

- **Google Tag Manager Server Side**: A Google Tag Manager Server Side environment is required to use this template.
- **Microsoft Ads Account**: A Microsoft Ads/Bing account is necessary for sending UET data.
- **Sirdata Account (Optional)**: If using the Sirdata data enrichment service, a Sirdata account is required to activate the advanced features.

## Installation

1. **Deploy the Template**:
   Download this template and import it into your Google Tag Manager Server Side environment.
   
2. **Configure Microsoft Ads/Bing Parameters**:
   Set up the necessary identifiers and parameters for integrating with Microsoft Ads (UET).

3. **Configure Sirdata (Optional)**:
   If you've subscribed to the Sirdata data enrichment service, enter your credentials and activate the desired features.

4. **Test**:
   Before going live, test the UET data sending and Sirdata integration to ensure everything is functioning as expected.

## Customization

The template can be customized to meet specific requirements:
- **Event Adaptation**: Modify the events sent to Microsoft Ads according to your tracking needs.
- **Data Enrichment**: Adjust the rules for user data conditioning if further data enrichment is desired.

## Documentation

For more details on how to configure and use Sirdata's server-side solution, please refer to the official documentation: [Sirdata Server-Side Documentation](https://server-side.docs.sirdata.net/sirdata-server-side/english-1)

## Support

For any questions or assistance, feel free to contact our support team at [sgtm@sirdata.com](mailto:sgtm@sirdata.com).

