- Keywords:: #Projects #Books
- Resources:: 
    - {{[[youtube]]: https://www.youtube.com/watch?v=HXV3zeQKqGY}}
- #[[Goals]]:
    - Produce lists of books:
        - That I own. Sources:
            - Onyx
            - Calibre
            - Readdle documents
        - That I have read. Sources:
            - Goodreads
        - That I intend to read or to check out, in priority order
    - Develop routines for updating the lists.
- [[Project Todos]]
    - {{[[TODO]]}} Produce update routine for [[booklist database]] #Booklists
    - {{{[[DONE]]}}}} Write a python script to process the readdle documents list
    - {{{[[DONE]]}}}} Consolidate all booklist data in an Sql database.
- [Active books - notion link](https://www.notion.so/6f446d01b6964d839d5931d8d87b0cfc)
- [[Books on Onyx]]
This table should be tagged with book subjects. 
Method for import of entire book file
    - Start FTP server on Onyx
    - Run Python program "**ftp-directory list.py**". (Output text file name should indicate that this is for the entire list. Eg "**booklist_all_books.txt**")
    - Import the resulting text file to excel. Save as xlsx file with same name.
    - Import excel file to Notion using Import menu.
    - Add tags column, tag book titles (long-term project)
- Method for import of list of new books
    - As above. The text file created by the Python program should be date marked, eg: "**booklist_20200710-20200720.txt**"
    - Import the text file to Excel, remove all older rows.
    - Merge CSV from the resulting excel file to the Onyx booklist table.
**Link:**
https://www.notion.so/05b8c09d3c244d248d6e2f7aa4ae85ce?v=ca4beeec951d48309f4873baa40b7780
- [Books read](https://www.notion.so/9948d390c92440918230a423b9ed4fa3)
- I would like to create a database in Excel and then Notion based on the list of books in [[Calibre]], with the following attributes per book:
    - Title
    - Author
    - In Onyx (boolean)
    - In Readdle documents on [[Ipad]] (boolean)
    - In Ibooks on [[Ipad]] (boolean)
- The database will have to be updated as I add new books to [[Calibre]], Onyx, Documents and Ibooks. 
- The [[Calibre]] list can be generated using the [[Calibre]]db CLI. Example:
**Calibredb --library-path=G:\Calibre-bibliotek list > Calibre-list.txt**
- Import this file to excel using fixed width to identify columns. Filename in position 5 and author in position (55?). Save as excel document and import from there to Notion.
- The list of books on Onyx can be generated using the method described in [[Books on Onyx]] 
- Alternatives for generating a list of books on Readdle Documents:
    - Use the WebDav server in Documents from Readdle.
        - Mount the Webdav server as a Windows drive using "This computer"
![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FDavidsroam%2F2iuBLkJffA.png?alt=media&token=18dbfa54-d8e9-4e95-87e7-02b54cfaad45)
        - Use **Karen's Directory Printer** to generate a text file with all directories and folders.
        - Develop a Python script with the above text file as input and the following output:
            - title 
            - author
            - tags (based on folder structure)
        - Example of text in input file:
FILE	Conscious Writing - Julia McCutcheon_2420.epub	U:\Art and #[[Creativity]]\Creative writing\
- Ibooks:
    - The apple apps are closed, there does not seem to be a way to access the Ibooks file system. At this stage I am leaning toward not including Ibooks in my books catalog. I can read epubs on Readdle Documents. The Ibooks reader is better, so I can use it to read books, but these should also be on Readdle Documents, in order to be included in the main catalog. In order to save space on the [[Ipad]], I should delete books from Ibooks that I am not reading. They can be copied there from Readdle Documents as I need them.
- FTP and WebDav client:
[**Cyberduck | Libre server and cloud storage browser**](https://cyberduck.io/)
- [**Manage files from a computer wirelessly with Wi-Fi Transfer - Readdle Knowledge Base**](https://apphelp.readdle.com/pdfexpert6/index.php?pg=kb.page&id=1144)
- 
