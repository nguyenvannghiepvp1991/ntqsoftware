# 🔋 Smart Battery - Landing Page

Official high-converting landing page for the Android app **Smart Battery - Charge Monitor** (`com.batterydoctor.chargemaster`).

Google Play Store listing: [Download Smart Battery on Google Play Store](https://play.google.com/store/apps/details?id=com.batterydoctor.chargemaster)

---

## 🌟 Landing Page Highlights

1. **Cyber Dark Mode & Neon Glow Aesthetic**: Modern high-tech UI designed to maximize app conversion rates across mobile, tablet, and desktop devices.
2. **Interactive Phone Mockup**: Real-time animated SVG battery gauge, turbo charging wattage indicator, and diagnostic metrics.
3. **Live Interactive Battery Simulator**:
   - Allows visitors to slide the battery level from **1% to 100%**.
   - Toggle **Plug In / Unplug** cable simulator.
   - **Realistic Audible Alarms**: Powered by the browser's native **Web Audio API** (zero external MP3 downloads required). Triggers alarm sounds at 100% full charge or when clicking the sound test button.
4. **Bento Grid Feature Showcase**: 6 core app features (Real-Time Wattage/Current, Anti-Overcharge Alarm, Thermal Diagnostics, Remaining Time Estimates, Cycle History, Hardware Specs).
5. **Social Proof & Community Feedback**: Prominently displays the **4.7★ rating**, **100K+ installs**, and user testimonials.
6. **Accordion FAQ & Developer Contact**: Answers frequent questions (why 80% cutoff matters, background battery efficiency, zero data tracking) and provides developer support contact (`anhquanabs@gmail.com`).
7. **100% GitHub Pages Ready**: Pure HTML5 + Tailwind CSS CDN, requiring zero build steps, bundlers, or server setups.

---

## 🚀 How to Deploy to GitHub Pages (100% Free)

You can host this website on the internet for free using **GitHub Pages** in just a few minutes:

### Step 1: Create a New Repository on GitHub
1. Log in to [GitHub](https://github.com).
2. Click **New** (or the **`+`** icon in the top right corner).
3. Name your repository, e.g., `smart-battery` or `charge-monitor-landing`.
4. Set visibility to **Public**.
5. **Do NOT** check *"Add a README file"* or *"Add .gitignore"* (we already initialized them locally).
6. Click **Create repository**.

---

### Step 2: Push Local Files to GitHub

Open PowerShell or Command Prompt inside `d:\Node Project\landing-page` and execute:

```bash
# 1. Add your GitHub repository remote URL (replace with your repo link):
git remote add origin https://github.com/<your-username>/<your-repo-name>.git

# 2. Push to the main branch
git push -u origin main
```

---

### Step 3: Enable GitHub Pages

1. In your GitHub repository page, navigate to the **Settings** tab.
2. In the left sidebar, click **Pages** (under *Code and automation*).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Choose `main` and keep the `/ (root)` folder.
   - Click **Save**.
4. Wait about **1 - 2 minutes**, then refresh the Pages tab. GitHub will display your live website URL:
   ```text
   https://<your-username>.github.io/<your-repo-name>/
   ```

---

## 🛠️ Customization & Next Steps

- **Custom Domain**: Under *Settings > Pages > Custom domain*, you can point your own domain name (e.g., `smartbattery.app`).
- **Google Play Developer Console**: Add your live website URL to your app's store listing under the **Developer contact details** section to boost SEO and trust.
- **Instant Updates**: Any time you edit `index.html`, simply run:
  ```bash
  git add .
  git commit -m "update landing page"
  git push
  ```
  GitHub Pages will rebuild and update your site automatically within 30 seconds.
