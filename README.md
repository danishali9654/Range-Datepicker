
📅 **Custom Range Datepicker for LWC**

This project provides a fully customizable Date Range Picker component built using Lightning Web Components (LWC), designed to replicate the native SLDS (Salesforce Lightning Design System) styling and provide functionality for selecting start and end dates within a user-friendly calendar interface.


✨**Features**

📆 Custom calendar UI inspired by SLDS datepicker

📅 Start & End date selection with range highlighting

🚫 Disabled past dates (configurable logic)

🔁 Month navigation with year dropdown

🎯 Single-date and range support

⚙️ Two-way communication using custom events (rangeapply, rangeclear)

🔍 Clean parent-child component architecture

📦 Easily embeddable inside lightning-card, lightning-input, or custom UI

🧩 <stronng>Component Structure</strong>

**customRangeDatepicker**: Main datepicker component with calendar UI

**parent**: Wrapper/consumer component using lightning-input and displaying the date range



📤 **Events**
rangeapply: Fires when user clicks Apply, returns startDate and endDate

rangeclear: Fires when user clicks Clear, resets the selection

closepicker: Optional event for manual closure from parent

🧠 **How it Works**
The calendar UI is rendered with dynamic month/year and weekday headers.

Users can click to select a start date, and then an end date. Selected range is highlighted.

Navigation allows moving across months and years.

Selected range is formatted (DD-MM-YYYY) and shown in the parent input.

🚀 <stronng>Installation</strong>
Clone or download this repository

Deploy the component to your Salesforce org via VS Code + SFDX

Add <c-custom-range-datepicker> inside any parent LWC

🔧 <stronng>TODO / Future Enhancements</strong>
Add keyboard navigation support

Option to disable weekends

Time range picker

Localization (month and day names)
