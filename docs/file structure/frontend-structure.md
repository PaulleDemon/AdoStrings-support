# File structure for frontend

```
.
└── license.txt/
    ├── README.md
    ├── src/
    │   ├── serviceWorkerRegistration.js
    │   ├── pages/
    │   │   ├── sidebar.js
    │   │   ├── views/
    │   │   │   ├── story-view.js
    │   │   │   └── search-view.js
    │   │   ├── main-routes.js
    │   │   ├── tabs/
    │   │   │   ├── stories/
    │   │   │   │   └── stories.js
    │   │   │   ├── people/
    │   │   │   │   ├── peoples-tab.js
    │   │   │   │   ├── request-category.js
    │   │   │   │   └── people.js
    │   │   │   ├── profile/
    │   │   │   │   ├── stories-tab.js
    │   │   │   │   ├── remarks-tab.js
    │   │   │   │   ├── profile.js
    │   │   │   │   ├── links-tab.js
    │   │   │   │   ├── achievement-tab.js
    │   │   │   │   └── skills-tab.js
    │   │   │   └── charts/
    │   │   │       └── charts.js
    │   │   └── registration/
    │   │       ├── login.js
    │   │       ├── authorization-components.js
    │   │       └── signup.js
    │   ├── constants/
    │   │   ├── lengths.js
    │   │   ├── endpoints.js
    │   │   └── file.js
    │   ├── css/
    │   │   ├── index.css
    │   │   └── mobile.css
    │   ├── index.js
    │   ├── reportWebVitals.js
    │   ├── service-worker.js
    │   ├── utils/
    │   │   ├── formatted-number.js
    │   │   ├── url-validation.js
    │   │   ├── linkify.js
    │   │   ├── hooks.js
    │   │   ├── datetime.js
    │   │   ├── image.js
    │   │   ├── image-compress.js
    │   │   └── random.js
    │   ├── install-prompt.js
    │   ├── errors/
    │   │   └── errors.js
    │   ├── icons/
    │   │   ├── png
    │   │   ├── svg/
    │   │   │   ├── share.svg
    │   │   │   ├── more-options.svg
    │   │   │   ├── next.svg
    │   │   │   ├── heart.svg
    │   │   │   ├── tick.svg
    │   │   │   ├── eye-closed.svg
    │   │   │   ├── input-clear.svg
    │   │   │   ├── upload.svg
    │   │   │   ├── comment.svg
    │   │   │   ├── menu.svg
    │   │   │   ├── search.svg
    │   │   │   ├── emoji.svg
    │   │   │   ├── down-caret.svg
    │   │   │   ├── back.svg
    │   │   │   ├── media.svg
    │   │   │   ├── edit.svg
    │   │   │   ├── reply.svg
    │   │   │   ├── eye-opened.svg
    │   │   │   ├── send.svg
    │   │   │   ├── close.svg
    │   │   │   ├── dropdown.svg
    │   │   │   └── write.svg
    │   │   └── sidebar-icons/
    │   │       ├── profile.svg
    │   │       ├── people.svg
    │   │       ├── story.svg
    │   │       └── charts.svg
    │   ├── illustrations/
    │   │   └── errors/
    │   │       ├── no-connection.svg
    │   │       ├── 404.svg
    │   │       └── not-found.svg
    │   ├── components/
    │   │   ├── cropper/
    │   │   │   ├── cropper.js
    │   │   │   ├── cropper-container.js
    │   │   │   └── slider.js
    │   │   ├── header.js
    │   │   ├── modals/
    │   │   │   ├── story-create.js
    │   │   │   ├── request-modal.js
    │   │   │   ├── info-modal.js
    │   │   │   └── category-request-modal.js
    │   │   ├── loading.js
    │   │   ├── private-route.js
    │   │   ├── input-components.js
    │   │   ├── tabs.js
    │   │   ├── emoji-list.json
    │   │   ├── cards/
    │   │   │   ├── post-card.js
    │   │   │   ├── category-card.js
    │   │   │   └── user-card.js
    │   │   ├── emoji-component.js
    │   │   ├── select-dropdown.js
    │   │   ├── zoomable-image.js
    │   │   └── more-options.js
    │   ├── apis/
    │   │   ├── category.js
    │   │   ├── story.js
    │   │   ├── user.js
    │   │   ├── authorization.js
    │   │   └── base.js
    │   ├── auth-navigation.js
    │   ├── sounds/
    │   │   └── wistle.mp3
    │   ├── App.js
    │   └── redux/
    │       ├── userSlice.js
    │       └── store.js
    ├── .github/
    │   └── ISSUE_TEMPLATE/
    │       ├── feature_request.md
    │       └── bug_report.md
    ├── package-lock.json
    ├── public/
    │   ├── index.html
    │   ├── favicon.ico
    │   ├── logo192.png
    │   ├── manifest.json
    │   ├── robots.txt
    │   ├── logo512.png
    │   ├── maskable_icon.png
    │   └── logo.svg
    ├── designs/
    │   ├── peopleknome-people.png
    │   ├── storiesknome-stories.png
    │   └── profileknowme.png
    ├── .env-cmdrc.json
    ├── package.json
    └── .gitignore
```