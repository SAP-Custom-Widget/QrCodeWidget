

![icon](https://raw.githubusercontent.com/SAP-Custom-Widget/QrCodeWidget/main/icon.png)

## SAP Custom Widget: Qr Code Widget
SAP Custom widget to generate and display QR Code dynamically, with colors.

![preview](https://raw.githubusercontent.com/SAP-Custom-Widget/QrCodeWidget/main/screenshot.png)

## Installation
To use this widget in your SAP application, follow these steps:

- Download the `QrCodeWidget.json` file from the URLs specified in the webcomponents property of the JSON.
- Go to your SAC Portal, select Analytic Application from the left side bar, and then go to the Custom Widget tab.
- Click on the + icon on the right side and select the `QrCodeWidget.json` file that you downloaded.
- You're done! You can now use it in your app.

## Methods
The widget has the following methods:

### Set Methods

|  Method | Parameter Type  | Description  |
| ------------ | ------------ | ------------ |
| setSize(size) | integer |  Set QR Code Width x Height |
| setData(data) | string |  Set Data for QR Code |
| setColor(color) | string |  Set QR Code Foreground Color |
| setBgcolor(bgcolor) | string |  Set QR Code Background Color |

### get Methods

|  Method | Return Type | Description  |
| ------------ | ------------ | ------------ |
| getSize()  | integer |  return QR Code Width x Height |
| getData()  | string |  return Data for QR Code |
| getColor()  | string |  return QR Code Foreground Color |
| getBgcolor()  | string |  return QR Code Background Color |

## About
This widget is developed by [Rohit Chouhan](http://linkedin.com/in/itsrohitchouhan "Rohit Chouhan")

