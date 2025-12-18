📱 CellPhone Shop Management System (VB.NET)


A Windows Forms application built with VB.NET for managing cellphone shop operations, including customer details, receipt creation, purchase history, and system customization with security controls.

🚀 Key Features
🧾 New Receipt Management

Capture customer information (phone, name, email)

Add multiple receipt items with:

Category selection

Item description

Quantity and price

Optional percentage discount

Automatically calculate and display total amount

Remove selected items from receipt

Save and print receipts

Notes and date tracking for each receipt

📊 Receipt & Item Handling

Read-only DataGridView for receipt items

Full-row selection for safe deletion

Prevents manual row edits to maintain data integrity

🔍 Customer History

Search customers by phone number

View complete purchase history

Double click any history record to view full receipt details

Clear visual separation between search and history results

🎨 Customization & Settings

Company information management:

Company name

Phone number

Email address

Physical address

Warranty text

Company logo upload with preview

Recommended size: 200×200 px

Receipt preview panel

Test print functionality

Reset system settings to default

🔒 Security & Access Control

Password-protected customization section

Lock / unlock system using a secure password

Sensitive fields hidden until unlocked

Prevents unauthorized changes to business settings

🗂 Application Structure
🔹 Main Tabs

New Receipt

Customer History

Customize

🔹 Core UI Components

TabControl for navigation

GroupBox sections for logical separation

DataGridView for receipts and history

NumericUpDown for quantity, price, and discount

DateTimePicker for receipt dates

PictureBox for logo display

Panel for receipt preview

BackgroundWorker for background processing

🧩 Technologies Used

VB.NET

Windows Forms

ADO.NET (SQL integration ready)

DataGridView

GDI+ Printing Support

Password-based UI locking

🖥 System Requirements

Windows OS

.NET Framework (compatible with WinForms)

Visual Studio (recommended for development)

📌 Notes

UI is locked to a fixed window size for layout consistency

Designed with business usability and data safety in mind

Suitable for small cellphone repair shops or retail stores

👤 Author

Mr Soul
