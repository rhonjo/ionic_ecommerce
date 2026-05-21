# ionic_ecommerce

Ionic e-commerce mobile app built with Ionic 3 and Angular 5.

## Overview

This repository contains an Ionic 3 mobile application for a simple e-commerce store. It includes UI pages, navigation, theming, and assets configured for mobile development.

## Features

- Ionic 3 + Angular 5 application structure
- Mobile-ready UI layout and navigation
- Product listing and home page
- Basic theming using SCSS
- Built for Android and iOS platforms via Ionic/Cordova

## Project Structure

- `src/app/` — app module, root component, and bootstrap files
- `src/pages/` — page components, markup, and styles
- `src/assets/` — icons, images, and static assets
- `src/theme/` — app theming and variables
- `config.xml` — Cordova configuration
- `ionic.config.json` — Ionic app configuration

## Installation

```bash
npm install
```

## Development

```bash
ionic serve
```

## Build

```bash
ionic cordova build android
ionic cordova build ios
```

## Notes

- This app is based on Ionic 3 and Angular 5, which are older framework versions.
- For modern Ionic development, consider upgrading to the latest Ionic and Angular versions.
