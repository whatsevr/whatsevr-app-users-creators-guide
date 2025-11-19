# Communities

## 1. Introduction

Communities are groups of users centered around shared interests, professions, locations, or causes. They provide a dedicated space where like-minded people can connect, share content, collaborate, and build meaningful relationships.

### Purpose and Benefits

- **Connect**: Find and engage with people who share your interests, profession, or location
- **Share**: Post content and updates relevant to your community
- **Collaborate**: Work together on projects, ideas, and initiatives within your community
- **Build**: Establish a network and reputation within your professional or interest-based circles

### Types of Communities

Communities can be either **Public** or **Private**:

- **Public Communities**: Members can join instantly without requiring owner approval
- **Private Communities**: New members must send a join request and wait for the community owner's approval

### Community Roles

- **Owner**: Has full control over the community, including member management, profile editing, content posting, and community moderation
- **Member**: Can view community content, participate in discussions, and (if owner allows) post content to the community

---

## 2. Discovering Communities

### Accessing Communities

1. Navigate to the Communities section from your app's main menu
2. You'll see the **New Community** page displaying available communities

### Browsing Communities

Communities are displayed in a masonry grid layout showing:
- Community profile picture
- Community title
- Member count
- Community status (professional status badge)

### Features

- **Pull-to-Refresh**: Swipe down to reload and see updated communities
- **Infinite Scroll**: Automatically loads more communities as you scroll down
- **Community Cards**: Tap any community card to view full details

![Screenshot: Communities list with masonry grid layout](placeholder-screenshot.png)

---

## 3. Creating a New Community

### Step-by-Step Guide

1. **Access Creation Modal**: Tap the **"Create A New Community"** button on the New Community page

2. **Enter Community Name**: 
   - Type your community name (max 40 characters)
   - Tip: Choose an engaging title that clearly reflects your community's purpose

3. **Select Status**:
   - Choose from the professional status list
   - This helps categorize your community

4. **Set Privacy Settings**:
   - Choose **Public** (instant join) or **Private** (requires approval)
   - Private communities show "Require admin approval to join?" with Yes/No choice chips
   - If you select "Yes", community members will need owner approval to join

5. **Create**: Tap the **CREATE** button
   - You'll be automatically directed to your new community's details page

![Screenshot: Community creation modal](placeholder-screenshot.png)

### Best Practices

- Use a clear, descriptive name that reflects your community's purpose
- Choose the privacy setting that matches your community's needs
- Private communities are ideal for exclusive professional groups or vetted membership networks
- Public communities are better for open discussions and widespread discovery

---

## 4. Joining and Leaving Communities

### Joining a Community

#### Public Communities
1. Find a community in the Communities list or search results
2. Tap the **Join** button on the community card or details page
3. You are instantly added as a member and can view all community content

#### Private Communities
1. Find a community in the Communities list or search results
2. Tap the **Join** button on the community card or details page
3. A **join request** is sent to the community owner
4. Your button status will show **"Pending"** while awaiting approval
5. Once the owner approves, you become a member
6. If declined, the join request is rejected and you can try again

> **Tip**: Private communities may show additional context about approval requirements. You can view the join request message or status by tapping the pending button.

### Leaving a Community

1. On the community details page, tap the **Leave** button (visible to members)
2. Confirm your choice when prompted
3. You will immediately be removed from the community and lose access to member-only content

### Understanding Join Requests

- **Pending Status**: Your join request is waiting for owner approval (shown with "Pending" button state)
- **Cancel Request**: You can cancel your pending join request by tapping the "Pending" button and selecting **Cancel**
- **Approval**: Once the owner approves, you'll be added to the community automatically

> **Note**: The join/leave workflow is handled by the `JoinLeaveCommunityBloc` state manager, which ensures your request status is always synchronized with the server.

---

## 5. Viewing Community Details

### Community Profile Layout

When you open a community, you'll see:

1. **Cover Media**: Full-width banner showing community cover image or video
2. **Profile Section**:
   - Profile picture (tap to view full-size, long-press for gallery view)
   - Memories indicator showing community stories
   - Community title
   - Username
   - Member count
3. **Action Buttons**:
   - **Share**: Share the community via deep link
   - **Chat**: Open direct community chat conversation
   - **Join/Leave**: Join or leave the community

### Interactions

- **Tap Member Count**: View all community members, pending join requests, and restricted members (owner-only)
- **Long-Press Profile Picture**: View the full-size community profile image
- **Tap Memories**: View community stories in the story player
- **Tab Navigation**: Switch between About, Services, Media, Videos, Offers, and Tags tabs

![Screenshot: Community details page](placeholder-screenshot.png)

---

## 6. Community Tabs Explained

### About Tab

The About tab displays comprehensive community information:

