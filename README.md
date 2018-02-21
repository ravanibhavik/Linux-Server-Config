1. Login to Udacity Account using following IP Address and Port.
   IP Address: 35.165.54.170 and SSH Port: 2200
   User: grader, Pwd:
2. Complete URL of hosted web application: http://ec2-35-165-54-170.us-west-2.compute.amazonaws.com/
3. Summary of softwares installed for completing Project:
   apache, flask, sqlalchemy, oauth2client, postgres, mod_wsgi, psycopg2
4. Summary of configuration changes made:
   1) Create authorized_keys file (touch .ssh/authorized_keys)
   2) Change permission for authorized_keys file
      chmod 700 .ssh/
      chmod 644 .ssh/authorized_key
   3) Change sshd_config to disallow login using Root user and password.
   4) Allow sudo permission to grader.
   5) Created new site CatalogApp.conf and enable it.
   6) Created new wsgi (catalogapp.wsgi) for launching Catalog App.
5. No 3rd party resources were used.
