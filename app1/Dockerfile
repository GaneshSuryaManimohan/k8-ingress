FROM nginx

# App page
RUN echo "<h1>Hello, this is from APP-1</h1>" > /usr/share/nginx/html/index.html \
    && chmod 644 /usr/share/nginx/html/index.html

# Health endpoint
RUN echo "healthy" > /usr/share/nginx/html/health \
    && chmod 644 /usr/share/nginx/html/health