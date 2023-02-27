# QR-Code-Generator-and-Printing

## Description
This is a module that generates QR codes from text input and prints them without showing a preview page using custom Java action. The QR codes are created server-side and stored in an Image object. The module uses the ZXing library and does not require any external APIs. You can find more information on the ZXing library at https://zxingnet.codeplex.com.

## usage scenario
Generate and print the QR

Skipping the Print Preview processing can save a significant amount of time. To achieve this, we can create a custom Java Action, which will enable us to meet our use case requirements efficiently.

## Dependencies
Mendix Modeler 9.18.3

## Configuration
For QR Generation:
Use the included Java action that requires two parameters: the text to be converted to a QR code and an Image object where the resulting QR code is saved.
For QR Printing:
Use the included Java action that requires only one parameters: the object to be printed.

## Screenshots
![Screenshot_10](https://user-images.githubusercontent.com/105714808/221665926-826bacbe-f581-467b-8e62-69a328381ce5.png)
![Screenshot_11](https://user-images.githubusercontent.com/105714808/221665945-aef2e3bf-641b-4536-add5-a35143ae9942.png)
![Screenshot_12](https://user-images.githubusercontent.com/105714808/221665968-df251497-8a65-4cd3-a9ea-17d12102276f.png)
![Screenshot_13](https://user-images.githubusercontent.com/105714808/221665989-288779af-2c31-4471-aca8-4e44f27c1c49.png)
![Screenshot_14](https://user-images.githubusercontent.com/105714808/221666018-5964e61d-215a-4427-b683-bad06d158f1e.png)
![Screenshot_15](https://user-images.githubusercontent.com/105714808/221666041-b685de4d-cf29-4fb6-8367-a726d642ecac.png)

