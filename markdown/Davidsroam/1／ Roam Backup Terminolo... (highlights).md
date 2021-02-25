- Author:: [[@roamhacker on Twitter]]
- URL:: https://twitter.com/roamhacker/status/1355408834941038595
- Recommended By::
- Tags:: #Tweets #Inbox #Readwise
- ### Highlights first synced by #Readwise [[February 25th, 2021]]
    - 1/ Roam backup terminologies & strategies. Recently in the Slack channels a discussion was started about backup. When you do an Export you have 3 options. Markdown, JSON and EDN. These terms can be confusing.

I want to provide an opinionated view & some basic guidance. #roamcult
    - 2/ my basic strategy is to export in EDN & Markdown. These two formats give me (1) ability to fully restore my graph & (2) to restore the text of individual pages.

JSON is JavaScript Object Notation and mostly is intended for programmers & isn't as useful for a backup strategy.
    - 3/ EDN (from the developer documentation) is Extensible Data Notation. A superset of edn is used by Clojure to represent programs, and it is used by Datomic and other applications as a data transfer format.

Nerdy! Yawn!
    - 4/ For none nerds: the EDN format most accurately reflects the way the internal database of Roam stores data. So when exporting EDN, it is a full fidelity backup, as a format it is expressive enough to really capture all the attributes that make up a graph. JSON doesnt do this.
    - 5/ There is one essential thing to know about using EDN: In Roam when you use a EDN backup to do a restore, it restores (replaces) the entire database currently stored in Roam. It restores everything. It overwrites the graph. 

This means its not good for restoring just a page.
    - 6/ A markdown backup exports each page as an individual file using the Markdown format. So Markdown is very useful for restoring the content of a single page. Markdown does not retrain all aspects of a page, but maintains important elements that covers the 80/20 of recovery needs
    - 7/ Markdown exports the text, the outline structure and some basic formatting elements (bold, italics and highlight). Again, this is very useful for retrieving the text of a page or text of blocks. One minus of Markdown is that it exports block refs as refs ((AwxsIaD21)).
    - 8/ If you want full fidelity Markdown export (including block refs), #roam42 converter tool does this for you. It is not a backup tool, but allows you to extract full text for export into other programs.
    - 9/ So Roam allows you to export your data, but it doesn't include any tools for an automated backup strategy. This is a complaint point for many many users. We should discuss what would be a good automated solution??????
    - 10/ In the meantime, we can and SHOULD set up a good backup strategy. And frankly speaking, if Roam eventually automates the backup, it is still a best practice to have your own manual backup strategy in the unlikely event Roams backup fails -- this is life it happens.
    - 11/ BACKUP Strategy includes answering a few questions:
(1) What do we need to backup?
(2) When do we need to backup?
(3) How do we remember to do our backup?
(4) How long should you keep your backups?
    - 12/ (1) What do we need to backup:
+ Do a EDN backup to get a full fidelity backup of your graph. In worse case scenario, we use this to replace and restore a graph to the date of the backup.This is for disaster recovery!
+ Do a Markdown backup so you can restore individual pages
    - 13/ (2) When do we need to backup?
You need to establish how frequently you think your database needs to be backed up. Once a month is probably not wise, Once a week is very reasonable.
I do it every 3 to 4 days, and then sometimes when I did a lot of important work in a day.
    - 14/ How do we remember to do our backup?
Set up a recurring reminder in a TODO program, or better yet, use DELTA feature of Roam to create a repeating reminder. Here is what mine looks like:

+ Backup: EDN & Markdown  {{[[∆]]:4+0}}

Every 4 days on my DNP I get a backup reminder
    - 15/ How long should you keep your backups?
This depends on your needs, but I do my backup every 4 days and put it into a Google Drive folder. I keep the EDN backups for about 2 months, since I won't every fully restore a backup older than that. continued...
    - 16/ But I never delete the Markdown backups. I like to be able to go back in history to any date and get the contents of a page. I am surprised at how often I do go back in time a few months to see what the contents of a page where in the past.
    - 17/ In summary, my backup strategy:
+ Export to EDN & Markdown
+ Backup every 4 days, or on days when have done extensive work
+ Store backups in a cloud storage for easy retrieval
+ Use Delta to get a reminder
+ Keep EDN backups for 2 months, Markdowns I dont delete
    - 18/ Finally have some expressed concern that a $15 month program with no automated or time based backup is disappointing. We can't fault a person if they think that. In comparison, Dynalist is $3 a month & includes automated daily backups to cloud services. So it can be done.
    - 19/ Wow.. a Saturday morning tweeting about Backup strategies. Man, I need to get a life away from Roam at some point :-)

What is your backup strategy? Would love to learn from your best practices. Please tweet back.
