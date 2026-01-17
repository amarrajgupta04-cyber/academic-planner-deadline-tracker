# 🎓 Academic Planner - Open Source Workshop Issues

This document contains 20 issues designed for an open-source workshop. Issues are categorized by difficulty level to accommodate contributors of all skill levels.

**Distribution:** 
- 🟢 **10 Beginner Issues** (50%) - Perfect for newcomers
- 🟡 **6 Intermediate Issues** (30%) - Build on fundamentals  
- 🔴 **4 Advanced Issues** (20%) - Complex features

---

## 🟢 BEGINNER ISSUES (10 Issues - Good First Issues)

### Issue #1: Add Favicon to the Application
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `documentation`, `html`  
**Estimated Time:** 15-30 minutes

**Description:**  
The application currently doesn't have a favicon (the small icon that appears in the browser tab). Add an appropriate favicon to improve the professional appearance of the app.

**Tasks:**
- Create or find an appropriate academic-themed favicon (e.g., graduation cap, book, calendar icon)
- Add the favicon link to the `<head>` section of `index.html`
- Test in multiple browsers

**Learning Outcomes:**
- Understanding HTML `<head>` section
- Working with favicons and icon formats

**Acceptance Criteria:**
- Favicon appears in browser tabs
- Icon is clear and recognizable at small sizes
- Appropriate academic theme

---

### Issue #2: Improve README.md with Installation Screenshots
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `documentation`  
**Estimated Time:** 30 minutes

**Description:**  
Enhance the README.md file by adding screenshots of the application to help new users understand what they're building.

**Tasks:**
- Take screenshots of the main dashboard
- Add screenshots to a new `/docs/images/` folder
- Update README.md to include these screenshots
- Add alt text for accessibility

**Learning Outcomes:**
- Documentation best practices
- Markdown syntax
- Accessibility considerations

**Acceptance Criteria:**
- At least 3 screenshots showing different views
- Images are optimized for web (not too large)
- Proper alt text for all images

---

### Issue #3: Add Footer Links (GitHub, License, etc.)
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `html`, `css`  
**Estimated Time:** 30 minutes

**Description:**  
The footer currently only shows copyright text. Add useful links like GitHub repository, license information, and contribution guidelines.

**Tasks:**
- Update the footer in `index.html` with links
- Style the links in `css/style.css`
- Ensure links open in new tabs appropriately
- Make footer links responsive

**Learning Outcomes:**
- HTML link attributes
- CSS styling for navigation elements
- Responsive design considerations

**Acceptance Criteria:**
- Footer contains at least 3-4 useful links
- Links are styled and easy to click
- Footer remains responsive on mobile

---

### Issue #4: Add Color-Coded Priority Badges
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `css`, `ui/ux`  
**Estimated Time:** 45 minutes

**Description:**  
Enhance the visual distinction between priority levels by adding styled badges with colors and icons.

**Tasks:**
- Update the priority badge styling in `css/style.css`
- Add appropriate colors (red for high, yellow for medium, green for low)
- Consider adding icons (🔴 🟡 🟢) or emoji
- Ensure good contrast for readability

**Learning Outcomes:**
- CSS styling techniques
- Color theory and accessibility
- Visual hierarchy

**Acceptance Criteria:**
- Priority badges are clearly visible
- Colors meet accessibility standards
- Consistent styling across the application

---

### Issue #5: Create a "Quick Add" Keyboard Shortcut Guide
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `documentation`, `html`  
**Estimated Time:** 45 minutes

**Description:**  
Add a help section or tooltip that shows users the available keyboard shortcuts (like Ctrl+K for search).

**Tasks:**
- Create a keyboard shortcuts modal or info section
- Document all available shortcuts
- Add a "?" button in the header to show shortcuts
- Style the shortcuts guide

**Learning Outcomes:**
- Modal/dialog creation
- Documentation writing
- User experience design

**Acceptance Criteria:**
- Shortcuts guide is accessible from the main interface
- All shortcuts are documented
- Clean, easy-to-read format

---

### Issue #6: Add Empty State Messages and Graphics
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `ui/ux`  
**Estimated Time:** 30-45 minutes

**Description:**  
When users have no deadlines, show a friendly message encouraging them to add one.

