---
layout: home
pageClass: home-page

hero:
  name: "The Dotfiles Installer"
  image:
    src: /com.ml4w.dotfilesinstaller.svg
    alt: Linux logo
    style: "width: 200px; height: auto;"  
  tagline: Install Dotfiles easily, fast and secure. 
  actions:
    - theme: brand
      text: Get Started
      link: /getting-started/overview
    - theme: alt
      text: Install
      link: /getting-started/install
    - theme: alt
      text: GitHub ↗
      link: https://github.com/mylinuxforwork/dotfiles-installer

features:
  - title: Installation Wizzard
    details: Easy to use and guided installation wizzard of multiple dotfiles in parallel
  - title: Backup and Protect
    details: Backup of existing configuration and protection of your personal customization
  - title: Publish your Dotfiles
    details: The integrated development workflow supports you to create and publish your personal dotfiles for everyone
---

### 1. Install the Dotfiles Installer App

Install the Dotfiles Installer App from Flathub:

<a href='https://flathub.org/apps/com.ml4w.dotfilesinstaller' target="_blank">
    <img width='240' alt='Get it on Flathub' src='https://flathub.org/api/badge?locale=en'/>
</a>

### 2. Load the .dotinst

Copy the path to the `.dotinst` file into the Load Configuration entry field, click on Load and follow the installation wizzard.

<img
  src="/mainscreen-dark.png"
  alt="preview"
  style="max-width: 900px; width: 100%; border-radius: 12px; margin: 2rem auto; display: block;"
/>

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, var(--vp-c-purple-3), var(--vp-c-brand-3));
  --vp-home-hero-image-filter: blur(44px);

  --overlay-gradient: color-mix(in srgb, var(--vp-c-brand-1), transparent 40%);
}

.dark {
  --overlay-gradient: color-mix(in srgb, var(--vp-c-brand-1), transparent 75%);
}

.home-page {
  background:
    linear-gradient(200deg, transparent 25%, var(--overlay-gradient) 55%, transparent 85%),
    radial-gradient(ellipse at 80% 180%, var(--overlay-gradient), transparent 60%),
    var(--vp-c-bg);
  background-repeat: no-repeat;
  background-size: cover;

  .VPFeature a {
    font-weight: bold;
    color: var(--vp-c-brand-2);
  }

  .VPFooter {
    background-color: transparent !important;
    border: none;
  }

  .VPNavBar {
    background-color: transparent !important;
    -webkit-backdrop-filter: blur(16px);
    backdrop-filter: blur(16px);

    div.divider {
      display: none;
    }
  }
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>
