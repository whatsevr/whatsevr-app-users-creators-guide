# Messaging & Chat Guide

## 1. Introduction

Welcome to Whatsevr's messaging and chat system! Our comprehensive messaging platform enables you to stay connected with friends and community members through real-time conversations.

Whatsevr supports two types of conversations:
- **Private Chats**: One-on-one direct conversations with individual users
- **Community Chats**: Group discussions with all members of a community you've joined

Key features include:
- Real-time messaging with instant delivery
- Content sharing (posts, profiles, communities)
- Message editing and deletion
- Online user tracking
- Push notifications for new messages
- Rich message bubbles with delivery status indicators
- Attachment support (currently in development)

## 2. Accessing the Messages Tab

To access your messages, follow these simple steps:

1. Open the Whatsevr app
2. Look at the bottom navigation bar
3. Tap the **Messages** icon (typically a chat bubble icon)
4. You're now in the Messages page, which displays the app bar with "Messages" title

The Messages page features two main sub-tabs:

- **Chats**: Your private one-on-one conversations with individual users
- **Communities**: Group chats from communities you've joined

[Screenshot: Messages page showing Chats and Communities tabs]

## 3. Understanding the Messages Interface

### Chats Tab

The Chats tab displays all your private conversations:
- Each chat item shows your contact's **avatar**, **name**, **last message preview**, and **timestamp**
- Conversations are typically sorted by most recent activity
- Tap any chat to open the conversation and view the full message history

### Communities Tab

The Communities tab shows all community group chats:
- Each community chat displays the **community avatar** (with a person icon badge), **community name**, **last message preview**, and **timestamp**
- Only communities you've joined appear in this list
- Tap any community to open the group chat

### Online Users Indicator

When your account is in developer or verbose mode, you'll see an **online users indicator** in the Messages page header. This shows:
- The count of currently online users (e.g., "15 online")
- A green dot indicator showing live status
- Tap this indicator to view a list of all currently online users and start conversations with them

[Screenshot: Chats tab with conversation list]
[Screenshot: Communities tab with group chats]

## 4. Starting New Conversations

### Starting a Private Chat

You can start a private chat in three ways:

**Method 1: From User Profiles**
1. Visit any user's profile (through search, recommendations, or feed)
2. Look for the **message button** or **chat icon** in their profile header
3. Tap the message button to open a conversation with that user

**Method 2: From Online Users List** (Verbose Mode)
1. Tap the online users indicator in the Messages page header (shows "X online" with green dot)
2. Browse the list of currently active users
3. Tap the **"Start Chat"** button next to any user
4. The conversation opens and you can start messaging immediately

**Method 3: From Search**
1. Use the app's search feature to find a user
2. Tap their profile from the search results
3. Tap the message button on their profile
4. The chat opens or creates if it's a new conversation

### Starting a Community Chat

1. First, you must **join a community** (see Communities documentation for details)
2. Once you've joined, the community automatically appears in your **Communities tab**
3. Tap the community chat to open the group conversation
4. You can now see all community members' messages and participate in discussions

[Screenshot: Starting private chat from user profile]
[Screenshot: Starting community chat from communities list]

## 5. Sending Messages

### Opening a Conversation

1. From the Messages page, tap either the **Chats** or **Communities** tab
2. Select any conversation from the list
3. The conversation view opens, showing the message history and composer

### Conversation Interface

The conversation screen displays:
- **Header**: Shows the chat participant's avatar, name (tappable to view their profile), and a more options menu
- **Background**: A decorative background pattern for visual appeal
- **Message History**: All messages displayed in reverse chronological order, with the newest messages at the bottom
- **Message Composer**: Located at the bottom for typing and sending messages

### Sending Text Messages

To send a message, follow these steps:

1. **Tap the text input field** in the message composer (placeholder text reads "Write a message...")
2. **Type your message** - the field supports multi-line text (press Enter for new lines)
3. **Tap the send button** - the circular button with a send icon on the right of the composer
4. Your message appears in the conversation with a delivery status indicator

> **Note**: The send button is only active when you've entered text. It will be grayed out if the field is empty.

### Message Delivery Status

