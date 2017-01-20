# "Temp table is full" error

If you get an error about a full table, and the table has a random name, probably it's a full MySQL temporary table.
The size of temporary table is controlled by MySQL configuration values. In my experience changing the max_heap_table_size is sufficient to solve the problem. (TODO: investigate more, both on MySQL and prestashop. It's a blocklayered module error).