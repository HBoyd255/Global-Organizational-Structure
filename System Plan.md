# Global Organizational Structure System Plan

This is the plan for how I want to organize my various file structures going
forward.

### Motivation

One of the ones reasons that I am splitting up these roles into catagories is so
that I can cut down on the amount of email addresses I have. I want to just
have one email address, who's contents is split up into catagories via labels.

So for example hboydemail@gmail.com is currently for personal items,
hboyd255@gmail.com is currently for professional items. hboydtff@gmail.com and
harryb@tffsolutions.co.uk are used for business purposes,
hb1518@york.ac.uk is used for uni items, and harryapplegreen@gmail.com no
longer has a real purpose, but just still exists for legacy reasons.

### Rules

1. All financial information should be categorized in the personal/finance
   category. This includes tax information, payslips, university funding, Budget
   plans, Ext. The exception to this rule is all business related finances
   should be placed in Business/\*/finance. to attempt to keep my personal
   finance separate from my business finances.

2. Catagories should be written with capital letters and spaces separating
   words.

3. If colour is available, top level categories should be black, or similar,
   second level catagories should have colour that is intuitive and conciseness,
   E.G. Finance should be green, and medical should be red. Colours should be
   recursively applied to children, if easily possible.

4. Some colours may stick out, if it is of immediate benefit, for example, all of
   \*/Accounts should be the same colour, but the category "Account Deletion"
   could be set to red, to indicate its difference in purpose.

5. going forward code should be separated by project, not by language.

6. If a category has sub catagories, it should not hold items, items should
   Just exist at the end of category paths, like leaves on trees.

7. This may change, but for now the colour orange is reserved for items that
   I want to come back to, for for specific filters, basically anything orange
   should be there to grab my attention.

8. For now, projects that could be placed under other top level catagories,
   will remain under the projects category. For example, hboyd.co.uk is for
   professional use, but will remain under the projects top level category.

9. When organizing items, they should be categorized based on their overall
   category rather than what needs to be done with them. For example, a driving
   test booking should be grouped with other driving test-related items, not
   with other booking-related items.

### Top level categories

- **Archives**  
  A repository for older items that aren't actively needed but may be referenced
  or required in the future.
- **Backups**  
  Copies of essential data and files to ensure their safety and availability.
- **Business**  
  items related do business endeavors, currently TFF Solutions related items.  
  This category is unique in that it has a higher level of separation from other
  catagories, for example, it has its own subcategories for finance and digital.
- **Digital**  
  Items related to technology, for example information about the various
  computers I own.
- **Education**  
  Materials and information related to academic pursuits, Uni or otherwise.
- **Inbox**  
  A temporary holding space for new or unsorted items.
- **Meta**  
  Items related to either the overall Global Organizational Structure, or items
  related to the various environments, E.G. Todoist Rules in Meta/todoist, Gmail
  rules in my Gmail.
- **Personal**  
  Items related to myself and my personal life. This category is also the closes
  thing to a default category.
- **Professional**  
  Not to be confused with the Business category, This is for items related to me
  as an employee. CVs, jobs im applying for EXT. not really for professional
  qualification, as they will be held in Education.
- **Projects**  
  Items related to the various projects I am working on, that could be either
  code, hardware, or pretty much anything that I could imagine putting on my
  github.

### Independence

Aside from Business items, which are all to be nested under the business top
level category. A lot of second level categories will be Top Level Independent.
For example, all finance items are to be placed under person/finance
and all code should be placed in projects/\*/src or something similar.
Some second level categories however will remain Top level dependant, meaning
this second level category could be replicated against multiple top levels.
An example of this would be Accounts, the category holding information regauging
various platforms I have accounts with. Information about my github account
would be held in Projects/Account/Github, whereas information about my netflix
account would be held in Personal/Account/Netflix.
Top level independent and dependant are shortened to TLI and TLD.

### Some important second level categories

Personal/

- <span style="color:red">Medical</span>
- <span style="color:green">Finance</span> TLI
- <span style="color:white">Newsletters</span> TLD
- <span style="color:lightblue">Accounts</span> TLD
- <span style="color:hotpink">Family and Friends</span>
- <span style="color:">Communication</span> TLD
- <span style="color:lightPink">Volunteering and Charity</span>

Professional/

- <span style="color:">Applications</span>
- <span style="color:">Current Jobs</span>
- <span style="color:">Past Jobs</span>
- <span style="color:">CV</span>

Professional/

- <span style="color:">Applications</span>
- <span style="color:">Current Jobs</span>
- <span style="color:">Past Jobs</span>
- <span style="color:">CV</span>

### Ordering

Although most directories and environments automatically sort directories and
items alphabetically, this should be overridden to apply a better order.
This can be done by prefixing the desired number onto a name separated by an
underscore, as seen below. The decided upon order for my top level categories
can be seen below.

00_Inbox(When required)
01_Personal  
02_Professional  
03_Education  
04_Projects  
05_Digital  
06_Meta  
07_Backups  
08_Archives  
09_Business

Inbox should be placed at the top, when applicable, as it contains items that
need dealing with.
Personal should be at the top as it is the broadest, and most frequently used
category.
Business should be at the bottom to signify its separation. This does not,
however, indicate that it is any less important. There is no order of
importance built into this structure, as this can heavily depend on the context
of each items, some items in Education will be more important than some items in
Professional and vise versa. If a most important category had to be assigned,
it would be the personal category, as this holds medical and family items.

Second and deeper categories can stay in alphabetically order.

#### GMAIL Scripts Features

- Check that all items exist at the end of a category tree.
- check every item has exactly one label, not 0, not 2+.
- give every item that breaks the rules the Meta/NEEDS_ATTENTION label.
