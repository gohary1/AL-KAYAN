# Al Kayan Group

![Al Kayan Group Logo](./docs/assets/imgs/logo.jpg)

Al Kayan Group is Company specialized in electronics and technlogy. Our website showcases our services and projects with a modern, user-friendly interface.

<div align="center">
  <img src="./docs/assets/imgs/layout (1).png" alt="WLINK Layout 1" width="48%">
  <img src="./docs/assets/imgs/layout (2).png" alt="WLINK Layout 2" width="48%">
  <img src="./docs/assets/imgs/layout (3).png" alt="WLINK Layout 2" width="48%">
</div>
## Features

- **Responsive Design**: Built with Angular for a seamless experience across devices.
- **Multilingual Support**: Utilizes ngx-translate for Arabic and English language switching.
- **Interactive UI**: Incorporates animations and visualizations for engaging user experience.
- **Contact Form**: 
  - Secure data submission with regex validation.
  - Email notifications for users and administrators.
- **Project Showcase**: Highlighting our key projects and achievements.

## Multilingual Support

Our website supports both Arabic and English languages:

- Uses ngx-translate for seamless language switching.
- Stores translations in JSON files for easy management.
- Automatically detects user's preferred language on first visit.

Example usage:
```html
<h1>{{ 'WELCOME_MESSAGE' | translate }}</h1>
```

## Contact Form

The contact form includes robust validation:

- Regex patterns ensure data integrity before submission.
- Server-side validation for an added layer of security.
- Email notifications sent to both the user and our team.

Example regex for phone number (Saudi format):
```typescript
const phonePattern = /^((?:\+966)|(?:00966)|0)?5[0-9]{8}$/;
```

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/al-kayan-group.git
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   ng serve
   ```

4. Open your browser and visit `http://localhost:4200`


## Social Media

- [Twitter](@AlKayanGroup)
- [LinkedIn](https://www.linkedin.com/company/al-kayan-group)
- [Facebook](https://www.facebook.com/AlKayanGroup)


## License

© [2024] Al Kayan Group. All rights reserved.
