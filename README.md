# inodelimit
inodes limiting, setting quoteas... yadayada

Requiremnents:
>>install quota and quotatools
>>make changes in the fstab stating in the option section that usrquota and grpquota as necessary
>>once don reboot the server
>>quotacheck -aucg... se what happenes, since not sure
>>two ways of doing it setquota and edquota
>> setquota formating

setquota -u -F vsfv0 $username $block_soft_limit $block_hard_limit $inodes_soft $inodes_hard partition

>>repquota -a to check 


