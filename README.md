# Accessibility Widget

## Introduction

This script provides an accessibility widget for websites. It offers various options to improve readability and control.

## Features

* Title bar with language toggle  
* High contrast mode  
* Dark mode  
* Dyslexia friendly font  
* Reading mask  
* Cursor reading aid  
* Underline links  
* Hide images  
* Highlight headings  
* Adjustable font size  
* Adjustable line height  
* Adjustable letter spacing  
* Content scaling  
* Column width setting  
* Focus outline  
* Reduced motion  
* Large cursor  
* Stop autoplay  
* Invert colors  

## Installation

Copy the script file to your project  
Add this code before closing the body tag  

    <script src="path/to/accessibilityWidget.js"></script>
    <script>
      initAccessibilityWidget()
    </script>

## Usage

Open the widget panel by clicking the accessible icon at the bottom right of your site  
Use toggles and sliders to adjust settings in real time  
Changes are saved locally in the browser  

## Why this exists

This widget was created in response to the new European Accessibility Act available at  
https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/union-equality-strategy-rights-persons-disabilities-2021-2030/european-accessibility-act_en  
I had certain projects that could not be updated easily to meet the new requirements. Commercial services offered similar widgets but their pricing was not realistic and they did not comply with European data protection regulations. These services load various widgets from servers in the United States which needlessly harms the privacy of visitors and end users. I decided to build something of my own that is free and easy to integrate. It was developed specifically for a Flarum forum but works on most websites and aims to cover all major accessibility needs. My time is limited but I welcome bug reports and suggestions and will add improvements over time.

## Configuration

Open the script file and update the WIDGET_CONFIG object  
Use storageKey to set a unique key for local storage  
Set defaultLang to choose initial language  
Edit translations to add or modify labels for each language

## Contributing

Thanks for your interest  
* Fork the repository  
* Create a new branch with your feature or fix  
* Open a pull request and describe your changes clearly

## License

This project is licensed under the GNU General Public License version 2  
See the LICENSE file for details  
