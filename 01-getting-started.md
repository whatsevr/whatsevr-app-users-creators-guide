# Getting Started with Whatsevr

## Introduction

Welcome to **Whatsevr**, a comprehensive social media platform that connects you with friends, communities, and engaging content. Whether you're here to share your authentic moments through **WTV videos**, enjoy quick entertainment via **Flicks**, participate in vibrant **Communities**, get behind-the-scenes access with **Sneekpeek**, or chat with our AI assistant, Whatsevr has something for everyone.

### Key Features

- **WTV Videos**: Long-form video content for sharing your stories and experiences
- **Flicks**: Short-form vertical videos for quick, entertaining moments
- **Communities**: Join or create communities around shared interests
- **Sneekpeek**: Exclusive behind-the-scenes content from creators
- **AI Chat (EvrMind)**: Intelligent chat assistant for conversations and assistance
- **Messaging & Calls**: Connect with friends through real-time chat and video calls
- **Multi-Account Support**: Manage multiple accounts seamlessly on one device

### App Availability

Whatsevr is available on both **Android** and **iOS** platforms. Download from the Google Play Store or Apple App Store to get started.

---

## App Launch & Splash Screen

When you first launch the Whatsevr app, you'll be greeted with a welcoming splash screen experience.

### Initial Experience

1. **App Opens**: The app starts and displays the Whatsevr logo with a welcome message
2. **Message Displayed**: You'll see the text "Your Social Journey Starts Now"
3. **Automatic Check**: The app automatically checks for any previously saved session (takes approximately 2 seconds)
4. **Next Navigation**: Based on the result, you'll be directed to either:
   - **Dashboard** (if previously logged in)
   - **Login/Signup Page** (if no active session)

[Screenshot: Splash screen with Whatsevr logo and "Your Social Journey Starts Now" message]

---

## Account Creation (New Users)

If you're creating a Whatsevr account for the first time, follow these steps:

### Step 1: Access the Login Page

When you launch the app without an active session, you'll land on the **Login/Signup Page**. This page displays:
- The Whatsevr app logo
- A prominent "Login New Account" button
- Links to Terms of Service and Privacy Policy at the bottom

[Screenshot: Login page with app logo, "Login New Account" button, and Terms/Privacy links]

### Step 2: Initiate Authentication

Tap the **"Login New Account"** button to start the authentication process. This triggers the OTPless authentication service, which handles secure verification through multiple methods.

### Step 3: Choose Authentication Method

You'll see the **OTPless authentication screen** with several provider options:
- **WhatsApp**: Authenticate using your WhatsApp account
- **Phone Number**: Verify using your mobile number (recommended for easier verification)
- **Email**: Verify using your email address

Select the method that works best for you.

[Screenshot: OTPless authentication screen with provider options (WhatsApp, Phone, Email)]

### Step 4: Verify OTP

After selecting your authentication method:
1. **Enter Information**: Provide your phone number or email address
2. **Receive OTP**: A One-Time Password will be sent to your chosen method
3. **Enter OTP**: Input the OTP code in the verification field
4. **Verify**: The system verifies your OTP

### Step 5: Create Account Dialog (New Users)

If your phone number or email isn't already registered:
1. The **"Create Account" dialog** will appear
2. Your mobile number or email address will be shown (read-only)
3. You'll see a text field labeled **"Name"**

[Screenshot: Create Account dialog showing mobile/email (read-only) and name input field]

### Step 6: Enter Your Name

Enter your display name with the following requirements:
- **Minimum Length**: At least 4 characters
- **Maximum Length**: Up to 50 characters
- This name will be your public display name on the platform

### Step 7: Complete Account Creation

Tap the **"Continue"** button to proceed with account creation.

### Step 8: Processing

You'll see a loading state with the message **"Creating account..."** as the system processes your registration.

### Step 9: Automatic Login

After successful account creation, you'll be automatically logged in—no need to enter credentials again!

### Step 10: Welcome to Dashboard