- **Status Badge**: Professional status indicator
- **Services Preview**: Quick view of community services with "View all" link to Services tab
- **Bio**: Community focus or expertise (with rich text support)
- **Location**: Community location/office/landmark
- **Created On**: Community creation date
- **Description**: Detailed community purpose, guidelines, and call-to-action (with rich text support)

### Services Tab

- View the complete list of community services
- Each service displays:
  - Service title
  - Service description
- Services are managed by community owners through the edit profile page

### Media Tab

- Mixed content feed showing all media posted to the community
- Includes: photos, videos, offers, and memories
- Tap content to view or interact with it

### Videos Tab

- WTV (Whatsevr Television) videos posted to the community
- View video details and engage with content

### Offers Tab

- Promotional offers posted to the community
- View offer details and take action

### Tags Tab

- Content where the community has been tagged or mentioned
- Shows cross-community engagement and reach

---

## 7. Community Member Management (For Owners)

Community owners can manage members by accessing the member management page.

### Accessing Members Page

1. On the community details page, tap the **member count** (e.g., "234 Members")
2. The member management page opens with three tabs: Members, Requests, and Restricted

### Members Tab

**View All Members:**
- Displays all active community members
- Each member shows: profile picture, name, portfolio title, and role badge (owner/member)
- Tap a member to view their full profile

**Member Actions (Owner Only):**
1. Tap the **three-dot menu** next to a member
2. Choose:
   - **Remove**: Immediately remove the member from the community
   - **Restrict**: Ban the member from the community (appears in Restricted tab)

### Requests Tab (Private Communities Only)

For private communities, this tab shows:
- **Pending Join Requests**: Users who have requested to join
- Member information: profile picture, name, portfolio title
- **Join request message** from the requester
- **Timestamp** of the request
- Action buttons:
  - **Accept**: Approve the join request and add them to members
  - **Decline**: Reject the join request

### Restricted Tab

- View members you have restricted/banned from the community
- Each restricted member shows status badges
- **Unrestrict Button**: Remove restrictions and allow them to join again

### Additional Features

- **Pull-to-Refresh**: Swipe down to reload member lists
- **Pagination**: Automatically loads more members as you scroll
- **Member Roles**: Badges clearly indicate owner vs. regular member status

![Screenshot: Member management page](placeholder-screenshot.png)

---

## 8. Posting Content to Communities

### Uploading Content

1. On the community details page (owner-only in edit mode), tap the **Upload** button
2. A content upload bottom sheet appears with options:
   - **WTV**: Post videos
   - **Flick**: Post short video clips
   - **Photo**: Post images
   - **Memory**: Post temporary stories
   - **Offer**: Post promotional offers
   - **PDF**: Post documents

3. Select your content type and follow the upload flow

### Community as Posting Context

- When creating content, you can select the community as the posting context
- Your content will appear in the community's relevant tabs (Media, Videos, Offers, etc.)
- Community members will see your posts in the community feed

### Content Visibility

- **Public Communities**: All app users can see community content
- **Private Communities**: Only community members can see posted content

> **Cross-Reference**: For detailed content creation instructions, see [Creating Video Content](02-creating-video-content.md) and [Creating Other Content](03-creating-other-content.md).

---

## 9. Updating Community Profile (For Owners)

Community owners can customize their community profile to make it more engaging and informative.

### Accessing Edit Mode

1. On the community details page, tap the **pencil (edit) icon**
2. The edit community page opens with all customizable fields

### Profile Picture

- Tap to change your community profile picture
- Choose from camera or gallery
- Square aspect ratio with circular cropper UI
- Confirm your selection after cropping

### Community Title

- Update the community name (max 40 characters)
- Multiline text field
- Tip: Use clear, engaging language that reflects your community's purpose

### Bio

- Text field (max 300 characters)
- Describe your community's focus, expertise, or movement
- Use rich text formatting for better presentation

### Privacy Settings

- Toggle between Public and Private
- Private communities show "Require admin approval to join?" with Yes/No choice chips
- Changing this affects how new members can join

### Cover Media

- **Add/Remove Cover Images**: Set landscape/16:9 aspect ratio images
- **Add/Remove Cover Videos**: Include videos with thumbnail selection
- **Multiple Cover Media**: Support for multiple cover photos and videos
- Tap media items to preview or delete

### Username

- Edit your community's unique username
- Tap to access dedicated username update page
- Type-safe navigation ensures valid usernames

### Description

- Multiline text field (max 300 characters)
- Include your community's purpose, guidelines, and call-to-action
- Supports rich text formatting

### Location

- Text field (max 100 characters)
- Specify home office, landmark, city, or country
- Help members understand your community's geographic context

### Status

- Select from the professional status list
- Update your community's professional category

### Services

- Add services relevant to your community
- Each service has:
  - **Title**: Service name
  - **Description**: Service details
