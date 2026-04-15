
# AgroHelper
AgroHelper is a cross-platform gardening assistant designed to help users plan, manage, and care for their crops more efficiently. 
It combines garden planning tools, real-time weather alerts, plant data, and AI-powered diagnostics into a single application available on both web and mobile.
Try it out at:
agrohelper.org

## Features

### Garden Planner
- Create a grid-based layout of your garden
- Organize and plan crop placement visually
- Optimize space and crop rotation strategies

<img width="1900" height="862" alt="Screenshot 2026-03-31 144028" src="https://github.com/user-attachments/assets/8ebafabe-66fc-43af-a94d-9607fd19bfa6" />


### Crop Information
- Access detailed plant data via the Trefle API
- Learn about planting conditions, care requirements, and growth cycles

<img width="1919" height="856" alt="Screenshot 2026-03-31 144051" src="https://github.com/user-attachments/assets/5ad210e3-3ccf-47d0-a33b-991315b6b3fe" />


### Weather Alerts
- Location-based weather updates using OpenWeather API
- Get alerts relevant to plant health and gardening conditions

<img width="1919" height="875" alt="Screenshot 2026-03-31 144303" src="https://github.com/user-attachments/assets/1e4ab044-3316-49b8-b53a-6537d7198d5f" />


### AI Plant Doctor
- Upload plant images (currently supports up to 2MB)
- AI analyzes plant health and identifies issues
- Provides actionable care recommendations
- Powered by Gemini API

<img width="1338" height="717" alt="Screenshot 2026-03-30 182815" src="https://github.com/user-attachments/assets/ae7a8135-9383-4641-ae83-c81e008c7b33" />
<img width="1288" height="736" alt="Screenshot 2026-03-30 182947" src="https://github.com/user-attachments/assets/d993b931-a132-4837-bcd9-611dcac05bf0" />

### Authentication
- Firebase email/google account login

### Subscription System
- Free tier - 3 AI diagnoses
- Premium tier - up to 100 AI diagnoses x month (integrated with Paypal)
- Planned - google play billing for android and cross platform subscription sync

### Tech stack
- Frontend
Web: Hosted on Firebase
Mobile: Android (APK)
- Backend
Firebase (Functions, Auth, Hosting)
- APIs
Trefle API (plant data)
OpenWeather API (weather alerts)
Gemini API (AI plant diagnosis)
- Payments
PayPal API (web subscriptions)
Google Play Billing (planned)


### Future release:
Google Play Billing integration
Subscription sync across platforms
iOS version
Push notifications for weather alerts
Ability to access camera for Plant Doctor
Support larger pictures
