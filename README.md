# RabbitMQ

1. Make sure to install RabbitMQ and have the service running in the foreground or backgroun: See https://www.rabbitmq.com/install-homebrew.html
Run the following commands
  - brew update
  - brew install rabbitmq
  - export PATH=$PATH:/usr/local/sbin
      *OBS! once PATH is set, restart the computer
      
  - Start server:
   * The server can then be started with 'rabbitmq-server' in the foreground 
   * or with brew services 'start rabbitmq' to have it run under launched in the background.
  - Stop server:
   * sudo -u rabbitmq-server rabbitmqctl stop
