FROM httpd:alpine

COPY ./www/index.html /usr/local/apache2/htdocs/
COPY ./www/index.js /usr/local/apache2/htdocs/
COPY ./www/bootstrap.js /usr/local/apache2/htdocs/

COPY ./pkg/rusty_justy_wasm.js /usr/local/apache2/htdocs/
COPY ./pkg/rusty_justy_wasm_bg.js /usr/local/apache2/htdocs/
COPY ./pkg/rusty_justy_wasm_bg.wasm /usr/local/apache2/htdocs/

# COPY ./rustwasm.conf /usr/local/apache2/conf/httpd.conf