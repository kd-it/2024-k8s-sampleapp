FROM ghcr.io/kd-it/php-devcontainer/app:1729810622
COPY sampleapp /app
RUN sudo chown -R vscode:vscode /app
USER vscode
RUN composer install
