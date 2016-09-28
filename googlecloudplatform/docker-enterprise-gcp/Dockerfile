# Does work when deleting the stored credentials in the local/passwords.conf
# May it be due to storing encrypted credentials? http://blogs.splunk.com/2011/03/15/storing-encrypted-credentials/
# Other useful links related to encryption: https://answers.splunk.com/answers/55256/encrypt-my-password-in-the-configuration-across-servers-with-puppet-deployment-server.html
FROM splunk/enterprise:6.4.3

ENV SPLUNK_BACKUP_APP ${SPLUNK_BACKUP_DEFAULT_ETC}/etc/apps

COPY app-gcp ${SPLUNK_BACKUP_APP}/app-gcp
