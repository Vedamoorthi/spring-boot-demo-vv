# spring-boot-demo-vv


set DB_URL=jdbc:postgresql://localhost:5432/postgres

set DB_USER=vvairam



initdb.exe -D ../data --username=vvairam --auth=trust


pg_ctl -D ../data start
