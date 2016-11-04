FROM php:7.0-cli
RUN mkdir /app
WORKDIR /app
RUN echo "hello APP2" >> index.php
ENTRYPOINT ["php", "-S", "0.0.0.0:8000"]
