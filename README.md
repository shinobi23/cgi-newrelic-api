# cgi-newrelic-api
API res service for new relic written with ruby and apache 
# Setup apache web server
Enable CGI execution, a2enmod cgi-bin && a2enmod cgid

# Set file permissions
CentOS => chmod 0705
Debian & Ubuntu => chmod 755
# Install ruby
CentOS => yum -y install ruby
Debian & Ubuntu => apt-get install -y ruby
# Install ruby
Once you get all steps done place all the scripts inside /usr/lib/cgi-bin, then start apache web server and explore your API server.