- Services appear in the Services tab and About tab preview
- **Remove Icon**: Delete services by tapping the remove button

### Saving Changes

1. Review all your changes
2. Tap the **UPDATE** button
3. All changes are saved and the community details page refreshes

![Screenshot: Edit community profile page](placeholder-screenshot.png)

> **Reference**: Implementation details available in `lib/legacy_presentation/features/update_community_profile/views/page.dart`

---

## 10. Community-Specific Features

### Chat with Community

- Tap the **Chat** button on the community details page
- Opens a direct community chat conversation
- All members can participate in community-wide discussions
- Owner can moderate chat and manage discussions

### Share Community

- Tap the **Share** button
- Generate a shareable deep link to your community
- Invite others via messaging, social media, or email
- Recipients can directly access your community from the link

### Community Memories (Stories)

- Owners can post temporary stories to the community
- Stories appear on the community profile with a memories indicator
- Tap the memories indicator to view stories in the story player
- Stories have expiration dates and disappear automatically

### Owner-Only Features

- **Content Upload**: Post videos, photos, offers, and documents
- **Profile Editing**: Customize community appearance and information
- **Member Management**: Accept/decline join requests, remove or restrict members
- **Community Settings**: Adjust privacy and visibility options

### Community Notifications

Receive notifications for:
- New members joining your community
- New content posted to your community
- Member join requests (private communities)
- Messages in community chat
- Member activity and engagement

---

## 11. Best Practices and Community Guidelines

### Creating Engaging Communities

- **Clear Purpose**: Define what your community is about in the title and description
- **Compelling Bio**: Write a brief, engaging bio that explains your community's value
- **Professional Image**: Use a high-quality profile picture and cover media
- **Complete Profile**: Fill out all fields to help users understand your community

### Setting Privacy Appropriately

- **Use Public** for: general interest groups, professional networks, industry discussions
- **Use Private** for: exclusive teams, vetted networks, sensitive discussions, specialized groups

### Active Community Management

- **Respond to Join Requests**: Approve requests promptly to keep momentum
- **Welcome New Members**: Engage with new members and encourage participation
- **Post Regularly**: Share relevant content to keep your community active
- **Moderate Behavior**: Remove or restrict members who violate community guidelines
- **Clear Guidelines**: Communicate community rules in the description

### Engaging Community Members

- Post relevant, high-quality content regularly
- Respond to member questions and comments
- Highlight member contributions and achievements
- Foster positive, inclusive discussions
- Host events or challenges to increase engagement

### Building a Positive Community Culture

- Set a tone of respect and inclusivity from the start
- Welcome diverse perspectives and ideas
- Address conflicts professionally and fairly
- Celebrate member milestones and achievements
- Create opportunities for members to connect beyond content

### Handling Inappropriate Behavior

- **Warn**: Address issues privately with the member first
- **Restrict**: Use the restrict feature for repeated violations
- **Remove**: Remove members who persist in violating community standards
- **Document**: Keep records of violations for transparency

---

## 12. Troubleshooting

### Can't Create a Community

- **Check Required Fields**: Ensure you've entered a community name and selected a status
- **Character Limits**: Community name must be 40 characters or less
- **Try Again**: Network issues may cause creation to fail; check your connection and retry

### Join Request Not Approved

- **Contact Owner**: Reach out to the community owner directly if approval is delayed
- **Check Pending Status**: Verify that your request shows as "Pending" in the community details
- **Time Frame**: Give the owner time to review and approve your request
- **Try Another Community**: While waiting, explore other communities

### Can't See Community Content

- **Membership Required**: Verify you're a member of the community
- **Private Community**: Only members can view content in private communities
- **Permissions**: Check with the community owner if content is restricted
- **Refresh**: Pull down to refresh the feed and load latest content

### Can't Edit Community

- **Owner Only**: Only community owners can edit the community profile
- **Access Denied**: You must be the community owner to make changes
- **Contact Owner**: If you should have edit access, contact the community owner

### Member Management Not Visible

- **Owner Only**: The Members, Requests, and Restricted tabs are only visible to community owners
- **Tap Member Count**: As an owner, tap the member count on the community details page to access management

### Cover Media Upload Fails

- **File Size**: Ensure your image or video isn't too large
- **File Format**: Use standard formats (JPEG, PNG for images; MP4 for videos)
- **Aspect Ratio**: Check that your media matches the required aspect ratio (16:9 for landscape)
- **Network Connection**: Verify stable internet connection before uploading
- **Try Again**: If the upload fails, wait a moment and try uploading different media

### Services Not Saving

- **Required Fields**: Ensure both title and description are filled for each service
- **Character Limits**: Stay within field character limits
- **Validation**: Check that all services are properly formatted before clicking UPDATE
- **Network**: Verify you have a stable internet connection

---

*Last Updated: November 2024*
