# Cloud-Storage-Administration-Guide
Creating users, assigning permissions, managing folders and recovering files

Prepared by Armstrong Francis Ogbonnaya   |   armstrongogbonnaya.official@gmail.com   |   Version 1.0   |   October 2026

1. Purpose and Scope

This guide is for administrators who look after an organisation’s cloud storage. It covers the four jobs 
that take up most of the working week: setting up user accounts, giving people the right level of 
access, keeping folders in order, and getting files back when something goes wrong.
The steps are written to work on any of the common platforms (Google Drive, OneDrive, Dropbox 
Business and similar). Menu names differ from one provider to another, so where a label may vary, the 
usual alternatives are shown in brackets. Corrections or questions about this document can be sent to 
the author, Armstrong Francis Ogbonnaya, at armstrongogbonnaya.official@gmail.com.

2. Before You Begin

• An administrator account with enough rights to manage users and sharing. Use a dedicated 
admin login, not your everyday one.

• Multi-factor authentication (MFA) switched on for every admin account.

• A written naming rule for users, groups and folders. Agree it before the first account is made, 
because renaming later is slow and error-prone.

• A signed-off request from HR or the line manager for each new account, stating the person’s 
department, manager and start date.

3. Creating Users
Only create an account from an approved request. A verbal “please add Tunde to the system” is not 
enough, since you will need the paper trail during audits.

1. Sign in to the admin console and open Users (or Directory > Users).

2. Select Add user. Enter the first name, last name and company email address, following your 
naming rule, for example firstname.lastname@company.com.

3. Choose the department or organisational unit. This decides which policies the account picks up 
automatically.

4. Set a temporary password and tick Require password change at next sign-in. If your platform 
allows it, send an invitation link instead.

5. Add the user to the correct group or groups before you save. Access should come from group 
membership, not from one-off grants (see Section 4).

6. Set a storage quota if your plan uses per-user limits, then save.

7. Confirm that the account shows as Active in the user list. Send the sign-in details to the user 
directly or to their manager, never to a shared chat group.

Leavers. When someone leaves, suspend the account first rather than deleting it. Transfer their files 
to their manager, and delete the account only after your retention period has passed (30 to 90 days 
is common).

4. Assigning Permissions
The guiding rule is least privilege: give people the minimum access they need to do their job, and give 
it to groups rather than to individuals. When a person changes teams, you move them between groups 
and nothing else needs touching.


Role

What the person can do.

Typical use
Viewer

Editor

Manager

Administrator

Open and download files. Cannot change, upload or  delete anything.
View, upload, edit and delete files inside the folder.
Everything an Editor can do, plus add or remove 
people and change sharing on the folder.
Full control of the account, including users, policies 
and recovery.

Auditors, contractors, reference 
material

Regular team members
Team leads, folder owners

IT staff only; keep to two or three 
people

To grant access to a folder

1. Create a group for each team and access level, for example Finance-Editors and Finance-Viewers.

2. Right-click the folder and choose Share (or Manage access).

3. Type the group name, select the role, and confirm. Untick any option that notifies a large group 
unless it is needed.

4. Use Preview as user (or Effective access) to check the result from the user’s side.
Watch out for links. Avoid “Anyone with the link” sharing unless it has been approved. Where 
external sharing is necessary, set an expiry date and restrict it to named email addresses.

5. Managing Folders
A tidy structure saves more support calls than any other single habit. Organise by department first, 
then by project or year, and try not to go deeper than four levels. A consistent name pattern such as 
Department_Project_Year (for example, Finance_Payroll_2026) makes searching and reporting far 
easier.

• Creating. Open the parent folder, select New > Folder and name it using the pattern above. The 
new folder inherits the parent’s permissions.

• Moving and renaming. Check access afterwards. Moving a folder into a different parent can 
quietly change who is able to see it, because inherited permissions change with it.

• Breaking inheritance. Do this only when a sub-folder really needs tighter access, such as HR 
records inside a general folder. Write down the reason in your change log.

• Monitoring. Run the storage usage report monthly. Archive folders that have not been opened in 
twelve months, and ask owners before removing anything.

• Retention and holds. Apply a retention rule or legal hold to finance, HR and contract folders so 
files cannot be permanently deleted before the required period ends.

6. Recovering Files

A deleted file is rarely gone at once. There are three layers to try, starting with the simplest. Always ask 
the user for the file name, the folder it lived in and roughly when it disappeared.
A. The file was deleted and is still in the bin

1. Open Trash (or Recycle bin) and search for the file name.

2. Select the file and choose Restore. It returns to its original folder.

B. The file was overwritten or edited by mistake

1. Right-click the file and open Version history.

2. Pick the last good version, check its date and time, and select Restore this version.


C. The bin was emptied, or the user’s account was deleted

Go to Admin console > Users, select the user and look for Restore data (or Deleted items). Most 
platforms keep this for a limited window, often 25 to 30 days. Past that point the only route is a 
backup restore, which should be requested through your backup provider or IT lead.

After any recovery. Ask the user to open the file and confirm it is correct, check that its permissions 
match the folder, and log the incident with the date, file, requester and cause. Test a restore every 
quarter so you know the process works before you need it.

7. Routine Checklist Frequency

Task

Weekly

•Review new accounts, suspended accounts and any sharing alerts.

Monthly

•Run the storage usage report. Delete suspended accounts that are past the retention 
period.

Quarterly

•Review group membership and folder permissions. Perform a test file restore.

Annually

•Review retention policies, quotas and the overall folder structure.

Note: Retention periods and menu names depend on the provider and plan. Confirm the exact figures in your provider’s 
documentation before applying them. 

Document owner: Armstrong Francis Ogbonnaya, 
armstrongogbonnaya.official@gmail.com.