Messages show delivery indicators to confirm they've been sent:
- **Clock Icon**: Message is being sent (temporary state while uploading)
- **Double Checkmark Icon**: Message successfully delivered to the recipient's device

[Screenshot: Conversation view with message composer and sent messages]

## 6. Message Composer Features

### Text Input Field

The message composer includes a text input field with these capabilities:
- **Multi-line Support**: Type messages across multiple lines (up to 5 lines visible before scrolling)
- **Automatic Expansion**: The field grows as you type
- **Placeholder Text**: "Write a message..." guides you to start typing
- **Enter Key**: Press Enter to create new lines within the message

### Send Button

The send button (circular icon on the right) enables you to:
- **Send immediately** when tapped
- **Appears grayed out** when the text field is empty
- **Activate** automatically when you start typing

### Attachment Button (In Development)

The attachment button (paperclip icon on the left) opens options for:
- **Fast Image**: Search and select images from Google (currently implemented)
- **Photo**: Select photos from your device gallery (in development)
- **Video**: Select videos from your device (in development)
- **Document**: Attach files and documents (in development)
- **Location**: Share your current location (in development)

> **Note**: Full attachment functionality is currently being developed. Some features may have limited functionality.

[Screenshot: Message composer with attachment options sheet]

## 7. Sending Images and Files (Development Feature)

### Accessing Attachments

To attach files or media to your message:

1. Tap the **attachment button** (paperclip icon) on the left side of the text composer
2. An attachments options sheet appears with available media types

### Attachment Options

Choose from the following attachment types:

- **Fast Image**: Search and select images from Google (currently the most complete feature)
- **Photo**: Select photos from your device gallery (in development)
- **Video**: Select videos from your device (in development)
- **Document**: Attach files and documents (in development)
- **Location**: Share your current location (in development)

### Sending Process

1. Select your attachment type from the options sheet
2. Choose the content you want to attach
3. The attachment appears in the message composer for preview
4. Tap the send button to deliver the message with the attachment

> **Tip**: This feature is currently being enhanced. Check back regularly for updates to attachment functionality. If you experience issues, try the Fast Image option which is fully implemented.

[Screenshot: Attachment options sheet with icons]

## 8. Sharing Content in Messages

### What You Can Share

You can share the following types of content from anywhere in the app:
- **Posts**: WTV, Flicks, Photos, Offers, Memories
- **User Profiles**: Share someone's profile with context about why
- **Community Profiles**: Invite others to communities

### How to Share

1. From any content (post, profile, or community)
2. Tap the **share button** (typically an arrow or share icon)
3. Select **"Send in Message"** or **"Share to Chat"** option
4. Choose recipient(s) from your chats or communities list
5. Add an optional message providing context
6. Tap send to deliver

### Shared Content Preview

Shared content appears in conversations with rich preview cards:
- **Thumbnail Image**: Visual representation of the content
- **Content Type Badge**: Indicates what type of content (Post, Profile, Community, etc.)
- **Short Description**: Brief text preview of the content
- **Tap to View**: Click the preview card to open and view the full content
- **Masonry Grid Layout**: Multiple shared items display in a grid if several are sent

### Managing Shared Content Before Sending

Before sending, shared content appears in an **"Attachments" preview section** above the message composer:

1. View all items you're about to send with thumbnails
2. **Remove Individual Items**: Tap the X button on any item to remove it
3. **Remove All Attachments**: Tap the X button in the header to remove everything
4. Once ready, tap send to deliver all attachments

[Screenshot: Shared content preview in conversation]
[Screenshot: Attachments section before sending]

## 9. Message Actions and Management

### Accessing Message Actions

To access actions for any message:

1. **Long-press** (tap and hold) any message bubble in the conversation
2. A message actions sheet appears with available options for that message

### Available Actions for Your Own Messages

For messages you've sent, you have these options:

- **Edit Message**
  - Tap "Edit Message" from the actions sheet
  - The message text appears in an edit dialog
  - Modify the text as needed
  - Tap "Save" to confirm changes
  - The edited message updates in the conversation

- **Unsend**
  - Tap "Unsend" to delete the message for everyone
  - The message is immediately removed from the conversation
  - Recipients will see that a message was deleted

