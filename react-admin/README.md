# dbbm_web

## Table of contents

* [Create the Project (dbbm_web)](#create-the-project-dbbm-web)
* [Install Required Modules](#install-required-modules)
* [Code Setup](#code-setup)

## Create the Project <a name="create-the-project-dbbm-web"></a>

* Install Prettier extension for VScode
* Create a react App, and open the new created directory using VScode

  ```bash
  npx create-react-app react-admin
  cd react-admin
  code .
  ```

## Install Required Modules <a name="install-required-modules"></a>

* Install [Material UI](https://mui.com/material-ui/getting-started/installation/)

  ```bash
  npm install @mui/material @emotion/react @emotion/styled
  ```

* Install [Data Grid](https://mui.com/x/react-data-grid/getting-started/#installation)

  ```bash
  npm install @mui/x-data-grid
  ```

* Install [Material Icons](https://mui.com/material-ui/material-icons/)

  ```bash
  npm install @mui/icons-material
  ```

* Install React Router, React Pro Sidebar, formik and yum

  ```bash
  npm install react-router-dom@6 react-pro-sidebar@0.7.1 formik yup
  ```

* Install [Full Calendar](https://fullcalendar.io/docs/initialize-es6)

  ```bash
  npm install @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list
  ```

* Install [Nivo Charts](https://nivo.rocks/components)

  ```bash
  npm install @nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo
  ```

## Code Setup <a name="code-setup"><a>

* Delete the following files under `src` directory
  * `App.css`
  * `App.test.js`
  * `logo.svg`
  * `reportWebVitals.js`
  * `setupTests.js`

* Modify index.js, App.js

* Go to Google Fonts, search for `source sans pro`, add "Regular 400", "SemiBold 600", "Bold 700", select "@import" in "Use on the web" in the right panel, and copy the url to index.css

* Modify index.css

* Create "data" directory under "src", and copy data from GitHub

  ```bash
  wget https://raw.githubusercontent.com/ed-roh/react-admin-dashboard/master/src/data/mockData.js
  wget https://raw.githubusercontent.com/ed-roh/react-admin-dashboard/master/src/data/mockGeoFeatures.js
  ```
