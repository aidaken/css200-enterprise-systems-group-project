
This week we figured that the plugin has these main modules:
* Dashboard interface: Organizes emails into categories such as Academics, Finance, Registration, Careers/Internships, Campus Events, and News, along with a dedicated High Priority view.
* Metadata reader: Uses sender’s domain, subject line, timestamps, and existing Outlook flags/tags to categorize emails.
* Rule engine: Uses metadata to categorize emails and group similar notifications.
* Priority: Uses straightforward rules, especially focusing on deadlines within two days and keywords like “action required”, “hold”, or “past due”.
* Correction feature: Allows students to adjust an email’s category or priority when the system makes an error.
* Settings: Allows students to add or rename categories and tweak keyword or sender rules.
* Sync/refresh: Keeps the plugin updated with new messages.
* Privacy layer: Ensures the plugin doesn’t read or store email body content, using only minimum access necessary.


We will build a working prototype of the core experience rather than a full deployed Outlook add-in.

The prototype will include default categories, a High Priority view that shows urgent items across all categories, rule-based categorization, and priority assignment using metadata only.

The prototype will also include the ability for a student to correct an email’s category or priority when it is misclassified.

A simple settings area will be included where students can adjust a small set of rules, such as adding a keyword or changing a sender-based rule.

The prototype will not include deep integrations with systems like D2L or any student info systems, and will not read or store email body content.

Advanced machine learning will not be implemented in this phase.

The prototype may demonstrate “learning” in a simple way by saving user corrections as updated rules.

The focus will be on app store deployment or university-wide compliance implementation beyond demonstrating privacy-first design choices.

The hero prototype for week 8 will be illustrative design of what we are trying to show to people.