You'll be redirected to the **Dashboard** with five main tabs at the bottom:
- **Explore**: Discover trending content and creators
- **Home**: Your personalized activity feed
- **Chats**: Messaging and conversations
- **Alerts**: Notifications and activity updates
- **Account**: Your user profile

[Screenshot: Dashboard with bottom navigation showing 5 tabs]

> **Tip**: We recommend starting with the Account tab to complete your profile setup for better discoverability.

---

## Login (Existing Users)

If you already have a Whatsevr account, logging in is quick and straightforward.

### Step 1: Start Authentication

From the Login/Signup page, tap the **"Login New Account"** button.

### Step 2: Verify Your Identity

Complete the OTPless authentication process:
1. Select your authentication method (WhatsApp, Phone, or Email)
2. Provide the verified phone number or email associated with your account
3. Enter the OTP sent to your chosen method
4. The system verifies your credentials

### Step 3: Automatic Login Detection

Once your account is verified:
- The system detects that this account already exists
- Your session is automatically created
- No additional login step is needed

### Step 4: Session Loading

You may see a loading state with the message **"Checking session..."** as the system:
- Retrieves your account information
- Registers your device for push notifications (Firebase Cloud Messaging)
- Prepares your personalized content feed

### Step 5: Dashboard Access

You're logged in! You'll be redirected to the **Dashboard** with all your personalized content and features ready to use.

> **Note**: Enabling push notifications in your device settings ensures you receive real-time alerts about likes, comments, messages, and other activities.

---

## Account Switching

One of Whatsevr's powerful features is the ability to manage multiple accounts from a single device. This is perfect if you have personal, professional, or creator accounts.

### Understanding the User Switch Panel

On the **Login/Signup page**, you'll find the **User Switch Panel** below the "Login New Account" button. This panel displays all previously logged-in accounts on your device:

[Screenshot: User Switch Panel showing multiple saved accounts with profile pictures, names, and follower counts]

### Account Information Displayed

For each saved account, you'll see:
- **Profile Picture**: The account's avatar
- **User Name**: The account's display name
- **Status Indicator**: 
  - "Last Login" for the most recently active account
  - "Followers: X" for other saved accounts
- **Switch Button**: An action button to switch to that account

### Switching to a Saved Account

Follow these steps to switch to a previously logged-in account:

**Step 1: Locate Your Account**
Scroll through the User Switch Panel to find the account you want to switch to.

**Step 2: Tap "Switch to Account"**
Press the switch button on your desired account card.

**Step 3: Wait for Switching**
A loading state will appear with the message **"Switching..."** as the system:
- Switches your active session
- Loads your account data
- Prepares your personalized content

**Step 4: Access Dashboard**
You'll be automatically redirected to the Dashboard with your switched account active.

> **Important**: Account switching is prevented when you have an active call in progress. End any ongoing calls before switching accounts.

### Adding a New Account

To add a new account on your device:

1. **Tap "Add New Account"** button (visible in the User Switch Panel)
2. The current user is logged out
3. You're returned to the fresh Login/Signup page
4. Follow the login/account creation process for the new account

This new account will then appear in your User Switch Panel for future quick switching.

### Removing a Saved Account

To remove a saved account from your device (does not delete the account):

1. **Locate the account** in the User Switch Panel
2. **Tap the "X" icon** on the account card
3. **Confirm logout** in the warning dialog that appears
4. The account is removed from your device's saved accounts list

> **Important**: This action removes the account from your device only. The account itself remains active and can be logged in to from another device or the web.

---

## Account Switching from Dashboard

You can also switch accounts while logged into the app (without going to the login screen):

### Accessing Account Switch from Within the App

1. Navigate to the **Account tab** (rightmost tab in bottom navigation)
2. Tap the **Settings button** (menu icon)
3. Look for the **"Switch Account"** or **"Manage Accounts"** option
4. This opens the account switching modal showing your saved accounts

[Screenshot: Account switching modal from within the app]

### The Switching Process

