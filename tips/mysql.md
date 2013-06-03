## Table not wrapped

#### command line
    $>  mysql --pager="less -niSFX"

#### inside mysql
    mysql> pager less -niSFX

#### /etc/mysql/my.conf
    [mysql]  
    pager=less -niSFX


## Result in list
Replace `;` by `\G`

    mysql> SELECT * FROM mysql.db LIMIT 0,1\G
