## Trend Chart Mendix Pluggable Widget
A Mendix widget to show trend charts based on https://github.com/unsplash/react-trend. 

<img alt="Toolbox Screenshot" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/logo.png" width="50px"/>

Quoting the [Unsplash's README](https://github.com/unsplash/react-trend?tab=readme-ov-file#react-trend), "Graphing tools are often complex, abstract, and heavy. They require domain-specific knowledge, and a significant time investment. But what if you just need a spark line that shows a trend? (...) These are very simple and elegant visualizations, and they should not require a bloated graphing library to produce."

Now, it is possible to easily build these simple trend graphs (similar to the ones shown by Github, for instance) in your Mendix application.

## Features
Easily show trending charts. Custom settings include:

*   Gradient or Solid Color;
*   Height/Padding;
*   Autodraw (Enable/Duration/Easing)
*   Stroke/Smoothing (Stroke Width, Stroke Line Cap, Smoothing Enabled, Radius)


## Usage
Feel free to check the [demo (.mpk)](https://github.com/joaodelopes/mendix-react-trend/tree/main/demo) for a better understanding.

1. Add a dataview that returns an object (root) associated with a list of objects (that contain the trend values).
2. Inside the dataview, add the Trend widget.
3. Custumize it.

### Configuration Screenshots

#### Toolbox
<img alt="Toolbox Screenshot" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/toolbox.png" width="150px"/>

#### Page Setup
<img alt="Page Setup Screenshot" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/pagesetup.png" width="300px"/>

#### Domain Model (Demo)
<img alt="Domain Model Demo" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/domainmodel.png" width="400px"/>

#### Studio Pro
![Studio Pro Screenshot](https://github.com/joaodelopes/mendix-react-trend/blob/main/images/studiopro1.png)

#### Widget's General Settings
<img alt="Widget's General Settings" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/configgeneral.png" width="500px"/>

#### Widget's Auto-Draw Settings
<img alt="Widget's Auto-Draw Settings" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/autodraw.png" width="500px"/>

#### Widget's Stroke/Smoothing Settings
<img alt="Widget's Stroke/Smoothing Settings" src="https://github.com/joaodelopes/mendix-react-trend/blob/main/images/strokesmoothing.png" width="500px"/>

## Demo Project
- [Mendix app running on the cloud](https://reacttrend-sandbox.mxapps.io/index.html)
- [Mendix demo module (.mpk)](https://github.com/joaodelopes/mendix-react-trend/tree/main/demo)

![Trend Demo](https://github.com/joaodelopes/mendix-react-trend/blob/main/images/app.png)
<!-- - [Marketplace widget](https://marketplace.mendix.com/link/component/237438) -->
<!-- - [Mendix demo scss (.scss)](https://github.com/joaodelopes/block-note-mendix/blob/main/demo/demo.scss) -->

## Issues, Suggestions and Feature Requests

*   No known issues at the moment. If you have improvement suggestions, feel free to contact us.


## About Stoneworx

<img alt="From https://www.stoneworx.nl/o" src="https://cdn.prod.website-files.com/66991b9fc069c88aec093fd1/66b242753e65840128c97ab9_imagehero-p-800.png" width="50px"/>

We started our company as friends and will always remain a club of people that likes doing business in a friendly matter. A group of entrepreneurial, smart and highly experienced Mendix professionals.  

On a daily basis, we create software applications that simplify our clients’ business processes by using the Mendix low code platform. It is our mission is to turn complex ideas into simple solutions for medium to corporate-sized businesses, in any industry.