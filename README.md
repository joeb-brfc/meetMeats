# 🍽️ Meet Meats – Interactive Recipe Web App

This project is a responsive, Bootstrap-powered interactive recipe platform focused on meat-based dishes. It aims to connect food enthusiasts with chefs by showcasing diverse recipes, nutritional information, and user-generated ratings — all while promoting a smooth and accessible experience across devices.

## 💡 Purpose & Value

The site is built for food lovers, home cooks, and professional chefs. It provides value by:

- Highlighting chef-submitted recipes and linking them to individual chef profiles
- Offering personalised user interactivity, including recipe ratings and reviews
- Presenting nutritional and prep-time data to help users make informed choices
- Allowing users to explore healthy alternatives (e.g., swapping beef for chicken)
- Ensuring a mobile-first, accessible experience using semantic HTML and Bootstrap

---

## 🌐 Deployment Instructions

- **Live Website:** _TBC_
- **GitHub Repository:** _TBC_

### 🔧 Running the site locally:
1. Clone the repository or download it as a ZIP.
2. Extract the files if downloaded.
3. Open `index.html` in your browser.
4. No build tools or installations required — it's a static HTML/CSS/JS project.

---

## 🧭 Navigation Structure _(WIP)_

The site will be structured with the following pages:

### 1. **Home** (`index.html`)
- Welcome message
- Featured recipes carousel or cards
- Navigation links to explore all recipes or chef submissions

### 2. **All Recipes** (`recipes.html`)
- Grid or list of available meat-based recipes
- Filter/sort options (e.g., by prep time, popularity, type of meat)

### 3. **Submit Recipe / Login** (`submit.html`)
- Chef login form
- Recipe submission form visible only after login validation

### 4. **Chef Profile** (modal or `chef.html`)
- Displays chef name, bio, recipe contributions, and optional links

---

## 🧩 User Stories

### 🧑‍🍳 User Story: Chef Profile & Recognition

**As a chef**, I want my name and recipe contributions clearly displayed and linked to a simple profile, so I can build my brand and be recognised by users.

**Acceptance Criteria:**
- Each recipe shows the chef’s name and photo.
- Clicking the name shows their profile or opens a modal.
- Profile includes a short bio and optional contact link.

**Tasks:**
- Add chef metadata to the recipe data.
- Create a reusable profile component using semantic HTML.
- Link recipe cards dynamically to chef profiles.

---

### 🔁 User Story: Review Incentives

**As a returning user**, I want to earn small visual rewards for reviewing multiple recipes, so I feel encouraged to keep participating.

**Acceptance Criteria:**
- A badge or message appears after several reviews.
- Review count is stored across sessions using localStorage.

**Tasks:**
- Track reviews via localStorage or counter.
- Show visual feedback after 3 reviews.
- Use JavaScript to trigger feedback (e.g., “Thanks for 3 reviews!”).

---

### 🥦 User Story: Healthy Alternatives

**As a health-conscious user**, I want to view alternative meat options, so I can pick recipes that suit my lifestyle.

**Acceptance Criteria:**
- Recipes optionally display a meat substitution suggestion.
- Clicking the suggestion shows a related variation.

**Tasks:**
- Include alternative recipe reference in data.
- Display suggestion with a button or link.
- Use JS to show variation or navigate to another recipe.

---

### ⏱️ User Story: Prep Time & Nutrition

**As a customer**, I want to see prep time and key nutrition info on each recipe, so I can make informed decisions.

**Acceptance Criteria:**
- Each recipe shows prep time and calorie count.
- Nutrition values (protein, fat, etc.) are shown in a clear format.

**Tasks:**
- Add nutrition fields to recipe data (JSON or JS object).
- Use semantic HTML to show time/nutrition info.
- Display icons or badges for better UX.

---

### ⭐ User Story: Recipe Feedback

**As a user**, I want to rate a recipe from 1–5 stars and get confirmation, so I know my input was received.

**Acceptance Criteria:**
- Each recipe has a rating input (dropdown or stars).
- JavaScript validates input and shows confirmation message.

**Tasks:**
- Build a rating input and validation check (1–5).
- Show message like “Thanks for rating X stars.”
- Clear input after submission.

---

### 📱 User Story: Responsive & Accessible Site

**As a user**, I want the site to work smoothly on different devices and support assistive tools, so I can interact without barriers.

**Acceptance Criteria:**
- Layout adjusts for desktop, tablet, and mobile.
- Forms include labels, appropriate input types, and tab focus.

**Tasks:**
- Use Bootstrap grid and responsive utilities.
- Validate form fields (presence, type).
- Test for screen reader and keyboard navigation.

---

### 📤 User Story: Recipe Submission with Login

**As a chef**, I want to upload a recipe after logging in, so only authorised users can submit content.

**Acceptance Criteria:**
- A form accepts username and password.
- JavaScript checks credentials and shows a success alert.

**Tasks:**
- Build login form with required fields.
- Store dummy credentials in JS.
- Alert “Recipe submitted for processing” on valid login.
