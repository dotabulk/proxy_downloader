# proxy_downloader

connects to MYSQL server using these parameters:

export MYSQL_PROXY_USER=<username>

export MYSQL_PROXY_PASS=<password>

export MYSQL_PROXY_ADDRESS=<ip:port>


it uses :

    import proxy_manager

downloads the requested url(s)

takes care of errors, proxies, timeout, retry(s) ...

and returns the downloaded url file.


proxy_downloader.get(['url','url2',...])
