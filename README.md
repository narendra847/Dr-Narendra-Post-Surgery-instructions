# Dr Narendra - Post Operative Instructions Website

## 🏥 Overview
This website provides post-operative care instructions for surgical procedures. It features a clean, patient-friendly interface with graphical elements and easy-to-understand language.

**Current Website:** https://d611q5m6.scispace.co

---

## 📋 Current Procedures
1. **Laparoscopic Cholecystectomy** (Gallbladder Removal)
2. **Inguinal Hernia Repair** (Groin Hernia)
3. **Hiatal Hernia Repair**
4. **Fundoplication** (Anti-Reflux Surgery)
5. **Umbilical Hernia Repair** (Belly Button Hernia)
6. **Endoscopy** (Upper Gastrointestinal Endoscopy)

---

## ➕ How to Add New Procedures

### Step 1: Create the Instruction Page
1. Copy one of the existing HTML files (e.g., `cholecystectomy.html`) as a template
2. Rename it to match your new procedure (e.g., `appendectomy.html`)
3. Update the content:
   - Change the page title in `<title>` tag
   - Update the procedure name in the header
   - Modify the "What Was Done" section
   - Adjust procedure-specific instructions
   - Update any special diet or activity restrictions

### Step 2: Add the Procedure Card to the Home Page
1. Open `index.html`
2. Find the commented template section (marked with `<!-- TEMPLATE FOR ADDING NEW PROCEDURES -->`)
3. Copy the template code
4. Uncomment it and customize:
   - **href**: Link to your new HTML file (e.g., `href="appendectomy.html"`)
   - **Icon color**: Choose from the color options listed in comments (e.g., `bg-teal-100 / text-teal-600`)
   - **Icon**: Select an appropriate Font Awesome icon (e.g., `fa-capsules`)
   - **Display name**: Patient-friendly name (e.g., "Appendix Removal")
   - **Technical name**: Medical procedure name (e.g., "Laparoscopic Appendectomy")

### Step 3: Deploy the Updated Website
After adding new files:
1. Upload all files to your web server
2. Test the links to ensure the new procedure page loads correctly
3. Verify mobile responsiveness

---

## 🎨 Customization Options

### Available Colors for New Procedure Cards:
- `bg-blue-100 / text-blue-600` (Blue)
- `bg-teal-100 / text-teal-600` (Teal)
- `bg-pink-100 / text-pink-600` (Pink)
- `bg-yellow-100 / text-yellow-600` (Yellow)
- `bg-indigo-100 / text-indigo-600` (Indigo)
- `bg-cyan-100 / text-cyan-600` (Cyan)
- `bg-green-100 / text-green-600` (Green - currently used)
- `bg-purple-100 / text-purple-600` (Purple - currently used)
- `bg-orange-100 / text-orange-600` (Orange - currently used)
- `bg-red-100 / text-red-600` (Red - currently used)

### Available Font Awesome Icons:
- `fa-procedures` - Surgery table
- `fa-user-md` - Doctor
- `fa-heartbeat` - Heart monitor
- `fa-stethoscope` - Stethoscope
- `fa-syringe` - Injection
- `fa-capsules` - Pills
- `fa-hospital` - Hospital building
- `fa-notes-medical` - Medical notes
- `fa-briefcase-medical` - Medical briefcase
- `fa-first-aid` - First aid kit
- `fa-band-aid` - Bandage

---

## 📝 Example: Adding a New Procedure

Here's an example of adding "Appendectomy" instructions:

### 1. Create `appendectomy.html`:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Appendix Removal - Post-Op Instructions | Dr Narendra</title>
    <!-- Copy rest of header from existing file -->
</head>
<body>
    <!-- Update content for appendectomy -->
</body>
</html>
```

### 2. Add to `index.html`:
```html
<a href="appendectomy.html" class="procedure-card bg-white rounded-2xl shadow-lg p-8 block">
    <div class="flex items-center mb-4">
        <div class="bg-teal-100 p-4 rounded-full mr-4">
            <i class="fas fa-capsules text-teal-600 text-3xl"></i>
        </div>
        <h2 class="text-2xl font-bold text-gray-800">Appendix Removal</h2>
    </div>
    <p class="text-gray-600 mb-4">Laparoscopic Appendectomy</p>
    <div class="flex items-center text-blue-600 font-semibold">
        <span>View Instructions</span>
        <i class="fas fa-arrow-right ml-2"></i>
    </div>
</a>
```

---

## 📱 Features
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Icon-Based Navigation**: Visual cues for each procedure
- **Print-Friendly**: All instruction pages can be printed as PDFs
- **Accessible**: Clear language and large, readable text
- **Modern UI**: Clean, professional appearance using Tailwind CSS

---

## 🛠️ Technical Details
- **Framework**: HTML5, Tailwind CSS (CDN), Font Awesome Icons
- **No Backend Required**: Static website, easy to host anywhere
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

---

## 📞 Support
For questions or assistance with updating the website, contact your web administrator or the original developer.

---

## 📦 Files Included
- `index.html` - Home page with procedure selection
- `cholecystectomy.html` - Gallbladder removal instructions
- `inguinal-hernia.html` - Groin hernia repair instructions
- `hiatal-hernia.html` - Hiatal hernia repair instructions
- `fundoplication.html` - Fundoplication instructions
- `umbilical-hernia.html` - Umbilical hernia repair instructions
- `endoscopy.html` - Endoscopy post-procedure instructions
- `README.md` - Technical documentation
- `SHARING-INSTRUCTIONS.md` - Guide for sharing and hosting the website

---

**Last Updated:** February 2026  
**Website:** https://d611q5m6.scispace.co (preview only - see SHARING-INSTRUCTIONS.md for public hosting)