**Tasks:**
- Design empty state message
- Add illustration or icon
- Include call-to-action button
- Style in `css/style.css`

**Learning Outcomes:**
- User experience design
- Empty state best practices
- CSS styling

**Acceptance Criteria:**
- Shows when no deadlines exist
- Friendly, encouraging message
- Clear CTA to add first deadline

---

### Issue #7: Add Loading Animations for Better UX
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `css`  
**Estimated Time:** 30-45 minutes

**Description:**  
Add subtle loading animations when data is being processed.

**Tasks:**
- Create CSS loading spinner
- Add skeleton loaders for deadline cards
- Add fade-in animations for content
- Keep animations subtle and smooth

**Learning Outcomes:**
- CSS animations
- User experience enhancement
- Performance considerations

**Acceptance Criteria:**
- Smooth loading transitions
- No jarring content shifts
- Works in both themes

---

### Issue #8: Improve Form Validation Messages
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `javascript`  
**Estimated Time:** 45-60 minutes

**Description:**  
Add clearer validation messages when users submit the deadline form.

**Tasks:**
- Add validation for empty fields
- Check if deadline date is in the past
- Show helpful error messages
- Style error messages

**Learning Outcomes:**
- Form validation
- User feedback design
- JavaScript validation

**Acceptance Criteria:**
- All required fields validated
- Warning if deadline is in past
- Clear, helpful error messages
- Errors clear when user fixes them

---

### Issue #9: Add Quick Stats Dashboard
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `javascript`  
**Estimated Time:** 45-60 minutes

**Description:**  
Show quick statistics at the top of the dashboard (total deadlines, completed, upcoming).

**Tasks:**
- Calculate total deadlines
- Count completed vs pending
- Count deadlines this week
- Display in header area
- Style stat cards

**Learning Outcomes:**
- Data aggregation
- Dynamic content updates
- Dashboard design

**Acceptance Criteria:**
- Shows: Total, Completed, Upcoming This Week
- Updates in real-time when deadlines change
- Responsive design

---

### Issue #10: Add Confirmation Before Deleting Deadlines
**Difficulty:** Beginner  
**Labels:** `good first issue`, `beginner`, `javascript`  
**Estimated Time:** 30-45 minutes

**Description:**  
Prevent accidental deletions by asking for confirmation.

**Tasks:**
- Add confirm dialog before delete
- Show deadline title in confirmation
- Style confirmation modal
- Add "Cancel" and "Delete" buttons

**Learning Outcomes:**
- Modal dialogs
- User confirmation patterns
- Preventing data loss

**Acceptance Criteria:**
- Confirmation required before deleting
- Shows which deadline will be deleted
- Can cancel the deletion
- Delete only happens after confirmation

---

## 🟡 INTERMEDIATE ISSUES (6 Issues)

### Issue #6: Implement Drag-and-Drop for Deadline Prioritization
**Difficulty:** Intermediate  
**Labels:** `intermediate`, `javascript`, `feature`  
**Estimated Time:** 2-3 hours

**Description:**  
Allow users to reorder their deadlines by dragging and dropping deadline cards to change their order or priority.

**Tasks:**
- Implement HTML5 Drag and Drop API
- Update deadline order in local storage
- Add visual feedback during drag
- Handle touch events for mobile

**Learning Outcomes:**
- HTML5 Drag and Drop API
- Event handling
- State management
- Mobile touch events

**Acceptance Criteria:**
- Users can drag deadline cards
- Order persists after page reload
- Works on both desktop and mobile
- Visual feedback during drag operation

---

### Issue #7: Add Task Categories/Tags System
**Difficulty:** Intermediate  
**Labels:** `intermediate`, `javascript`, `feature`  
**Estimated Time:** 2-3 hours

**Description:**  
Implement a tagging system so users can categorize tasks beyond just courses (e.g., "research", "writing", "presentation", "exam").

**Tasks:**
- Add tags field to task form
- Create tag input with autocomplete
- Update storage to handle tags
- Add tag filtering to the filter system
- Display tags on deadline cards

**Learning Outcomes:**
- Dynamic form inputs
- Array manipulation
- Autocomplete implementation
- Advanced filtering

**Acceptance Criteria:**
- Users can add multiple tags to tasks
- Tags are displayed on task cards
- Can filter tasks by tags
- Tag suggestions based on previous tags

