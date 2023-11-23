# Install

`npm install`

---

# Things to add

- Create a config folder with a `.env` file and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - CLOUD_NAME = `your cloudinary cloud name`
  - CLOUD_API_KEY = `your cloudinary api key`
  - CLOUD_API_SECRET = `your cloudinary api secret`
  - MS_COMPUTER_VISION_SUBSCRIPTION_KEY = `your Microsoft Subscription Key`
  - MS_COMPUTER_VISION_ENDPOINT = `your Microsoft Computer Vision Endpoint`
  - MS_FACE_ENDPOINT = `your Microsoft Face Endpoint`
  - MS_FACE_SUB_KEY = `your Microsoft Face Key`

---

# Run

`npm start`

# Project Description

This app uses a Microsoft Azure Computer Vision machine learning api to detect brands in an image. The app currently just displays the brand name(s) on screen, but it could be modified into any workflow where images are uploaded and then analyzed for their brand content.
