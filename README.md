# Employee Service Marketing

## Relate '26 Demand Gen Command Center

A real-time dashboard for tracking the Relate '26 event registration progress and workstream status.

### 📊 Dashboard Overview

The Command Center provides at-a-glance visibility into:
- **Live Registration Tracking**: In-person and digital event registrations for IT and HR audiences
- **Workstream Board**: Trello-style kanban view of all demand gen workstreams
- **Executive Participation**: Confirmed executive attendance for key events
- **Key Deadlines**: Countdown timers for critical milestones
- **Communications Timeline**: Email campaign and digital activation schedule

### 🚀 Quick Start

1. Download `relate-demand-gen-dashboard.html`
2. Double-click to open in your browser
3. No installation or setup required - works offline

### 📈 Current Metrics (as of March 2026)

**In-Person Event**
- Target: 1,900 registrations
- Current: 178 (IT: 170, HR: 8)
- Progress: 9%

**Digital Event**
- Target: 5,600 registrations
- Current: 234 (IT: 218, HR: 16)
- Progress: 4%

### 🎨 Design

Built with Zendesk brand guidelines:
- Color palette: Zendesk Green (#03363D), Mint (#30AABC), Teal (#028079)
- Responsive design for desktop, tablet, and mobile
- Clean, scannable interface optimized for quick status checks

### 🔧 Technology Stack

- **React** (via CDN) - Component-based UI
- **Tailwind CSS** (via CDN) - Styling framework
- **Vanilla JavaScript** - Data management
- **Single HTML file** - No build process required

### ✏️ Updating the Dashboard

#### Update Registration Numbers

1. Open `relate-demand-gen-dashboard.html` in a text editor
2. Find the section: `const registrationData = {`
3. Update the `actual` values:
   ```javascript
   { metric: "IT Registrations", target: 1900, actual: 170, category: "IT" }
   ```
4. Save and refresh your browser

#### Update Workstreams

Find `const workstreams = [` and edit:
```javascript
{
    name: "Your Workstream Name",
    status: "In Progress",  // Options: "In Progress", "Vetting", "Not Started"
    owners: { it: "IT Owner", primary: "Primary Owner" },
    nextSteps: [
        { task: "Task description", done: false, isAction: true }
    ]
}
```

#### Update Deadlines

Find `const deadlines = [` and modify dates:
```javascript
{ name: "Event Name", date: "2026-04-20" }
```

### 🔒 Data Privacy

This dashboard contains confidential registration and business data. Do not:
- Publish to public websites
- Share outside authorized team members
- Post screenshots on social media

### 📱 Features

- ✅ Real-time progress bars with color-coded status
- ✅ Responsive grid layout
- ✅ Workstream kanban board with drag-free organization
- ✅ Countdown timers for deadlines
- ✅ Executive participation tracking
- ✅ Communications timeline
- ✅ Mobile-friendly design
- ✅ Printable for offline reference

### 🤝 Contributing

To request updates or report issues:
1. Contact the Employee Service Marketing team
2. Provide specific data changes needed
3. Updates can be made by editing the HTML file directly

### 📞 Support

For technical assistance or questions about the dashboard, contact your development team or Employee Service Marketing leadership.

---

**Last Updated**: March 20, 2026
**Version**: 1.0
**Maintained by**: Employee Service Marketing Team