---

### Issue #8: Implement Dark/Light Theme Animation
**Difficulty:** Intermediate  
**Labels:** `intermediate`, `css`, `javascript`  
**Estimated Time:** 1-2 hours

**Description:**  
Add smooth transitions when switching between dark and light themes instead of instant switching.

**Tasks:**
- Add CSS transitions for theme changes
- Implement smooth color transitions
- Add loading state during transition
- Ensure no flickering occurs

**Learning Outcomes:**
- CSS transitions and animations
- Theme management
- Performance optimization
- User experience enhancement

**Acceptance Criteria:**
- Smooth transition between themes (300-500ms)
- No layout shifts or flickering
- All colors transition smoothly
- Maintains accessibility

---

### Issue #9: Add Deadline Reminder Notifications
**Difficulty:** Intermediate  
**Labels:** `intermediate`, `javascript`, `feature`, `notification`  
**Estimated Time:** 3-4 hours

**Description:**  
Implement browser notifications to remind users about upcoming deadlines. Users should be notified at configurable intervals (1 day before, 1 hour before, etc.).

**Tasks:**
- Request notification permissions
- Check for upcoming deadlines
- Trigger browser notifications
- Add settings for notification preferences
- Handle notification clicks to open specific tasks

**Learning Outcomes:**
- Browser Notification API
- Permission handling
- Interval management
- Settings persistence

**Acceptance Criteria:**
- Users can grant/deny notification permission
- Notifications trigger at appropriate times
- Users can configure notification timing
- Clicking notification focuses relevant task

---

### Issue #10: Create Export to Calendar (ICS) Feature
**Difficulty:** Intermediate  
**Labels:** `intermediate`, `javascript`, `feature`  
**Estimated Time:** 2-3 hours

**Description:**  
Allow users to export their deadlines as an ICS (iCalendar) file that can be imported into Google Calendar, Outlook, or Apple Calendar.

**Tasks:**
- Research ICS file format
- Generate ICS file from deadline data
- Create download functionality
- Add "Export to Calendar" button
- Test with multiple calendar applications

**Learning Outcomes:**
- File format specifications
- Data transformation
- File generation and download
- Cross-platform compatibility

**Acceptance Criteria:**
- ICS file is correctly formatted
- All deadlines are included with proper dates
- File imports successfully into major calendar apps
- Export includes task descriptions and priorities

---

### Issue #11: Enhance Search with Text Highlighting
**Difficulty:** Intermediate  
**Labels:** `intermediate`, `javascript`, `feature`  
**Estimated Time:** 2-3 hours

**Description:**  
Highlight matching text in search results for better visibility.

**Tasks:**
- Implement text highlighting algorithm
- Highlight in title and description
- Style highlighted text
- Search across multiple fields
- Show search result count

**Learning Outcomes:**
- Text search algorithms
- DOM manipulation
- Regular expressions
- User experience design

**Acceptance Criteria:**
- Matching text is highlighted
- Searches title, description, course
- Case-insensitive search
- Clear visual highlighting
- Shows result count

---

## 🔴 ADVANCED ISSUES (4 Issues)

### Issue #11: Implement Calendar View with Interactive Grid
**Difficulty:** Advanced  
**Labels:** `advanced`, `javascript`, `feature`  
**Estimated Time:** 5-8 hours

**Description:**  
Create a fully functional calendar view that displays deadlines on a monthly calendar grid. Users should be able to click dates to add deadlines and see all deadlines for each day.

**Tasks:**
- Build calendar grid with JavaScript
- Calculate and display correct days for any month
- Show deadlines on their respective dates
- Handle navigation between months
- Add quick-add functionality by clicking dates
- Show deadline count per day
- Make calendar responsive

**Learning Outcomes:**
- Date manipulation in JavaScript
- Complex DOM rendering
- Calendar algorithms
- Event delegation
- Responsive grid layouts

**Acceptance Criteria:**
- Calendar correctly displays all months and years
- Deadlines appear on correct dates
- Clicking a date allows quick-add
- Calendar is responsive on mobile
- Performance is smooth even with many deadlines

---

### Issue #12: Add Data Visualization for Statistics
**Difficulty:** Advanced  
**Labels:** `advanced`, `javascript`, `visualization`  
**Estimated Time:** 6-8 hours