The switching process from the app is identical to switching from the login screen:
1. Select the account you want to switch to
2. Confirm the action
3. Wait for the "Switching..." loading state
4. The app redirects you to the Dashboard with the switched account

---

## Special Account States

Whatsevr has safety measures in place to protect the platform. You may encounter special account states in certain situations.

### Banned Account

If your account has been banned:

1. **Dialog Appears**: When attempting to login, you'll see an **"Account is banned"** dialog
2. **Reason**: The dialog explains that your account has been flagged for violating community guidelines
3. **Message**: Additional context about why the ban occurred may be provided

[Screenshot: Account banned dialog with contact support button]

**Next Steps:**
- Tap the **"Contact Support"** button to open a support form
- Explain your situation and request an account review
- The support team will investigate and respond to your appeal

### Deactivated Account

If you or the system has deactivated your account:

1. **Dialog Appears**: You'll see an **"Account is in deactivated state"** dialog
2. **Context**: This typically happens when you've requested account deactivation or the system detected suspicious activity
3. **Options**: You'll see an option to contact support

[Screenshot: Account deactivated dialog with contact support button]

**Reactivation Process:**
- Tap the **"Contact Support"** button
- Explain your situation and request account reactivation
- The support team will guide you through the reactivation process
- Provide any necessary verification to restore access

---

## First-Time User Experience

Congratulations on creating your Whatsevr account! Here's what awaits you on the Dashboard.

### Dashboard Overview

Your main hub is the Dashboard, featuring five tabs at the bottom navigation:

[Screenshot: Dashboard tabs highlighted]

#### 1. **Explore Tab**
Discover trending content, popular creators, and recommended communities. Perfect for exploring what's happening on Whatsevr.

#### 2. **Home Tab**
Your personalized activity feed showing:
- Content from creators you follow
- Posts from your communities
- Trending content tailored to your interests

#### 3. **Chats Tab**
All your messaging and conversations:
- Direct messages with friends
- Group chats
- Access to voice and video calls

#### 4. **Alerts Tab**
Notifications about:
- New likes and comments on your content
- Friend requests and follows
- Messages and mentions
- Community activity

#### 5. **Account Tab** (Profile)
Your user profile showing:
- Profile picture and cover media
- Account statistics (likes, followers, connections)
- Content organized by type
- Profile editing options

### Recommended First Steps

1. **Start with the Account Tab**: Complete your profile setup to ensure better discoverability
2. **Upload a Profile Picture**: Personalize your account
3. **Write a Bio**: Tell others about yourself
4. **Explore Communities**: Join communities that match your interests
5. **Follow Creators**: Start following content creators you enjoy

---

## Profile Setup Basics

Let's complete your profile setup to make the most of your Whatsevr experience.

### Navigating to Your Profile

Tap the **Account tab** (rightmost tab in the bottom navigation) to access your profile page.

### Profile Page Layout

Your profile page displays:

[Screenshot: Account page showing profile picture, name, stats, and action buttons]

**Profile Elements:**
- **Profile Picture**: Your avatar (tap to view memories if any)
- **Cover Media**: Background image or video at the top of your profile
- **Name & Username**: Your display name and unique username
- **Statistics**: 
  - Total likes received
  - Number of followers
  - Friends/connections count
- **Upload Button**: Plus icon to create new content
- **Settings Button**: Menu icon for account settings and profile editing

### Updating Your Profile Picture

**Steps:**
1. Tap the **profile picture area** in the top section of your profile
2. Options appear to:
   - Select an image from your gallery
   - Take a new photo with your camera
   - View existing memories (if any)
3. Select or capture an image
4. **Crop & Adjust**: Fine-tune the image using the crop tool
5. **Save**: The new profile picture is saved to your account

> **Tip**: Use a clear, recognizable photo for your profile picture to attract followers and build credibility.

### Updating Your Cover Media

