# git-sendmail-test  
add test message  
git format-patch -s -v 1 -1
git send-email v1-0001-add-test-message.patch --to happyqiurui@163.com --cc happyqiurui@163.com  
git send-email --to 收件人 --cc 抄送人  
git reset commit_id 撤销commit，但是不撤销代码修改  
git reset --hard commit_id 完成撤销,同时将代码恢复到前一commit_id 对应的版本  

