# [Argon Dashboard React](https://demos.creative-tim.com/argon-dashboard-react?ref=adr-github-readme) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/home?status=Argon%20Dashboard%20is%20a%20Free%20Bootstrap%204,%20React%20and%20Reactstrap%20Dashboard%20made%20using%20create-react-app%20%E2%9D%A4%EF%B8%8F%0Ahttps%3A//demos.creative-tim.com/argon-dashboard-react%20%23react%20%23reactstrap%20%23createreactapp%20%23argon%20%23argondesign%20%23reactdashboard%20%23argonreact%20%23reactdesign%20%23bootstrap%20%23material%20%23design%20%23uikit%20%23freebie%20%20via%20%40CreativeTim)


 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg)  ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/argon-dashboard-react.svg?maxAge=2592000)](https://github.com/creativetimofficial/argon-dashboard-react/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/argon-dashboard-react.svg?maxAge=2592000)](https://github.com/creativetimofficial/argon-dashboard-react/issues?q=is%3Aissue+is%3Aclosed) [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim-general/Lobby) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)


# Ngetest
- Jalankan RESTFUL API NodeJS Healt-care ( npm run dev / npm run start)
- lalu start Engine Frontend nya npm run start 
- edit .env isi API_URL=localhost:5000/login karena ingin mencoba API login saja
- setup di file /src buat file constant.js sebagai inialisasi url API
- buat folder baru /services dan berisi Api.js dan Auth.js untuk mengolah data dari urlAPI menjadi data yang bisa digunakan dan di olah pada frontend
- Edit views dengan Login & Dashboard, gunakan class di login.jsx untuk melakukan kondisi dan beberapa logic yang bila sukses akan menuju halamana dashboard /admin 

---

## Quick start

- `npm i argon-dashboard-react`
- [Download from Github](https://github.com/creativetimofficial/argon-dashboard-react/archive/master.zip).
- [Download from Creative Tim](https://www.creative-tim.com/product/argon-dashboard-react?ref=adr-github-readme).
- Install with [Bower](https://bower.io/?ref=creativetim): ```bower install argon-dashboard-react```.
- Clone the repo: `git clone https://github.com/creativetimofficial/argon-dashboard-react.git`.


## Documentation
The documentation for the Material Kit is hosted at our [website](https://demos.creative-tim.com/argon-dashboard-react/documentation/overview).


## File Structure
Within the download you'll find the following directories and files:

```
Argon Dashboard React
.
├── Documentation
│   └── documentation.html
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── LICENSE
├── README.md
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── assets
    │   ├── css
    │   │   ├── argon-dashboard-react.css
    │   │   ├── argon-dashboard-react.css.map
    │   │   └── argon-dashboard-react.min.css
    │   ├── fonts
    │   │   └── nucleo
    │   ├── img
    │   │   ├── brand
    │   │   ├── icons
    │   │   │   └── common
    │   │   └── theme
    │   ├── scss
    │   │   ├── argon-dashboard-react.scss
    │   │   ├── bootstrap
    │   │   │   ├── mixins
    │   │   │   └── utilities
    │   │   ├── core
    │   │   │   ├── alerts
    │   │   │   ├── avatars
    │   │   │   ├── badges
    │   │   │   ├── buttons
    │   │   │   ├── cards
    │   │   │   ├── charts
    │   │   │   ├── close
    │   │   │   ├── custom-forms
    │   │   │   ├── dropdowns
    │   │   │   ├── footers
    │   │   │   ├── forms
    │   │   │   ├── headers
    │   │   │   ├── icons
    │   │   │   ├── list-groups
    │   │   │   ├── maps
    │   │   │   ├── masks
    │   │   │   ├── mixins
    │   │   │   ├── modals
    │   │   │   ├── navbars
    │   │   │   ├── navs
    │   │   │   ├── paginations
    │   │   │   ├── popovers
    │   │   │   ├── progresses
    │   │   │   ├── separators
    │   │   │   ├── tables
    │   │   │   ├── type
    │   │   │   ├── utilities
    │   │   │   └── vendors
    │   │   ├── custom
    │   │   └── react
    │   └── vendor
    │       ├── @fortawesome
    │       │   └── fontawesome-free
    │       │       ├── LICENSE.txt
    │       │       ├── css
    │       │       ├── js
    │       │       ├── less
    │       │       ├── scss
    │       │       ├── sprites
    │       │       ├── svgs
    │       │       │   ├── brands
    │       │       │   ├── regular
    │       │       │   └── solid
    │       │       └── webfonts
    │       └── nucleo
    │           ├── css
    │           └── fonts
    ├── components
    │   ├── Footers
    │   │   ├── AdminFooter.jsx
    │   │   └── AuthFooter.jsx
    │   ├── Headers
    │   │   ├── Header.jsx
    │   │   └── UserHeader.jsx
    │   ├── Navbars
    │   │   ├── AdminNavbar.jsx
    │   │   └── AuthNavbar.jsx
    │   └── Sidebar
    │       └── Sidebar.jsx
    ├── index.js
    ├── layouts
    │   ├── Admin.jsx
    │   └── Auth.jsx
    ├── routes.js
    ├── variables
    │   └── charts.jsx
    └── views
        ├── Index.jsx
        └── examples
            ├── Icons.jsx
            ├── Login.jsx
            ├── Maps.jsx
            ├── Profile.jsx
            ├── Register.jsx
            └── Tables.jsx
```


## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">



## Resources
- Demo: <https://demos.creative-tim.com/argon-dashboard-react/#/admin/index?ref=adr-github-readme>
- Download Page: <https://www.creative-tim.com/product/argon-dashboard-react?ref=adr-github-readme>
- Documentation: <https://demos.creative-tim.com/argon-dashboard-react/#/documentation/overview?ref=adr-github-readme>
- License Agreement: <https://www.creative-tim.com/license?ref=adr-github-readme>
- Support: <https://www.creative-tim.com/contact-us?ref=adr-github-readme>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/argon-dashboard-react/issues?ref=creativetim)
- **Kit:**

| HTML | Vue |
| --- | --- |
| [![Argon Design System  HTML](https://github.com/creativetimofficial/public-assets/blob/master/argon-design-system/argon-design-system.jpg?raw=true)](https://www.creative-tim.com/product/argon-design-system) | [![Vue Argon Design System](https://github.com/creativetimofficial/public-assets/blob/master/vue-argon-design-system/vue-argon-design-system.jpg?raw=true)](https://www.creative-tim.com/product/vue-argon-design-system) |

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Material Kit. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Kit. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/?ref=adr-github-readme).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing

- Copyright 2018 Creative Tim (https://www.creative-tim.com/?ref=adr-github-readme)

- Licensed under MIT (https://github.com/creativetimofficial/argon-dashboard-react/blob/master/LICENSE.md?ref=creativetim)

## Useful Links

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w?ref=creativetim)
- [Affiliate Program](https://www.creative-tim.com/affiliates/new?ref=adr-github-readme) (earn money)
- [Blog Creative Tim](http://blog.creative-tim.com/?ref=adr-github-readme)
- [Free Products](https://www.creative-tim.com/bootstrap-themes/free?ref=adr-github-readme) from Creative Tim
- [Premium Products](https://www.creative-tim.com/bootstrap-themes/premium?ref=adr-github-readme) from Creative Tim
- [React Products](https://www.creative-tim.com/bootstrap-themes/react-themes?ref=adr-github-readme) from Creative Tim
- [Angular Products](https://www.creative-tim.com/bootstrap-themes/angular-themes?ref=adr-github-readme) from Creative Tim
- [VueJS Products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes?ref=adr-github-readme) from Creative Tim
- [More products](https://www.creative-tim.com/bootstrap-themes?ref=adr-github-readme) from Creative Tim
- Check our Bundles [here](https://www.creative-tim.com/bundles?ref=adr-github-readme)

### Social Media

Twitter: <https://twitter.com/CreativeTim?ref=creativetim>

Facebook: <https://www.facebook.com/CreativeTim?ref=creativetim>

Dribbble: <https://dribbble.com/creativetim?ref=creativetim>

Instagram: <https://www.instagram.com/CreativeTimOfficial?ref=creativetim>
