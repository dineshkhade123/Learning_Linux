User Management commands

1 . usermod -u new_id username ------ change user id 
2. usermod -L usename ----- lock user
3. usermod -U sername ---- unlock user
4. usermod -g group_name user_name ----- set goup as primary group of user
5. usermod -G group_name user_name ----- set group as secondary group of user and remove user membership from another groups
6. usermod -aG group_name username ----- set group as secondary group of user and not remove membership of user from another groups
7. usermod -l new_login-name old-login-name --- change login name 
8. usermod -d /new/home/directory/path username --- change home directory
9. useradd --- add new user (without creating home directory)
10. adduser --- add new user with home directory password 
11. passwd username --- set user password
12. useradd -m -g group username ------ add new user with set exist group as primary group 
15. useradd -m -G group1,group2,group3 user_name ------ create user with multiple secondary groups
