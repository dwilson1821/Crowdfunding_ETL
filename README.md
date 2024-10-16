# Crowdfunding_ETL

We worked on this entire project collaboratively during class time. We referenced previous class projects and homeworks and turned to XPert Learning Assist when we were really stuck.

Phil helped us find an error that was causing all of our dates to change to 1-1-1970 and we learned something about UNIX timestamps along the way.

When we were working on uploading creating our table schema and uploading our CSV files, we ran into snags where we were labeling our data types incorrectly or were not correctly referencing all of the columns in the campaign CSV. Once we recognized our superfluous columns and spelling errors we went back to our notebook and schema altered our code accordingly. To drop our tables, we had to drop campaign first because it had several foreign keys. Reversely, when creating our tables, we created the campaign table last.