- **Copy Text**
  - Tap "Copy Text" to copy the message content to your device clipboard
  - You can then paste it elsewhere

### Available Actions for Others' Messages

For messages received from other users:

- **Copy Text**: Copy the message content to your clipboard for reference or sharing

### Future Actions (Coming Soon)

These message actions are planned for future releases:
- **Reply to Specific Messages**: Quote and reply to individual messages in a thread
- **Forward Messages**: Share messages to other chats

[Screenshot: Message actions sheet with Edit, Unsend, and Copy options]

## 10. Understanding Message Bubbles

### Your Messages (Sent by You)

Messages you send appear with these characteristics:
- **Alignment**: Positioned on the right side of the screen
- **Background**: Dark gradient background for clear distinction
- **Text Color**: White text for contrast
- **Status Indicators**: Timestamp and delivery status (clock or checkmarks) displayed at the bottom
- **Shape**: Typically rounded corners for a modern appearance

### Others' Messages (Received)

Messages from others are styled differently:
- **Alignment**: Positioned on the left side of the screen
- **Background**: Accent color gradient background
- **Text Color**: White text for contrast
- **Information**: Shows timestamp (and sender's name in community chats)
- **Shape**: Rounded corners matching sent messages

### Community Chat Messages

In group chats, received messages include additional information:
- **Sender Avatar**: Small circular profile picture in the bottom-left corner
- **Sender Name**: The name of who sent the message
- **Tap Avatar/Name**: Click the avatar or name to view the sender's profile

### Message Content

Messages support rich content:
- **Clickable Links**: URLs in messages are linked
- **Mentions**: @mentions of other users
- **Hashtags**: #hashtags for topic organization
- **Shared Content**: Appears above the message text as preview cards
- **Read More**: Messages longer than 8 lines show a "Read more" option to expand

[Screenshot: Message bubbles showing sent and received messages]
[Screenshot: Community chat with sender names and avatars]

## 11. Online Users Feature (Verbose Mode)

### Accessing Online Users

The online users feature is available in developer or verbose mode. To access it:

1. Look for the online users indicator in the Messages page header (displays "X online" with green dot)
2. Tap this indicator to open the online users dialog
3. Browse the list of all currently active users on the platform

### Online Users Dialog

The dialog displays:

- **Header**: Shows total count (e.g., "15 user(s) online")
- **Your Profile**: Appears first in the list with an "You are online" label to identify yourself
- **Other Users**: Remaining users show "Online now" status
- **Start Chat Button**: Each user has a "Start Chat" button for quick messaging

### Starting a Chat from Online Users

To initiate a conversation from the online users list:

1. Browse the list to find a user you want to chat with
2. Tap the **"Start Chat"** button next to their name
3. The dialog closes automatically
4. A conversation with that user opens immediately
5. If you already have an active chat with this user, it opens that conversation

> **Note**: This feature is available in developer/verbose mode for testing and engagement purposes. It's a great way to connect with active community members.

[Screenshot: Online users dialog with list of active users]

## 12. Community Chats vs Private Chats

### Private Chats (One-on-One)

Private chats are direct conversations between you and another individual user:

- **Participants**: Exactly two people (you and one other user)
- **Message Visibility**: Messages are only visible to you and the recipient
- **Sender Display**: Message bubbles don't show sender names (it's obvious who sent what)
- **Header Navigation**: Tap the header to view the other user's profile
- **Use Case**: Personal conversations, direct communication with friends
- **Privacy**: More private than community chats

### Community Chats (Group)

Community chats are group conversations with all members of a community:

- **Participants**: All members of the community
- **Message Visibility**: All community members can see all messages
- **Sender Display**: Received messages show sender's avatar and name for clarity
- **Header Navigation**: Tap the header to view community details and member list
- **Use Case**: Group discussions, community announcements, collaborative conversations
- **Moderation**: Community owners can moderate and manage discussions

### Key Differences Table

