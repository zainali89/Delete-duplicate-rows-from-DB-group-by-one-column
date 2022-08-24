# Delete-duplicate-rows-from-DB-group-by-one-column

DELETE c1 FROM users_data c1
INNER JOIN users_data c2 
WHERE
    c1.user_id > c2.user_id AND 
    c1.data_fid_data_id = c2.data_fid_data_id;