**Steps:**
1. Tap the **cover media area** at the top of your profile
2. Options appear to upload a photo or video
3. Select media from your gallery or capture new content
4. **Adjust**: Crop or frame the media as desired
5. **Set as Cover**: Confirm to set it as your profile cover

### Editing Profile Information

**Steps:**
1. Tap the **Settings button** (menu icon) on your profile page
2. Look for options like **"Edit Profile"** or **"Update Profile"**
3. Access profile editing view to update:
   - **Bio**: Write about yourself (who you are, interests, etc.)
   - **Location**: Your city or region
   - **Website**: Link to your personal website or portfolio
   - **Occupation**: Your profession or role
   - **Status**: Your current status (e.g., "Creator," "Student," "Professional")
4. Make changes and tap **Save**

### Changing Your Username

**Steps:**
1. Open **Settings** from your profile page
2. Navigate to **"Update Username"** or **"Change Username"** option
3. Enter your desired new username
4. The system checks availability in real-time
5. If available, tap **"Save"** to confirm the change

> **Note**: Username availability is subject to Whatsevr's guidelines. Usernames must be unique and follow platform policies.

---

## Profile Tabs Overview

Your profile features multiple tabs organizing your content and information. After updating your profile picture and cover, explore these sections:

[Screenshot: Profile tabs showing different content sections]

### Available Profile Tabs

**1. About Tab**
- Bio and personal description
- Work experience and employment history
- Education background
- Personal interests and information
- Contact details (if you choose to share)

> **Recommendation**: Fill out the About section first as it's the first thing visitors see.