| Feature | Private Chat | Community Chat |
|---------|--------------|----------------|
| **Participants** | 2 (you + 1 other) | Multiple (all community members) |
| **Message Visibility** | Private to 2 people | Visible to all members |
| **Sender Display** | No name shown | Sender name and avatar shown |
| **Header Tap** | View user profile | View community details |
| **Notifications** | 1-on-1 notifications | Group notifications |
| **Use Case** | Personal conversations | Group discussions |
| **Moderation** | None needed | Community owners can moderate |

[Screenshot: Private chat conversation interface]
[Screenshot: Community chat with sender information]

## 13. Conversation Navigation and Features

### Scroll to Bottom

When you scroll up in a long conversation to view older messages:

1. If you've scrolled up more than 1000 pixels from the bottom
2. A floating action button (FAB) appears in the bottom-right corner
3. The button displays a down arrow icon
4. Tap the FAB to instantly scroll back to the latest messages
5. The FAB disappears once you're viewing the most recent messages

### View Profiles

To quickly access profile information:

1. Tap any avatar in the conversation header or message bubbles
2. Or tap the name in the conversation header
3. For private chats: Opens the other user's profile
4. For community chats: Opens the community's profile page
5. View their information and interact with their content

### More Options Menu

The three-dot menu in the conversation header provides access to:
- Additional conversation settings (future features)
- Conversation preferences
- More options as they become available

### Background Pattern

Conversations feature:
- **Decorative Background**: A subtle pattern for visual appeal
- **Overlay**: A semi-transparent overlay for better readability of messages
- **Purpose**: Creates a cohesive, polished appearance while maintaining focus on content

[Screenshot: Conversation with scroll-to-bottom FAB visible]

## 14. Message Notifications

### Push Notifications

Receive real-time alerts for new messages when your app is in the background or closed:

- **Notification Badge**: A number badge appears on the app icon (platform-dependent)
- **Lock Screen Alert**: Notification appears on your device lock screen
- **Notification Center**: Notification is added to your device notification center

### Notification Content

Each notification displays:

- **Sender's Name**: Who sent the message
- **Sender's Profile Picture**: Visual identification
- **Message Preview**: The first line of the message text
- **Tap Action**: Tap the notification to open that conversation directly

### Enabling Notifications

To receive message notifications:

1. **Device Settings**: Ensure push notifications are enabled in your device settings
2. **App Permissions**: Grant notification permissions when the app first requests them
3. **Automatic Registration**: The app automatically registers your device for Firebase Cloud Messaging
4. **Verify**: Check that Whatsevr has notification permissions in your device settings

### Managing Notification Preferences

To customize what notifications you receive:

1. Open the Whatsevr app
2. Tap your **Account** tab (usually at the bottom navigation)
3. Navigate to **Settings**
4. Look for **Notification Settings** or **Message Preferences**
5. Customize which types of messages trigger notifications
6. Save your preferences

### In-App Indicators

Whatsevr shows visual indicators for unread messages:

- **Chat Tab Badge**: An unread message count appears on the Chats tab icon
- **Bold Conversation Names**: Chats with unread messages appear in bold text in your chat list
- **Timestamp Updates**: The latest message timestamp shows when the last activity occurred
- **Visual Feedback**: Helps you quickly identify which chats have new messages

[Screenshot: Push notification for new message]

## 15. Privacy and Safety Tips

### Protecting Your Privacy

Be mindful of the information you share in messages:

- **Avoid Sensitive Information**: Don't share personal details like phone numbers, home addresses, or financial information in messages
- **Photo Privacy**: Be cautious about sharing personal or sensitive photos; only share with people you trust
- **Document Security**: Don't share sensitive documents or files with strangers
- **Community Awareness**: Remember that community chat messages are visible to all community members
- **Privacy Settings**: Review your account's privacy settings to control who can message you

### Staying Safe

Protect yourself from harmful content and interactions:

- **Suspicious Links**: Don't click links sent by users you don't know or trust
- **Identity Verification**: Verify the identity of users before sharing sensitive information
- **Malicious Content**: Report suspicious files or links to the support team
- **Personal Information**: Never share passwords, authentication codes, or banking details
- **Unexpected Requests**: Be wary of unusual requests or "too good to be true" offers

### Blocking Users

If a user sends inappropriate or unwanted messages:

