#show proccess list
watch -n 1 'echo "show processlist;" | mysql -uroot -proot';

# kill a thread id
kill <thread_id>;
