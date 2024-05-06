# HR_Management_Analysis 

### Project Objective

1. gybujnijnujj
``` sql
      SET autocommit = 0;
      start transaction;
          SELECT * FROM STUDENT;
          DELETE FROM STUDENT WHERE STUDENT_ID = 1003;
          SET autocommit = 0;
          commit;
          SELECT* FROM STUDENT;
          rollback
```