1. Visit the user's profile
2. Tap the **three-dot menu** in their profile header
3. Select **"Block User"**
4. **Result**: Blocked users cannot send you messages, see your profile, or interact with your content
5. You can unblock users from your privacy settings if needed

### Reporting Issues

Help keep the community safe by reporting problematic behavior:

1. **Report a Message** (if available): Long-press a problematic message and select "Report"
2. **Report a User**:
   - Visit the user's profile
   - Tap the three-dot menu
   - Select "Report User"
3. **Report Community Issues**: Report inappropriate community behavior to community owners or platform support
4. **Provide Details**: Include as much context as possible to help the support team investigate

### Community Chat Safety

Special considerations for group conversations:

- **Community Moderation**: Community owners can moderate messages and remove members
- **Report Inappropriate Behavior**: Report issues to community owners or platform support
- **Leave Communities**: Leave communities that don't align with your values or have an unsafe environment
- **Community Guidelines**: Follow all community rules and guidelines to maintain a safe space

## 16. Best Practices for Messaging

### Communication Etiquette

Foster positive interactions through good messaging habits:

- **Be Respectful and Kind**: Always communicate respectfully with others
- **Clear Communication**: Use clear, concise language so your message is understood
- **Avoid Message Flooding**: Don't send too many messages in quick succession
- **Respect Response Time**: Don't expect immediate replies; people have their own schedules
- **Think Before Sending**: Consider the impact of your words before hitting send

### Group Chat Etiquette

Community chats require extra consideration:

- **Stay On Topic**: Keep discussions relevant to the community's purpose
- **No Spam**: Don't send irrelevant, promotional, or duplicate content
- **Follow Guidelines**: Respect all community rules and guidelines
- **Sparse Mentions**: Use @mentions sparingly to avoid flooding people with notifications
- **Quality Over Quantity**: Contribute meaningfully rather than sending numerous low-value messages

### Content Sharing

When sharing content with others:

- **Relevance**: Only share content that's relevant and interesting to the conversation
- **Ask Permission**: Ask before sharing promotional content or business-related material
- **Respect Copyrights**: Don't share copyrighted material without proper rights
- **Privacy**: Never share others' private information, photos, or personal details without permission
- **Context**: Provide context explaining why you're sharing the content

### Response Time

Understand delivery versus read status:

- **Delivery Status**: The checkmarks mean the message was delivered to the recipient's device, not that they've read it
- **Processing Time**: Messages may take a few seconds to deliver depending on connection speed
- **Busy Users**: People may be busy and can't respond immediately; be patient
- **Urgent Matters**: For urgent communication, consider calling or using other methods in addition to messaging

## 17. Troubleshooting Common Issues

### Messages Not Sending

If your messages fail to send:

1. **Check Connection**: Verify you have a stable WiFi or cellular data connection
2. **Block Status**: Ensure the recipient hasn't blocked you
3. **Restart App**: Force-close the app completely and reopen it
4. **Clear Cache**: Go to device Settings → Apps → Whatsevr → Storage → Clear Cache
5. **Update App**: Ensure you're running the latest version of the Whatsevr app
6. **Message Content**: Verify the message isn't excessively large or contains problematic content

### Not Receiving Messages

If you're missing incoming messages:

1. **Check Connection**: Verify your internet connection is stable and active
2. **Notifications**: Check that push notifications are enabled in device settings
3. **Block List**: Verify you haven't accidentally blocked the sender
4. **Restart App**: Close and reopen the app to refresh connections
5. **Device Settings**: Check that Whatsevr has notification permissions in your device settings
6. **Disable Airplane Mode**: Ensure Airplane Mode is off on your device

### Cannot Start a Chat

If you're unable to initiate a conversation:

1. **Block Status**: Verify the user hasn't blocked you
2. **Account Status**: Ensure your account is in good standing (not banned or restricted)
3. **Login**: Confirm you're logged in properly with your correct credentials
4. **Restart**: Close and restart the app
5. **Clear Data**: In extreme cases, try signing out and back in
6. **Support**: Contact support if the issue persists

### Attachments Not Working

Attachment features are currently in development:

