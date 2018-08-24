1. Download xampp for Mac version is 7.2.8
2. Unzip the project in htdocs folder of installed xampp.
3. Check the path of mysqldump . I have already written it but just need to confirm that the same path is there on client machine.
          /Applications/XAMPP/xamppfiles/bin/mysqldump
4. In the phpmyadmin of xampp please run attached commands.
      Hit the url   http://localhost/phpmyadmin/
      Then select test database.
      And then run attached files command.
     This will create table in test database which we are going to backup.
5. Once table is created then hit another url as  http://localhost/LaravelAssignment/public/
6. Then one button named "BACKUP DB" will be there on screen. Click on it and then check the sql dump on following path.
         /Application/xampp/htdocs/LaravelAssignment/storage/app/backups
     Here you will get dump file as databseName_currentTimestamp.sql
