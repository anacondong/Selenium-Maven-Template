How to run:
Start docker-compose >>> docker-compose -f docker-compose.yaml up
run Selenium with connect to selenium hub: mvn integration-test -Dbrowser=chrome -Dheadless=false -Dremote=true -DseleniumGridURL=http://localhost:4444/wd/hub -Dbrowser=chrome


Note:
Selenium Grid: http://localhost:4444/grid/console