

1. List all unique albums that are represented in the "Grunge" playlist.

create view example as
SELECT DISTINICT Playlist = Grunge OR WHERE Playlistid 16


2. How much total money was billed for the TV Show genre?

create view example as
SELECT SUM(Total) WHERE = TV show LIMIT DESC

3. In which countries does Jane Peacock represent clients?

create view example as
SELECT*FROM 'Customer' DISTINCT *Invoicelineid WHERE = Jane Peacock

4. How many customers have no company listed?

create view example as
SELECT*FROM 'Customer' WHERE Company IS NULL  

5. What is the average amount of money spent by customers with gmail addresses?
 
create view example as
SELECT COUNT(*) AVG(Total) FROM `Customer`
