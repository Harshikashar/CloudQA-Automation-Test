# CloudQA Automation Test

## Overview
This project contains a robust Selenium WebDriver automation test written in C# for the CloudQA practice form. The solution tests three form fields and is designed to handle changes in HTML element properties.

## Features
- **Robust Element Location**: Multiple locator strategies for each field
- **Error Handling**: Comprehensive try-catch blocks
- **Detailed Logging**: Console output for debugging
- **Flexible Architecture**: Easy to extend for more fields

## Tested Fields
1. **First Name** - Text input field
2. **Email** - Email input field  
3. **Country** - Dropdown selection

## Key Features for Robustness
- Multiple XPath and CSS selector strategies
- Fallback locators for element changes
- Dynamic waits for element loading
- Detailed error reporting

## Setup & Run
1. Install .NET 6.0 SDK
2. Install required NuGet packages
3. Run the test:
   dotnet run