**Description:**  
Implement the Statistics view with charts and graphs showing completion rates, tasks by course, upcoming deadlines timeline, and productivity trends.

**Tasks:**
- Choose a chart library (Chart.js, D3.js, or implement custom)
- Create completion rate pie/donut chart
- Add bar chart for tasks by course
- Create timeline view for upcoming deadlines
- Add trend analysis (tasks completed per week/month)
- Make charts responsive and accessible

**Learning Outcomes:**
- Data visualization principles
- Chart library integration
- Data aggregation and analysis
- Canvas or SVG rendering
- Responsive chart design

**Acceptance Criteria:**
- Multiple chart types implemented
- Charts update based on actual data
- Charts are responsive and mobile-friendly
- Color scheme matches application theme
- Charts are accessible (keyboard navigation, screen readers)

---

### Issue #13: Add Progressive Web App (PWA) Support
**Difficulty:** Advanced  
**Labels:** `advanced`, `javascript`, `pwa`  
**Estimated Time:** 5-7 hours

**Description:**  
Convert the application into a Progressive Web App so users can install it on their devices and use it offline.

**Tasks:**
- Create manifest.json file
- Implement service worker for offline support
- Add install prompt
- Cache static assets
- Handle offline data sync
- Add appropriate icons for different platforms
- Test on multiple devices

**Learning Outcomes:**
- Progressive Web App concepts
- Service Worker API
- Cache strategies
- Offline-first design
- Web app manifest

**Acceptance Criteria:**
- App can be installed on devices
- Works offline with cached data
- Install prompt appears appropriately
- All static assets are cached
- Passes PWA audit in Lighthouse

---

### Issue #14: Implement Recurring Deadlines Feature
**Difficulty:** Advanced  
**Labels:** `advanced`, `javascript`, `feature`  
**Estimated Time:** 6-10 hours

**Description:**  
Implement recurring deadlines for weekly assignments, monthly projects, etc. Users should be able to set recurrence patterns (daily, weekly, monthly) with options for end dates or occurrence counts.

**Tasks:**
- Design recurrence pattern UI
- Implement recurrence logic (daily, weekly, monthly, custom)
- Generate future deadline instances
- Handle editing and deletion of recurring series
- Add option to edit single instance vs all instances
- Store recurrence rules efficiently

**Learning Outcomes:**
- Complex date calculations
- Recurrence rule algorithms (similar to iCalendar RRULE)
- Data modeling for recurring events
- Complex UI state management
- Efficient data storage

**Acceptance Criteria:**
- Users can create recurring deadlines
- Multiple recurrence patterns supported
- Can edit/delete single instance or entire series
- Recurring deadlines appear correctly on calendar
- Performance remains good with many recurrences

---

## 🏷️ Issue Labels Guide

- **good first issue**: Perfect for newcomers to open source
- **beginner**: Requires basic HTML/CSS/JS knowledge
- **intermediate**: Requires solid understanding of web development
- **advanced**: Requires advanced skills and problem-solving
- **bug**: Something isn't working
- **documentation**: Improvements to documentation
- **feature**: New feature or request
- **enhancement**: Improvement to existing feature
- **help wanted**: Extra attention needed
- **question**: Further information requested
- **ui/ux**: User interface and experience
- **performance**: Performance improvements
- **accessibility**: Accessibility improvements

---

## 📊 Difficulty Distribution

- **🟢 Beginner (10 issues - 50%)**: Perfect for learning basics and getting started
- **🟡 Intermediate (6 issues - 30%)**: Build on fundamentals with more complex features
- **🔴 Advanced (4 issues - 20%)**: Complex features for experienced developers

This balanced distribution ensures that newcomers have plenty of accessible entry points while still providing challenging work for experienced contributors.

## 🎯 Workshop Tips

1. **Start Small**: Begin with beginner issues to understand the codebase
2. **Read Carefully**: Each issue has detailed requirements
3. **Ask Questions**: Use issue comments if anything is unclear
4. **Test Thoroughly**: Test your changes in different scenarios
5. **Document**: Update relevant docs with your changes
6. **Have Fun**: Learning is the goal, perfect code is secondary!

---

**Happy Coding! 🚀**
