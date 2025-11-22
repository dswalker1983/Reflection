Reflection – README
Reflection is a lightweight, 100% offline, single-file HTML classroom participation & reflection tracker designed for teachers who want fast, simple daily scoring without any accounts, servers, or installations.
Just open the HTML file in any modern browser (Chrome, Firefox, Safari, Edge) and start using it immediately.


Features
Completely offline – all data stored in your browser using IndexedDB (via localforage)
Manage multiple classes
Add/remove students per class
Daily attendance & participation scoring (Present/Tardy/Absent/Excused + 5 participation levels)
Automatic score calculation (max 10, base 8)
Per-student daily notes with visual indicator
Weekly participation report (Mon–Sun, with Monday–Friday totals and bonus highlighting)
Full data export to CSV (backup)
Full data import from CSV (merge/restore)
Delete all data option
Responsive design – works great on tablets and phones
No dependencies except one small CDN script (localforage ~20 KB)

How to Use
Save the entire HTML code as reflection.html
Open the file in your browser (double-click or drag into browser)
Click Classes → Add your first class
Select the class → Click Students → Add students
Pick a date (defaults to today) → Start marking attendance & participation
Click the + / ? button next to a student to add a private note
Use Weekly Report to generate a printable week overview (Mon–Fri total out of 40 + bonus points)
Use Data → Export to backup everything; Import to restore or move to another device
Tip: Bookmark the page or add it to your home screen for instant access.


Scoring System
Attendance
Base Score
Present
8
Tardy
–1 → 7
Absent
0
Excused
8 (neutral)


Participation
Modifier
Exceptional
+2
Engaged
+1
Average
0
Disruptive
–1
Sleeping
–3

Maximum possible daily score: 10

Weekly Report Notes
Always shows a full week starting on Monday
Only Monday–Friday scores count toward the 40-point total
Students scoring >40 get a bonus shown (e.g., 42 → “42/40 (+2)”)
Perfect for printing or screenshotting to share with students/parents

Data Backup & Transfer
Export Full Backup (CSV) → Downloads everything in a standard CSV file
Import Backup from CSV → Merges with existing data (great for moving to a new computer or restoring)
CSV format is simple and can be opened in Excel, Google Sheets, Numbers, etc.




Privacy & Security
Nothing ever leaves your device
No tracking, no analytics, no internet required after the first load
You own 100% of your data

Known Limitations
Data is stored per browser/device (use Export/Import to move between devices)
Very large classes (100+ students) may slow down slightly
No cloud sync (by design – keeps it private and simple)