1. **Fast Image**: The Fast Image search feature should work - try that first
2. **Storage**: Check that the app has storage permission in device settings
3. **Device Space**: Ensure you have enough available storage on your device
4. **File Size**: Try smaller files if you're having trouble with large files
5. **Format**: Try different file types if one isn't working
6. **Alternative**: For now, sharing via Fast Image is the most reliable method

### Messages Appearing Out of Order

If messages seem scrambled:

1. **Connection Issues**: Poor internet can cause out-of-order delivery
2. **Wait**: Allow a moment for messages to sync properly
3. **Refresh**: Pull down in the conversation to manually refresh
4. **Restart**: Close and reopen the conversation
5. **Persistent Issue**: If this continues, report to support for investigation

### Cannot Edit or Delete Messages

If edit or delete options aren't available:

1. **Your Messages Only**: You can only edit/delete your own messages
2. **Long-press**: Ensure you're long-pressing the message bubble properly
3. **Restart**: Try restarting the app - UI bugs can prevent options from showing
4. **Time Limit**: Some messages may have a time limit for editing (check app policies)
5. **Message Type**: Some special message types (shared content) may have limitations

### Online Status Not Updating

If your online status isn't showing correctly:

1. **Connection**: Online status requires an active internet connection
2. **App State**: The app must be open and in active use for online status to work
3. **Background Restrictions**: Check device battery optimization settings - they may restrict the app in the background
4. **Permissions**: Verify the app has necessary permissions in device settings
5. **Restart**: Try closing and reopening the app

## 18. Tips for Effective Messaging

### Organize Your Chats

Keep your messaging organized and efficient:

- **Use Search**: The app's search function helps you find specific conversations quickly
- **Regular Review**: Periodically check both Chats and Communities tabs for important messages
- **Future Features**: Watch for archive and mute features (coming soon) to organize further

### Engagement

Build stronger connections through active messaging:

- **Share Content**: Share interesting posts from your feed to start meaningful conversations
- **Online Users**: Use the online users feature to connect with active community members
- **Participate**: Engage in community chats to build relationships and find like-minded people
- **Contribute**: Add value to group discussions with thoughtful messages

### Content Sharing

Make the most of the content sharing feature:

- **Preview First**: Check shared content before sending to ensure it's appropriate
- **Add Context**: Explain why you're sharing content and what makes it relevant
- **Review Attachments**: Use the attachments preview section to review everything before sending
- **Organize**: Group related shared items together in a single message

### Managing Conversations

Navigate and manage your conversations efficiently:

- **Scroll Button**: Use the scroll-to-bottom FAB for quick navigation in long chats
- **Edit Instead**: Use message editing to correct typos rather than sending corrections
- **Copy Important Info**: Use the copy feature to save important information from messages
- **Profile Taps**: Quickly access user profiles by tapping names and avatars

## 19. Future Features (Coming Soon)

Whatsevr's messaging system is constantly evolving. Look forward to these upcoming features:

- **Chat Requests**: Accept or decline message requests from users you don't follow
- **Message Reactions**: React to messages with emoji reactions
- **Reply to Specific Messages**: Quote and reply to individual messages in a thread
- **Forward Messages**: Share messages to other chats
- **Voice Messages**: Record and send audio messages
- **Video Messages**: Record and send short video messages
- **Read Receipts**: See exactly when messages have been read
- **Typing Indicators**: See when someone is typing a response
- **Message Search**: Search within conversations for specific text
- **Chat Archive**: Archive old conversations to declutter your chat list
- **Mute Conversations**: Silence notifications for specific chats
- **More Attachment Types**: Full support for photos, videos, documents, and location sharing

## 20. Next Steps

Now that you understand Whatsevr's messaging features, explore related topics:

- **[Communities](06-communities.md)** - Learn about community features and group interactions
- **[Profile & Account Management](08-profile-and-account.md)** - Manage your profile and privacy settings
- **[Notifications & Alerts](09-notifications-and-alerts.md)** - Customize your notification preferences
- **[Engaging with Content](05-engaging-with-content.md)** - Learn about sharing content and social interactions

Happy messaging! Stay connected with your community and build meaningful relationships through Whatsevr's powerful messaging platform.