**2. Services Tab** (Portfolio Accounts)
- Available only for portfolio/professional accounts
- Services you offer (if you're a service provider)
- Service descriptions, pricing, and booking information

**3. Media Tab**
- All your mixed content posts
- Photos and videos together
- Sorted by date (newest first)

**4. Videos/WTV Tab**
- Long-form video content specifically
- Your WTV uploads
- Detailed video posts with descriptions

**5. Flicks Tab**
- Short-form vertical videos
- Entertainment-focused quick content
- Your Flicks uploads

**6. Offerings Tab**
- Promotional offers and deals
- Limited-time promotions you're running
- Exclusive deals for your followers

**7. PDF Tab** (Portfolio Accounts)
- Document uploads
- Portfolios, certificates, resumes
- Professional documentation

**8. Tags Tab**
- Content where you've been mentioned or tagged
- Posts by other users featuring you
- Community of people tagging you

### Profile Completion Checklist

To maximize your visibility and engagement:

- ✓ Profile picture uploaded
- ✓ Cover media set
- ✓ Name and username set
- ✓ Bio written in About tab
- ✓ At least one piece of content uploaded
- ✓ Communities joined (at least one)
- ✓ Privacy settings configured

---

## Terms of Service & Privacy Policy

Before fully engaging with Whatsevr, please review our important policies:

### Where to Find Them

- **Login Screen**: Links are available at the bottom of the Login/Signup page
- **App Settings**: Policies can also be accessed from Settings → Legal

### What You Need to Know

By continuing to use Whatsevr, you agree to:
- The **Terms of Service**: Your rights and responsibilities as a user
- The **Privacy Policy**: How we collect, use, and protect your data

We strongly recommend reading these documents to understand:
- Community guidelines and prohibited behavior
- Your privacy rights and data protection
- Intellectual property and content ownership
- Dispute resolution procedures

---

## Troubleshooting Common Issues

Having trouble getting started? Here are solutions for common problems:

### Authentication Failed

**Problem**: You see an error message during OTP verification or authentication.

**Solutions:**
1. **Check Internet Connection**: Ensure you have a stable, active internet connection
2. **Verify Information**: Double-check that your phone number or email is correct
3. **Wait and Retry**: Sometimes temporary issues occur—wait a few moments and try again
4. **Clear Cache**: Go to app settings and clear the app cache (Settings → Apps → Whatsevr → Storage → Clear Cache)
5. **Contact Support**: If the issue persists, reach out through the Support section with error details

### OTP Not Received

**Problem**: You don't receive the OTP after requesting it.

**Solutions:**
1. **Check Spam Folder**: For email OTPs, check your spam or junk folder
2. **Verify Contact Info**: Confirm your phone number or email address is entered correctly
3. **Request New OTP**: Use the "Resend OTP" button and try again
4. **Network Check**: Ensure you have cellular data or WiFi enabled
5. **Contact Support**: If you've tried multiple times, contact support—they may need to resend manually

### Account Switching Not Working

**Problem**: You can't switch to another account or get stuck during switching.

**Solutions:**
1. **End Active Calls**: Ensure no voice or video calls are currently in progress
2. **Check Connection**: Verify stable internet connectivity
3. **Force Quit App**: Close the app completely (force stop) and reopen it
4. **Clear Cache**: Clear app cache through device settings
5. **Restart Device**: Restart your phone and try again
6. **Contact Support**: If still unresolved, contact support with details

### Cannot Create Account

**Problem**: Account creation fails with an error message.

**Solutions:**
1. **Check Name Length**: Verify your name is between 4-50 characters
2. **Avoid Duplicates**: Your phone number or email might already be registered—try logging in instead
3. **Internet Stability**: Ensure stable internet throughout the creation process
4. **Clear Cookies**: Clear app data (not app cache) in Settings → Apps → Whatsevr → Storage → Clear Data
5. **Reinstall App**: Delete and reinstall the app if issues persist
6. **Contact Support**: Provide error message details to support team

### App Stuck on Splash Screen

**Problem**: The app opens but stays on the splash screen indefinitely.

**Solutions:**
1. **Wait**: The authentication check takes about 2 seconds—wait a bit longer
2. **Force Close**: Force close the app and reopen (Settings → Apps → Whatsevr → Force Stop)
3. **Connection Check**: Verify internet connectivity
4. **Clear Cache**: Settings → Apps → Whatsevr → Storage → Clear Cache
5. **Reinstall**: If nothing else works, uninstall and reinstall the app
6. **Device Restart**: Restart your phone completely and try launching again

### Cannot Switch Accounts During Active Call

**Problem**: The "Switch Account" option is disabled or grayed out.

**Solutions:**
1. **End Current Call**: Finish or hang up on the active call first
2. **Check for Background Calls**: Some calls may be on hold—end those too
3. **Wait for Call to Disconnect**: Sometimes it takes a moment for the system to register the call ended
4. **Restart App**: Force close and reopen the app after ending calls

---

## Tips for New Users

### Profile & Discoverability

- Complete your profile information in the **About tab** for better search visibility
- Upload a profile picture as it significantly increases engagement
- Write a compelling bio that describes who you are and what content you share
- Join communities related to your interests to get discovered by like-minded users

### Content Exploration

- Explore the **Explore tab** to discover trending content and popular creators
- Follow users whose content aligns with your interests
- Save content you like for later viewing
- Comment and engage with content from other users to build community

### Community Engagement

- Join communities that match your interests and values
- Participate actively by commenting and sharing your thoughts
- Respect community guidelines and other members
- Report inappropriate content or behavior

### Notifications & Settings

- Enable push notifications in your device settings for real-time alerts
- Customize notification preferences in app settings
- Review privacy settings to control who can see your profile and content
- Block or mute users if needed to maintain a positive experience

### Account Security

- Use a strong, unique device lock (PIN/password/biometric)
- Don't share your OTP with anyone
- Enable two-factor authentication if available
- Review login activity periodically in account settings

---

## Next Steps

Now that you've set up your account and learned the basics, explore these additional resources:

- **[Creating Video Content](02-creating-video-content.md)**: Learn how to create and upload WTV videos and Flicks
- **[Discovering Content](04-discovering-content.md)**: Find and explore content that interests you
- **[Communities](06-communities.md)**: Create and manage communities, or join existing ones
- **[Profile & Account Management](08-profile-and-account.md)**: Advanced profile customization and account settings

Happy exploring! 🎉
