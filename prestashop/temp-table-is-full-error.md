# Temp table is full error

If you get an error on a table full, and the table has a random name, it's a full MySQL temporary table.
The size of temporary table is controlled by some MySQL configuration values. In my experience changing the max_heap_table_size is sufficient to solve the problem. (TODO: investigate more, both on MySQL and prestashop. It's a blocklayered module error).