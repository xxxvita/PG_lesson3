# PG_lesson3
regress_db=# \di+
                                                 List of relations
 Schema |           Name            | Type  |  Owner   |      Table       | Persistence |    Size    | Description 
--------+---------------------------+-------+----------+------------------+-------------+------------+-------------
 public | pk_project_id             | index | postgres | project          | permanent   | 8192 bytes | 
 public | pk_project_user_id        | index | postgres | project_user     | permanent   | 8192 bytes | 
 public | pk_task_id                | index | postgres | task             | permanent   | 8192 bytes | 
 public | pk_task_step_id           | index | postgres | task_step        | permanent   | 8192 bytes | 
 public | pk_task_step_result_id    | index | postgres | task_step_result | permanent   | 8192 bytes | 
 public | pk_users_id               | index | postgres | users            | permanent   | 8192 bytes | 
 public | task_step_result_dataset  | index | postgres | task_step_result | permanent   | 8192 bytes | 
 public | task_step_result_is_error | index | postgres | task_step_result | permanent   | 8192 bytes | 
(8 rows)

